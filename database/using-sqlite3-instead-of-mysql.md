---
description: Using SQlite3 Instead of Mysql
---

# Using SQlite3 Instead of Mysql

#### Set SQlite DB Path

**system/User/Config.php**

```php
public $sqlite_db = __DIR__ . "/../../PATH_TO_SQLITE_DB ";
```

```
/../../ is Because it Redirects to Root Directory
```

```php
public $db;
function __construct(){
    $this->db = $this->library("sqlite3"); //replace database with sqlite3
}
```

Functions Are Same as Database Library
