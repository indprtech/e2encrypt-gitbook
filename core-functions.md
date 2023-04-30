# 💻 Core Functions

{% hint style="warning" %}
Some Functions Are Not Intended for Usage in Controllers
{% endhint %}

## loadConfig - Loading Config's

```php
$this->loadConfig()
```

```
Returns any thing in system/User/Config.php
Such as $this->loadConfig()->base_url from public $base_url = "http://localhost:8000";
```

## library($library , $parse0 , $parse1) - Load System Library

```php
$this->library("library");
```

## securityChecks - Checks LibSecurity

```php
$this->securityChecks();
```

## initApp - Inits Application (used in index.php only)

```phpdoc
$this->initApp();
```

## showError($message) - Shows a error message

```php
$this->showError("Nice Job!");
```

## get\_client\_ip - Gets Client IP Address

```php
$this->get_client_ip();
```
