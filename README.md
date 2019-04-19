Docker Apache Web Server
========================

This installs Ubuntu 18.04 running an Apache Web Server.

Build with:
```php
docker build -t apache .
```

To map the current directory to the Apache web server run with:
```php
docker-compose up
```

Connect to:
```php
http://127.0.0.1:8080
```


If you're using this with Palo Alto Firewall External Dynamic Lists, connect to
```php
http://w.x.y.z:8080
(where w.x.y.z is your External/Ethernet IP address)
```
and be sure to associate the EDL with a Security Policy Rule for the EDL to populate entries.
