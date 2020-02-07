En javascript nous avons 3 manières de déclarer des variables :


*let* est utilisé pour déclarer une variable ou la valeur risque de changer dans le temps, exemple:
```js
let myAge = 20;

// un an plus tard

myAge = 21;
```
Votre âge changera tous les ans, donc on utilisera le mot clé *let*

*const* est utilisé pour déclarer une constante, donc une variable ou la valeur ne changera pas plus tard. Si vous déclarez une variable et que vous voulez la changer plus tard cela provoquera une erreur, exemple:
```js
const myBirthday = '07/01/2000';

myBirthday = '01/09/1990'; // Error
```
Votre date de naissance ne changera théoriquement jamais dans votre vie, donc on peut dire que c'est une constante et on utilisera donc la mot clé *const*

var était utilisé à l'époque ou let et const n'était pas encore introduit dans le standard (avant ES6). Il n'est aujourd'hui plus conseillé de l'utiliser pour des raisons que nous détaillerons plus tard. Mais si jamais vous le voyais encore dans du dit 'old school' sachez qu'il fonctionne de la même manière qu'un *let*:
```js
var myAge = 20;

myAge = 21;
```