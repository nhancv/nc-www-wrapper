# nc-www-wrapper
add www prefix to host

```xml
<VirtualHost *:80>
    ServerName nhancv.com
    DocumentRoot "resource dir"
    <Directory "resource dir">
        Options Indexes FollowSymLinks Includes execCGI
        AllowOverride All
        Require all granted
    </Directory>
</VirtualHost>
```

###Usage
access if you access to nhancv.com it auto redirect to www.nhancv.com
