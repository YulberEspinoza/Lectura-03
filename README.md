# Lectura-03

## Aprende HTML
### ¿Cuándo se puede utilizar una lista no ordenada en tu documento HTML?
Cuando querramos utilizar un conjunto de lista que no tiene relación con los otros elementos.

### ¿Cómo cambias el estilo bullet de la lista de elementos no ordenados?
Podemos hacerlo con el siguiente código:
ul { list-style-type: ***; }

### ¿Cuándo debes usar una lista ordenada o lista no ordenada en tu documento HTML?
ol Cuando los elementos son ordenados y tienen relación.
ul Cunado el orden de los elementos no requiera tener una relación.
  
### Describe dos formas en las que puedes cambiar los números en los elementos de la lista proporcionados por una lista ordenada
Podemos utilizar el siguiente código:
ol start="10"
ol type="j"

## Aprende CSS
### Describe las propiedades de margin y padding en CSS como si fueran los personajes de una historia. ¿Cuál es su rol en la historia: “El Box Model”?

Margin es un ente que ayuda que las personas tengan un espacio entre lineas.
Padding es un ente que ayuda que los elementos tengan un espacio.

### Enumera y describe las cuatro partes de un box del elementos HTML según el box model.
Content: Donde se presenta el contenido
Padding: El espacio entre el contenido y el borde del elemento.
Border: El borde alrededor del padding y el contenido.
Margin: El espacio afuera del borde, separando el elemento de otros elementos circundantes.

## Aprende JS
### ¿Qué tipos de datos puedes almacenar en un Array?
Es un array cuando son: cadenas, números, objetos, variables e incluso otros arreglos.

### ¿El array people es un array de JavaScript válido? De ser así, ¿cómo puedo acceder a los valores almacenados? Y si no, ¿por qué?
const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant','fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];
Si es un array es valido y para acceder a los valores debemos encadenarlo dos pares de corchetes.

### Enumera cinco operadores abreviados de asignación en javascript y describe lo que hacen.
ASIGNACION DE ADICION: X +=Y: Suma el valor de Y al valor de X para luego almacenr el resultado en X
ASIGNACION DE RESTA: X -=Y: Resta el valor de Y al valor de X para luego almacenr el resultado en X
ASIGNACION DE MULTIPLICACION: X *=Y: Multiplica el valor de Y al valor de X para luego almacenr el resultado en X
ASIGNACION DE DIVISION: X /=Y: Divide el valor de Y al valor de X para luego almacenr el resultado en X
ASIGNACION: X=Y: El valor de x es asignado a y.

### Lee el código a continuación, evalúa la última expresión y explica cuál sería el resultado y por qué.

let a = 10;
let b = "dog";
let c = False;
//evalúa esto
(a+c)+b;
Hay muchos valores que no tienen la misma estructura ya que hay numero, letras y valor, por lo tanto el dato que rebotará será el siguiente: "10dog".

### Describe un ejemplo cotidiano de por qué una declaración condicional se debería usar en un programa en JavaScript.
Una de las formas en las que se podría utilizar el concepto del if, cuando realizamos el siguiente uso:
if(comprobación){
valor positivo;
}else{
valor negativo;
}
