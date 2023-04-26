---
description: >-
  If Encryption is Enabled JSON will be JWT Instead of normal JSON Ouput with
  header application/json
---

# Returning JSON

Response Return JSON

```php
$Request->Response('JSON' , ['status' => true, 'message' => "Hi!"]);
```

**In Action**

```php
<?php
class Welcome extends Controller{
    public $defaultController = "index";
    
    public function index(){
        echo $this->Response('JSON' , ['status' => true, 'message' => "You've Successfully Saw the API!"]);
    }
}
```

