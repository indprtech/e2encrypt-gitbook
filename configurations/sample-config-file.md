---
description: system/User/Config.php
---

# Sample Config File

```php
<?php
class Config {
    //Domain
    public $domain = "localhost:8000";
    public $base_url = "http://localhost:8000";
    public $requireSSL = FALSE;
    public $same_domain = FALSE;

    //Database
    public $database = array(
        'host' => 'localhost',
        'user' => 'root',
        'pass' => '',
        'dbase' => 'test'
    );

    //Encryption
    public $encryption = true;
    // TODO: Change the Secret Key for Producional USE!
    public $secret_key = "1234@1345";
}
```
