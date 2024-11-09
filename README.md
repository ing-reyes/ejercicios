# Ejercicios de la sección 1

## Ejercicios Básicos


1. __Sumar todos los elementos de un array de números__. Crea una función que reciba un array de números y devuelva la suma de todos sus elementos.

```
const array = [ 1, 5, 6, 1, 7, 8, 9 ];

function sum(array){
    // Lógica...
}
// Salida: 37
```

2. __Encontrar el número mayor en un array__. Crea una función que reciba un array de números y devuelva el número mayor.

```
const array = [ 5,1,8,9,3 ];
function largestNumber( array ){
    // Lógica...
}
// Salida: 9
```

3. __Invertir el orden de los elementos en un array__.
Crea una función que invierta el orden de los elementos de un array sin usar el método reverse().

```
const array = [ 'carmen', 'marcos', 'jose', 'beatriz' ];

function invert(array){
    // Lógica...
}
// Salida: ['beatriz, jose, marcos','carmen']
```

4. __Filtrar los elementos de un array de números mayores que 10__. Crea una función que filtre y devuelva los elementos de un array de números que sean mayores que 10.

```
const array = [ 4, 7, 10, 11, 20, 4, 21 ];
function filter(array){
    // Lógica...
}
// Salida: [11, 20, 21]
```

5. __Crear un array de strings con la primera letra de cada palabra de un array de strings__. Crea una función que reciba un array de strings y devuelva un nuevo array con la primera letra de cada string.

```
const array = [ 'alberto', 'luis', 'david', 'carina' ];
function transform( array ){
    // Lógica...
}
// Salida: ['a','l','d','c']
```

6. __Eliminar los elementos duplicados en un array de números__. Crea una función que elimine los números duplicados en un array.

```
const array = [ 1,5,4,8,9,1,2,4 ];
function noDuplicate(array){
    // Lógica...
}
// Salida: [ 1,5,4,8,9,2 ]
```

7. __Encontrar un string dentro de un array de strings__. Crea una función que reciba un array de strings y un string objetivo, y devuelva true si el string objetivo se encuentra en el array.

```
const array = ['jose', 'leandro', 'carlos', 'marcos'];
const string = 'marcos';

function searchString(array, string){
    // Lógica...
}
// Salida: true
```

8. __Contar cuántas veces aparece un valor en un array__. Crea una función que reciba un array y un valor, y devuelva la cantidad de veces que ese valor aparece en el array.

```
const array = [ 1,2,3,4,5,6,7,1 ];
const value = 1;
function countValue(array, value){
    // Lógica...
}
// Salida: 2
```

9. __Comprobar si un array está vacío__. Crea una función que reciba un array y devuelva true si el array está vacío, y false si no lo está.

```
const array = ['typescript','javascript','nestjs'];

function arrayIsEmpty( array ){
    // Lógica...
}
// Salida: false
```

10. __Concatenar dos arrays__. Crea una función que reciba dos arrays y devuelva un nuevo array concatenado.

```
const array1 = ['jose','marta','sandra'];
const array2 = ['pedro','juan','tomas'];

function concatArray(array1, array2){
    // Lógica...
}
// Salida: ['jose','marta','sandra','pedro','juan','tomas']
```

11. __Convertir un array de números a strings__. Crea una función que reciba un array de números y lo convierta en un array de strings.

```
const array = [1,2,3,4,5,6,7,8,9];

function convertToString(array){
    // Lógica...
}
// Salida: ['1','2','3','4','5','6','7','8','9']
```

12. __Unir todos los elementos de un array en un solo string__. Crea una función que reciba un array de strings y los una en un solo string, separados por comas.

```
const array = [ 'carolina','marcos','carmen' ];

function unio( array ){
    // Lógica...
}
// Salida: 'carolina,marcos,carmen'
```

13. __Encontrar el índice de un elemento en un array__. Crea una función que reciba un array y un valor, y devuelva el índice del primer elemento que coincida con el valor.

```
const array = [ 5, 2, 8, 2 ];
const value = 2;

function searchValue(array, value){
    // Lógica...
}
// Salida: 1
```

14. __Eliminar un elemento en una posición específica de un array__. Crea una función que reciba un array y un índice, y elimine el elemento en esa posición.

```
const array = ['marialys','marla','yensy','sofia'];
const index = 2;

function removeElement(array, index){
    // Lógica...
}
// Salida: ['marialys','marla','sofia'];
```

15. __Crear un array de números consecutivos__. Crea una función que reciba dos números a y b, y devuelva un array con todos los números consecutivos entre a y b (inclusive).

```
const array = [1,2,3,4,5,6,7,8,9,10];
const a = 3;
const b = 8;
function consecutive( a, b ){
    // Lógica...
}
// Salida: [3,4,5,6,7,8]
```

## Ejercicios Intermedios

1. __Ordenar un array de números de menor a mayor__. Crea una función que reciba un array de números y lo ordene de menor a mayor.

