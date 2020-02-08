# Variable en go

En go nous utilisons le mot clé *var* comme préfixe pour déclarer une variable, exemple:
```go
var myAge = 20; // 20
var my_age = 20; // 20

```

## convention de nommage

Les variables doivent suivre une convention de nommage:

- le premier charactère du nom de la variable doit impérativement être une lettre ou un souligné *_* 
- sensible à la casse
- ne pas utiliser de *&*, *$* ou de *-* dans le nom de la variable
- si le nom contient plusieurs mots on utilisera le *snake_case* ou le *camelCase*
- ne pas utiliser de mot clé reservé comme: *func*, *var*, *const*, *import*

exemple:
```go
var my-age = 20; // error
var my$age = 20; // error

var myAge = 20; // 20
var my_age = 20; // 20
```