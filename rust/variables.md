# Variable en rust

En rust nous utilisons le mot clé *let* comme préfixe pour déclarer une variable, exemple:
```rs
let myAge = 20; // 20
let my_age = 20; // 20

```

## convention de nommage

Les variables doivent suivre une convention de nommage:

- le premier charactère du nom de la variable doit impérativement être une lettre ou un souligné *_* 
- sensible à la casse
- ne pas utiliser de *&*, *$* ou de *-* dans le nom de la variable
- si le nom contient plusieurs mots on utilisera le *snake_case*
- ne pas utiliser de mot clé reservé comme: *fn*, *let*, *mut*

exemple:
```rs
let my-age = 20; // error
let my$age = 20; // error

let myAge = 20; // 20, mais on préférera utiliser un *_* pour séparer les mots
let my_age = 20; // 20
```