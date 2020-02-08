# Variable en php

En php nous utilisons le *$* comme préfixe pour déclarer une variable, exemple:
```php
$myAge = 20; // 20
```

## convention de nommage

Les variables doivent suivre une convention de nommage:

- le premier charactère du nom de la variable doit impérativement être une lettre ou un souligné (*_*)
- sensible à la casse
- ne pas utiliser de mot clé reservé comme: *this*

exemple:
```php
$this = 20; // error
$0myAge = 20; // error

$_myAge = 20; // 20
$myAge = 20; // 20
```