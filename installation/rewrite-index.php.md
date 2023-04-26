# Rewrite index.php

### Apache2

Create a .htaccess file in the root of install\
With Theese Contents

```apacheconf
RewriteEngine on
RewriteCond $1 !^(index\.php|resources|robots\.txt)
RewriteCond %{REQUEST_FILENAME} !-f
RewriteCond %{REQUEST_FILENAME} !-d
RewriteRule ^(.*)$ index.php/$1 [L,QSA]
```

### NGINX

```nginx
location / {
  if (!-e $request_filename){
    rewrite ^(.*)$ /index.php/$1 break;
  }
}
```
