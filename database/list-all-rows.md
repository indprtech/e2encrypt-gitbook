---
description: List all rows in database
---

# List all Rows

Replace table with the table from what you're going to fetch

```php
$db->list("SELECT * FROM table")
```

Response

```php
array(1) { 
    [0]=> array(4) { 
        ["id"]=> int(1) "1"
        ["name"]=> string(25) "test1" 
    } 
}
```
