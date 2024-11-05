<!--lenguaje markdown
objetivo: proporcionar una herramienta para documentar codigo, o aspectos tecnicoa para compartirlos o tenerlos de refenrecia en mi git hub o otra plataforma.

markdown es un lenguaje de marcado ligero 

el objetivo de su creador fue hacer quela gente pudiera escribir usando un formato de texto plano facil de leer
facil de escribir y con la posibilidad de convertir su documento en html valido.

la gran simpleza de su sintaxis hizo que tuviera una rapida adopcion y popularidad en la comunidad de desarrolladores.

actualmente aparte de permitir generar contenido html de forma dinamica, tambien se emplea (casi de forma estandar)
para la creacion de documentacion tecnica y con la proliferacion de la arquitectura JAM Stack para la creacion de sitios estaticos a traves de herramientas de tipo SSG(static site generator) y ssr (sergey side rendering) como hugo, gatsby, eleventy, next js, sergey

conocer sintaxis Markdown

1.-parrafos [parrafo 1...]
Lorem Ipsum es simplemente el texto de relleno de las imprentas y archivos de texto. Lorem Ipsum ha sido el texto de relleno estándar de las industrias desde el año 1500, cuando un impresor (N. del T. persona que se dedica a la imprenta) desconocido usó una galería de textos y los mezcló de tal manera que logró hacer un libro de textos especimen.-->

Cursiva
*negrita*
tachado
*cursiva y negrita*
cursiva y tachado
*negrita y tachado*
*cursiva, negrita y tachado*

Encabezado

# Encabezado nivel 1
## Encabezado nivel 2
### Encabezado nivel 3
#### Encabezado nivel 4
##### Encabezado nivel 5
###### Encabezado nivel 6

Divisiones

un bloque de contenido
---
este es otro bloque de contenido

listas: podemos utilizar las listas ordenadas y desordenadas

1. html5
1. css
1. javascript
1. ajax
1. json

-html5
-css
-javascript
-ajax
-json 

citas podemos dar formato de cita a un texto, anteponiendo a la linea de texto un caracter de mayor que (>).

la IA en el futuro reemplazara muchas profeciones de TI. -Ad Nasser

chatgpt debe potenciar mi aprendizaje, no suprimir mi estado autodidacta.

Ad Nasser

Enlaces 
[youtube](https://www.youtube.com)
[enlace a google](https://www.google.com)

Imagenes
![texto alternativo] (URLdelaimagen)

Tablas

|Columna 1 |Columna 2|Columna 3|
|----------|---------|---------|
|A         |B        |C        |
|D         |E        |F        |
|G         |H        |I        |

Codigo
podemos dar formato de codigo aun texto para ello se usa el cento grave (`).

esto es`codigo` en linea.

en javascript  una variables se define asi:
let saludo = "Hola Mundo";

pero si queremos sacar un bloque completo de codigo utilizamos':
js
let estudiante="juan perez";
let edad=19;
let isestudiante=true;
let calificacion=90.0;



<!--esto es un comentario-->



// alert("Estamos en el archivo de estructuraciclo.js")

for(let i=0;i<=10;i++){
    console.log("[for]No iteracion: "+i);
}
  let contador=1;

  while (contador<10){

    console.log("[while]No iteracion: "+contador);
    contador++;
}
//do / while
let numero=1;
do{
    console.log("[do/while ]No iteracion"+numero);
    numero++;
}while(numero<10);

//for in

let estudiante={nombre:"Alexander", edad:18, calificacion :70};
for(let propiedad in estudiante){
    console.log(propiedad+ ": " +estudiante[propiedad]);
}

//for.. of
//Este ciclo itera sobre los valores de un objeto iterable (como un array).

let mis_numeros=[10, 20, 30, 40, 50];

for (let  numero of mis_numeros){
	console.log(numero);
}


// JavaScript

//Asi se utilizan los comentarios en JavaScript de una sola LInea 


console.log("Bienvenidos al mundo de la programacion FrontEnd con JavaScript");

console.log("Esta es otra linea "+"y se conecta con el mas +");


//Asi se utilaza los comentarios en javascript de una sola linea

console.log("Bienvenido alk mundo de la programcion fronend con javascript")
console.log("Esta es otra linea "+"Y se concatena con el +");


/*
Este es un comentario de mas de una linea
*/

/*
En java Script no existe  un compilador dado que es un lenguaje interpretado. Es por ello
que debemops utilizar la instruccion console.log para monitorear el avance y flujo de la logica
que implemntamos.Sin embargo chrome ofrece unas herramientas para revisar los errores
*/ 

//Ahora vamos a trabajar con  declaracion de variables:
let estudiante="jazmin"
let edad=20;
let isEstudiante=true;
let calificacion=83.0 

let num1=8
let num2=4

console.log("Estudiante: "+estudiante);
console.log("Edad "+edad);
console.log("¿Estudia?: "+isEstudiante);
console.log(typeof calificacion);

console.log(` El promedio global del estudiante es ${calificacion} `);

console.log("La suma es: "+(num1+num2));
console.log("La resta es: "+(num1-num2));
console.log("La multiplicacion es: "+(num1*num2));
console.log("La division es: "+(num1/num2));


let val1;
let val2;
    val1=prompt("Ingresa un primer numero ");
    val2=prompt("Ingresa un segundo numero ");

let nume1=parseInt(val1);
let nume2=parseInt(val2);
        console.log("La suma es "+(nume1+nume2))
/*
Java script es un lenguaje debilmente tipeado, esto signific que no es estricto en la declaracion
de tipos de datos. Es decir, no fuerza a que inicialmente digas es tipo de dato de la variable. Y esta 
pueda cambiar en el transcurso de logica por otro tipo de datos segun la necesidad.

*/




