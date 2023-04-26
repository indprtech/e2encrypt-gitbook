---
description: Routes are like this /home or /api
---

# Creating New Routes

```php
// src/Routes.php
...
public $routes = [
    '/new_route_name' => array(
        'controller' => "YourControllerName",
        'route' => "index"
    ),
];
...
```
