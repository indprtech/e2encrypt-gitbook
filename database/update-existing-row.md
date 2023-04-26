---
description: Edit Existing Row
---

# Update Existing Row

Table = table name\
1st Array Row = Row and id = id

2nd Array = New Data in Array

```php
$db->edit(
    "table", 
    array(
        "row" => "id",
        "id" => "1"
    ), 
    [
        "col1" => "col2",
        "col2" => "col3"
    ]
);
```

```php
Array(
'STATE' => TRUE,
'MESSAGE' => "Successfully edited",
)
```
