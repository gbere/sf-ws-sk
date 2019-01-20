```php
<?php
// phpstan-shim bug
// add on autoload_real.php
if (false !== \strpos($file, 'phpstan-shim')) {
    return;
}
```
