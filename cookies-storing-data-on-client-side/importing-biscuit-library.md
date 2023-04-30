---
description: >-
  Biscuit Library is used for Cookies in e2encrypt theese cookies are encrypted
  and will not work if the user ip changes!
---

# Importing Biscuit Library

```bash
public $biscuit;
function __construct(){
    $this->biscuit = $this->library("biscuit");
}
```

| Method | Arguments      | What does it does?    |
| ------ | -------------- | --------------------- |
| get    | $name          | Get the Saved Session |
| set    | $name , $value | Set The Session       |
| del    | $name          | Delete The Session    |
