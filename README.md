# arrays_js

- Un array es una zona de almacenamiento continuo, donde se pueden introducir varios valores, cada un de ellos ubicados por la posicion que ocupa en el array.
- Tambien son denominados como arreglos o vectores, y cuando son de dos dimensiones son llamados matrices.
- Los arrays nos brindan la capacidad de almacenar una coleccion de elementos y acceder a ellos de manera individual.
- Cada elemento se identifica mediante su posicion en array denominada **indice**y estos indices son siempre secuenciales.
- En javascript son altamentes flexibles en terminos de los diferentes tipos de datos que podemos almacenar en cada posicion del array.

## Crear un array

1. Declarando una array con elementos en linea 

```Javascript
// Declarando un array con elemento en linea
console.log("--------------------");
console.log("Arrays en Javascript");
console.log("--------------------");
console.log("1. Declarando un array con elementos en lineas");
let miArray = [1,2,3];
console.log(miArray);

```
2. Declarando una array con la sintaxis **new Array()**
```Javascript
let miArray = new Array{1,2,3};
console.log(miArray)
```

3. Declarando un array con un tamaño especifico utilizando la sintaxis **new Array** y asignando valores despues:

```Javascript
let miArray3 = new Array(3);
miArray[0] = 1;
miArray[1] = 2;
miArray[2] = 3;
console.log(miArray3)
```

4. Declarando un array con elementos de difetentes tipos de datos
```Javascript
let miArray4 = [1, "Dos", true, {nombre: "Juan", edad: 30}];
console.log(miArray4)
```

## Accediendo a la informacion de un array

### Propiedad length
- Devuelve la cantidad de elementos del array

### Operador [pos]
- Permite acceder para leer o modificar el elemento pos del array

### Metodo at(pos)
- Devuelve el elemento de la posicion pos. El parametro admite valores negativos, lo que significa que empiezan a contar por el final del array.
```Javascript
const letters = ["A", "B", "C"];
console.log(letters.length);
console.log(letters[2]);
console.log(letters[2]);
```

## Añadir o eliminar elementos
- push(ele1,ele2): Añade uno o varios elementos al final del array. Devuelve el tamaño del array.

```Javascript
let miArray = (1,2,3)
miArray.push(4); // Agrega el elemento 4 al final del array
console.log(miArray);

```

- pop(): Devuelve el ultimo elemento del array y lo elimina

```Javascript
let miArray = (1,2,3)
miArray.pop(); // Elimina el ultimo elemento del array
console.log(miArray);

```

- unshift(ele1,ele2): añade varios elementos al inicio, devolviendo el array despues de aññadido

```Javascript
let miArray = (1,2,3)
miArray.unshift(0); // agrega el elemento 0 al inicio del array
console.log(miArray);

```




## Busqueda de elementos en un array
- includes(elemento): devuelve true o false si el si el elemento existe o no dentro del array
- indexOf(elemento): Devuelve la primera aparicion del elemento si no existe debuelve -1.
- lastIndexOf(elemento): Devuelve la posicion del elemento. Si no existe devuelve -1.
 ## Modificar el array o crear fragmentos
 - slice(inicio, fin): Devuelve un array con los elementos de la posicion inicio hasta la posicion fin, ambos excluidos.

 ## Ordenar elementos de un array
 - reverse(): invierte el orden de los elementos del array
 - sart(): Ordena el array alfabeticamente
 - sort(criterio): Ordena el array con el criterio determinado por la funcion criterio.

 ## Borrar elementos de un array
 - se puede borrar el contenido de un elemento array poniendo su valor a null o asignando una cadena vacia " ".
 - Para eliminar completamente un elemento del array se utiliza el operador delete.

 ## Recorrido de un array
 1. Recordatorio con un bucle basico pasando por todos los elementos.
 ```Javascript
 var dias = ["Lunes","Martes","Miercoles","Jueves","Viernes","Sabado","Domingo"];
 for(i=0;1<dias..lenght;1++)
 {
    console.log(dias(1))
 }
 ``` 
 2. Recordatorio con un while pasando por todos los elementos. 

 3. usando la sentencia for..in
 ```Javascript
  var dias = ["Lunes","Martes","Miercoles","Jueves","Viernes","Sabado","Domingo"];
  for(let index in dias)
  {
    console.log(dias[index])
  }
 ```

 ## Arrays multidimencionales
 ```Javascript
 const matrix = {
    ()

    
 }
 ```

# Ejercicios

1. Dada una lista de números separados por coma, calcular la suma, el mayor, el menor y la media de todos.

2. Introducir dos cadenas con elementos seperados por coma, y con un botón concatenar las dos cadenas y mostrarlas en pantalla.

3. Introducir uno a uno los elementos en un array a través de un boton. Con otro botón se va eliminado el último elemento. Siempre que se pulse alguno de los botones de debe mostrar el contenido del array.

4. Introducir un conjunto de números separados por comas. Cuando se pulsa el botón "Pares" cargar una tabla con los números introducidos y luego crear otra que solo incluya los números pares y mostrarla.
