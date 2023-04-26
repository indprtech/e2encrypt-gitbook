# Add New Row

Table = The Table Name

Next is arrays of colums to add

```php
$db->add(
    "table" , 
    [
        "col1" => "col2",
        "col2" => "col3"
    ]
)
```

<pre class="language-php"><code class="lang-php">Returns
Array(
<strong>   'STATE' => TRUE,
</strong>   'MESSAGE' => "Successfully added",
   'INSERT_ID' => "1"
)
</code></pre>

