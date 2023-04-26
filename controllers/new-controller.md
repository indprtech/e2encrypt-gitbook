# New Controller

<mark style="color:blue;">**src/Controller/HomeController.php**</mark>

```php
<?php
class Home extends Controller{
    public $defaultController = "index";

    public function index(){
        $this->view("home");
    }
    
}
```

<mark style="color:blue;">**src/Views/home.view.php**</mark>

```
<h4>Hello!</h4>
```
