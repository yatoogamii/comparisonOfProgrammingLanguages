# Variable en javascript

En javascript nous avons 2 manières de déclarer des variables, *let* et *var*. 

## var

*var* est un mot clé utilisé avant ES6 (ECMAScript 2015), nous pouvons encore le voir dans certain script aujourd'hui mais il est conseillé d'utiliser plutôt le nouveau mot clé introduit avec ES6 *let* pour des raisons que nous détaillerons plus tard, voici quand même un exemple:
```js
var myAge = 20; // 20
```

## let

*let* est un mot clé utilisé depuis ES6, il permet de déclarer une variable. Il se comporte visuellement exactement comme *var* exemple: 
```js
let myAge = 20; // 20
```

## convention de nommage

Les deux doivent suivre une convention de nommage:

- le nom de la variable doit contenir seulement des lettres, nombres, ou le symbole $ et _.
- le premier charactère du nom de la variable ne doit impérativement pas être un chiffre
- sensible à la casse
- ne pas utiliser de mot clé reservé comme: *function*, *this*, *let*, *var*, *const*, *class*, *import*, *extends*, *export*...

exemple:
```js
var 0myAge = 20; // error
let @myAge = 20; // error
let function = 20; // error

var _myAge = 20; // 20
let $myAge = 20; // 20
```