2. __Ordenar un array de strings alfabéticamente__. Crea una función que reciba un array de strings y lo ordene alfabéticamente.

3. __Eliminar los elementos nulos o indefinidos de un array__. Crea una función que reciba un array y elimine todos los elementos null y undefined.

4. __Convertir un array de strings a minúsculas__. Crea una función que reciba un array de strings y lo convierta todo a minúsculas.

5. __Encontrar el índice de un objeto dentro de un array de objetos__. Crea una función que reciba un array de objetos y un objeto de búsqueda, y devuelva el índice del objeto en el array.

6. __Buscar un valor en un array de objetos por una propiedad__. Crea una función que reciba un array de objetos y una clave, y devuelva el objeto que contiene esa clave.

7. __Sumar los valores de una propiedad en un array de objetos__. Crea una función que reciba un array de objetos y una propiedad, y devuelva la suma de los valores de esa propiedad.

8. __Crear un nuevo array con los valores de una propiedad de un array de objetos__. Crea una función que reciba un array de objetos y una propiedad, y devuelva un nuevo array con los valores de esa propiedad.

9. __Contar cuántos elementos cumplen con una condición en un array__. Crea una función que reciba un array y una condición (como "ser mayor que 10"), y cuente cuántos elementos cumplen con la condición.

10. __Verificar si todos los elementos de un array cumplen con una condición__. Crea una función que reciba un array y una condición, y devuelva true si todos los elementos cumplen con la condición.

11. __Agrupar elementos de un array de objetos por una propiedad__. Crea una función que reciba un array de objetos y una propiedad, y agrupe los objetos por esa propiedad.

12. __Obtener los elementos que están en el primer array pero no en el segundo__. Crea una función que reciba dos arrays y devuelva los elementos que están en el primero pero no en el segundo.

13. __Verificar si al menos un elemento cumple con una condición en un array__. Crea una función que reciba un array y una condición, y devuelva true si al menos un elemento cumple con la condición.

14. __Eliminar elementos de un array según una condición__. Crea una función que reciba un array y una condición, y elimine todos los elementos que cumplan esa condición.

15. __Encontrar el primer valor único en un array__. Crea una función que reciba un array y devuelva el primer valor que no se repite.

## Ejercicios Avanzados

1. __Buscar el objeto más grande en un array de objetos__. Crea una función que reciba un array de objetos y encuentre el objeto con la propiedad size más grande.

2. __Transformar un array de strings en un objeto donde las claves sean los strings__. Crea una función que reciba un array de strings y devuelva un objeto cuyas claves sean esos strings, y los valores sean sus longitudes.

3. __Contar la frecuencia de los elementos en un array de objetos__. Crea una función que reciba un array de objetos con propiedades similares y devuelva un objeto con la frecuencia de cada valor.

4. __Desestructurar un array de objetos y devolver un array de propiedades específicas__. Crea una función que reciba un array de objetos y extraiga una propiedad específica de cada objeto, devolviendo un array de esas propiedades.

5. __Fusionar dos arrays de objetos sin duplicar__. Crea una función que reciba dos arrays de objetos y los fusione sin duplicar los objetos que tengan la misma propiedad id.

6. __Crear un array de objetos ordenado por una propiedad numérica__. Crea una función que reciba un array de objetos y los ordene por una propiedad numérica, como age.

7. __Agrupar un array de objetos por un conjunto de propiedades__. Crea una función que reciba un array de objetos y devuelva un objeto donde las claves sean combinaciones de propiedades (por ejemplo, name y age), y los valores sean arrays de objetos que compartan esa combinación.

8. __Eliminación condicional de propiedades de un array de objetos__. Crea una función que reciba un array de objetos y elimine propiedades específicas de esos objetos basándote en una condición.

9. __Crear un array de objetos a partir de un array de strings usando map()__. Crea una función que reciba un array de strings y convierta cada string en un objeto con la propiedad value igual al string.

10. __Realizar una búsqueda en un array de objetos con una función de filtro compleja__. Crea una función que reciba un array de objetos y filtre solo los objetos que cumplen con varias condiciones (por ejemplo, edad > 18 y nombre contiene "John").

11. __Ordenar un array de objetos alfabéticamente y numéricamente__. Crea una función que reciba un array de objetos y lo ordene alfabéticamente por nombre, y luego por edad de manera numérica.

12. __Crear una tabla de frecuencias a partir de un array de objetos__. Crea una función que reciba un array de objetos y devuelva un objeto donde las claves sean los valores de una propiedad específica, y los valores sean la cantidad de veces que ese valor aparece.

13. __Eliminar todos los elementos que contienen un valor nulo en un array de objetos__. Crea una función que reciba un array de objetos y elimine aquellos objetos donde una propiedad tenga un valor null.

14. __Aplanar un array de arrays en un solo array__. Crea una función que reciba un array de arrays