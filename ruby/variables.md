# Variable en ruby

En ruby nous devons juste écrire le nom de notre variable pour la déclarer, exemple:
```rb
myAge = 20; // 20
```

## convention de nommage

Les deux doivent suivre une convention de nommage:

- sensible à la casse
- ne pas utiliser de mot clé reservé comme: *this*
- ne pas utiliser de *&* ou de *-* dans le nom de la variable
- snake case

exemple:
```rb
my&Age = 20; // error
my-age = 20; // error

myAge = 20; // 20, mais on préférera utiliser un *_* pour séparer les mots

my_age = 20; // 20
```