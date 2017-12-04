# Get Real IP from user

## Description

This PHP script get the real IP from an user.

## Install via composer

Just run the following command in your project root :

```
composer require machou/real-ip
```

## Example PHP

```php
<?php
require_once '/path/to/ip.php';

$user_ip = getUserIP();

echo $user_ip; // Output IP address [Ex: 177.87.193.134]
```

## License

The script Real IP are distributed under the [The MIT License](https://opensource.org/licenses/MIT).
