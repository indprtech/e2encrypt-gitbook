# Database Setup

```php
public $database = array(
        'host' => 'hostname',
        'user' => 'username',
        'pass' => 'password',
        'dbase' => 'database'
);
```

After That Load the Library in the Controller

```php
public $db;
function __construct(){
    $this->db = $this->library("db");
}
```

Full Controller Code with Database Loaded

```php
<?php
class Welcome extends Controller{
    public $defaultController = "index";

    public $db;
    function __construct(){
        $this->db = $this->library("db");
    }

    public function index(){
        $this->view("hello-e2e");
    }
}
```

