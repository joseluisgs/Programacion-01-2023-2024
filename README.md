# Programación - 01 - Introducción a la Programación Software

Tema 01 Introducción a la Programación Software. 1DAW. Curso 2023/2024.

![imagen](https://raw.githubusercontent.com/joseluisgs/Programacion-00-2022-2023/master/images/programacion.png)

- [Programación - 01 - Introducción a la Programación Software](#programación---01---introducción-a-la-programación-software)
  - [Contenidos](#contenidos)
  - [Algoritmos y Programas](#algoritmos-y-programas)
  - [Paradigmas de Programación](#paradigmas-de-programación)
  - [Fases de Programación](#fases-de-programación)
  - [Tipos de Lenguajes](#tipos-de-lenguajes)
    - [Cercanía al programador](#cercanía-al-programador)
    - [Generaciones](#generaciones)
  - [Traductores: Compiladores e Intérpretes](#traductores-compiladores-e-intérpretes)
    - [Lenguaje compilado](#lenguaje-compilado)
    - [Lenguaje interpretado](#lenguaje-interpretado)
    - [Lenguaje mixto o intermedio](#lenguaje-mixto-o-intermedio)
  - [Paradigmas de Programación](#paradigmas-de-programación-1)
  - [Elementos de un Lenguaje de Programación](#elementos-de-un-lenguaje-de-programación)
  - [Referencias](#referencias)
  - [Autor](#autor)
    - [Contacto](#contacto)
  - [Licencia de uso](#licencia-de-uso)

## Contenidos
1. Algoritmos y Programas
2. Paradigmas de Programación
3. Fases de la Programación
4. Tipos de Lenguajes
5. Compiladores e Intérpretes
6. Lenguajes más usados


## Algoritmos y Programas
Algoritmo: secuencia ordenada de pasos, descrita sin ambigüedades, que conducen a la solución de un problema dado.

Los algoritmos son independientes de los lenguajes de programación y de las computadoras donde se ejecutan. Un mismo algoritmo puede ser expresado en diferentes lenguajes de programación y podría ser ejecutado en diferentes dispositivos. Piensa en una receta de cocina, ésta puede ser expresada en castellano, inglés o francés, podría ser cocinada en fogón o vitrocerámica, por un cocinero o más, etc. Pero independientemente de todas estas circunstancias, el plato se preparará siguiendo los mismos pasos.

La diferencia fundamental entre algoritmo y programa es que, en el segundo, los pasos que permiten resolver el problema, deben escribirse en un determinado lenguaje de programación para que puedan ser ejecutados en el ordenador y así obtener la solución.

Los lenguajes de programación son sólo un medio para expresar el algoritmo y el ordenador un procesador para ejecutarlo. Mediante el lenguaje creramos programas que ejecutan uno o más algoritmos en un sistema específico.

En esencia, todo problema se puede describir por medio de un algoritmo y las características fundamentales que éstos deben cumplir son:
- Debe ser preciso e indicar el orden de realización paso a paso.
- Debe estar definido, si se ejecuta dos o más veces, debe obtener el mismo resultado cada vez.
- Debe ser finito, debe tener un número finito de pasos.


## Paradigmas de Programación
Paradigma de programación: es un modelo básico para el diseño y la implementación de programas. Este modelo determinará como será el proceso de diseño y la estructura final de un programa.
Son las reglas del juego. Tienes una pelota o balón y una portería, pero no es lo mismo jugar al fútbol que al balonmano. Pero en ambos tu objetivo es introducir el balón en la portería y anotar más que tu rival. Igual pasa con los lenguajes, existen reglas y según las usemos podremos hacer unas cosas u otras. Tipos: Programación Estructurada, Programación Modular, Programación Declarativa Programación Orientada a Objetos, Programación Reactiva, etc.

## Fases de Programación 
El proceso de creación de software puede dividirse en diferentes fases:
- Fase de resolución del problema: Análisis y Diseño.
- Fase de implementación: Codificación y Pruebas.
- Fase de explotación y mantenimiento.

## Tipos de Lenguajes
### Cercanía al programador
- Alto nivel: C, C++, Java, Kotlin, Python, etc.
- Bajo nivel: ensamblador, máquina, etc.

### Generaciones
- Primera generación: lenguaje maquina. 
- Segunda generación: se crearon los primeros lenguajes ensambladores. 
- Tercera generación: se crean los primeros lenguajes de alto nivel. Ej. C, Pascal, Cobol… 
- Cuarta generación: son los lenguajes capaces de generar código por si solos, son los llamados RAD, con lo cuales se pueden realizar aplicaciones sin ser un experto en el lenguaje.
- Quinta generación: aquí se encuentran los lenguajes orientados a la inteligencia artificial. Ej. LISP 

## Traductores: Compiladores e Intérpretes
La traducción de un programa escrito en un lenguaje de programación a un lenguaje de máquina se realiza mediante un traductor. Este traductor puede ser un compilador o un intérprete. Sus fases principales, son:
- Análisis léxico: se analiza el programa fuente y se separa en tokens.
- Análisis sintáctico: se analiza la estructura del programa y se comprueba que la sintaxis sea correcta.
- Análisis semántico: se comprueba que el programa tenga sentido y que no haya errores.
- Optimización: se realiza una serie de optimizaciones para mejorar el rendimiento del programa.
- Enlazador: se enlazan las librerías necesarias para que el programa funcione.
  
### Lenguaje compilado
Gracias al compiladores se convierte el código a binarios que se ejecutan en el sistema operativo.
### Lenguaje interpretado
Los lenguaje interpretados, necesita de dicho intérprete, que lea la instrucción que se necesita ejecutar, realice el proceso de traducción de la misma y la ejecute.
### Lenguaje mixto o intermedio
Es un lenguaje que se compila a un código objeto o intermedio y se interpreta en una máquina virtual . Ej. Java o Kotlin.

## Paradigmas de Programación
Los lenguajes de programación también se pueden clasificar por paradigmas. Un paradigma de programación es una forma de clasificar los lenguajes de programación según las características y estilos de programación que promueven. Aquí hay una descripción general de algunos de los paradigmas más comunes:

**Programación Imperativa:**

En la programación imperativa, los programas son una serie de comandos que la computadora ejecuta en orden. Los comandos cambian el estado del programa. Los lenguajes de programación imperativa incluyen C, C++, Java y Python.

**Programación Declarativa:**

En la programación declarativa, los programas describen el resultado que se desea, no cómo lograrlo. Los lenguajes de programación declarativa incluyen SQL y HTML.

**Programación Procedimental:**

La programación procedimental es un subtipo de programación imperativa. En la programación procedimental, los programas son una serie de procedimientos o funciones que manipulan el estado del programa. Los lenguajes de programación procedimental incluyen C, Pascal y BASIC.

**Programación Orientada a Objetos (OOP):**

En la programación orientada a objetos, los programas son una colección de objetos que interactúan entre sí. Los objetos son instancias de clases, que contienen datos y métodos que operan en esos datos. Los lenguajes de programación orientados a objetos incluyen Java, C++, Python y Ruby.

**Programación Funcional:**

En la programación funcional, los programas son una serie de funciones matemáticas. Las funciones no tienen estado y no cambian ningún dato. Los lenguajes de programación funcional incluyen Haskell, Erlang y Lisp.

**Programación Lógica:**

En la programación lógica, los programas son una serie de afirmaciones en lógica formal. La computadora deduce la respuesta a una pregunta utilizando estas afirmaciones. Los lenguajes de programación lógica incluyen Prolog y Datalog.

**Programación de Eventos:**

En la programación basada en eventos, el flujo del programa está determinado por eventos, como la entrada del usuario o los cambios en el estado del sistema. Este paradigma es comúnmente utilizado en la programación de interfaces gráficas de usuario y servidores. Los lenguajes que soportan la programación basada en eventos incluyen JavaScript y Python.

Estos son solo algunos de los paradigmas de programación más comunes. Muchos lenguajes de programación soportan múltiples paradigmas. Por ejemplo, Python admite tanto la programación imperativa como la orientada a objetos. La elección del paradigma depende del problema que se esté tratando de resolver y de las preferencias del programador.

## Elementos de un Lenguaje de Programación
Un lenguaje de programación es un lenguaje formal que proporciona un conjunto de instrucciones que permiten a un programador escribir secuencias de comandos, que son interpretadas por una máquina, para producir un comportamiento deseado. Estos lenguajes son utilizados para controlar el comportamiento de las máquinas o para expresar algoritmos.

Los lenguajes de programación constan de varios elementos clave, que incluyen:

**1. Sintaxis:**

La sintaxis de un lenguaje de programación se refiere a las reglas que rigen la estructura de las declaraciones y expresiones válidas en ese lenguaje. Por ejemplo, en el lenguaje de programación Python, la indentación es parte de la sintaxis y se utiliza para delimitar bloques de código.

**2. Semántica:**

La semántica de un lenguaje de programación se refiere al significado de las declaraciones y expresiones. Por ejemplo, en la mayoría de los lenguajes de programación, la expresión "a = b + c" significa que el valor de "b + c" debe ser calculado y luego asignado a la variable "a".

**3. Tipos de Datos:**

Los tipos de datos son los diferentes tipos de valores que pueden ser representados y manipulados en un lenguaje de programación. Los tipos de datos comunes incluyen números enteros, números de punto flotante, caracteres, cadenas y booleanos.

**4. Variables:**

Las variables son símbolos que representan valores en el programa. Las variables tienen tipos, y un valor de un tipo particular puede ser asignado a una variable.

**5. Operadores:**

Los operadores son símbolos que representan operaciones específicas. Por ejemplo, "+" es un operador que representa la adición, y "==" es un operador que representa la comparación de igualdad.

**6. Control de Flujo:**

Las estructuras de control de flujo determinan el orden en el que se ejecutan las instrucciones en un programa. Las estructuras de control de flujo comunes incluyen condicionales (como "if" y "switch" en C++) y bucles (como "for" y "while").

**7. Subrutinas y Funciones:**

Las subrutinas y funciones son bloques de código que pueden ser definidos y llamados por nombre. Permiten la reutilización de código y ayudan a hacer los programas más modulares y más fáciles de entender y mantener.

**8. Comentarios:**

Los comentarios son notas que los programadores dejan en el código para explicar lo que hace el código o por qué se tomó una decisión particular de programación. Los comentarios no son ejecutados como parte del programa.

Estos son solo algunos de los elementos básicos de un lenguaje de programación. Los lenguajes de programación pueden variar ampliamente en términos de qué elementos soportan y cómo se implementan estos elementos.


## Referencias
- http://www.larevistainformatica.com/clasificacion-de-los-lenguajes-de-programacion.html
- https://programas.cuaed.unam.mx/repositorio/moodle/pluginfile.php/1023/mod_resource/content/1/contenido/index.html#:~:text=Un%20lenguaje%20de%20bajo%20nivel,programas%20de%20una%20manera%20sencilla.
- https://profile.es/blog/que-son-los-paradigmas-de-programacion/#:~:text=Un%20paradigma%20de%20programaci%C3%B3n%20es,resultados%20que%20necesitan%20los%20programadores.

## Autor

Codificado con :sparkling_heart: por [José Luis González Sánchez](https://twitter.com/JoseLuisGS_)

[![Twitter](https://img.shields.io/twitter/follow/JoseLuisGS_?style=social)](https://twitter.com/JoseLuisGS_)
[![GitHub](https://img.shields.io/github/followers/joseluisgs?style=social)](https://github.com/joseluisgs)
[![GitHub](https://img.shields.io/github/stars/joseluisgs?style=social)](https://github.com/joseluisgs)

### Contacto

<p>
  Cualquier cosa que necesites házmelo saber por si puedo ayudarte 💬.
</p>
<p>
 <a href="https://joseluisgs.dev" target="_blank">
        <img src="https://joseluisgs.github.io/img/favicon.png" 
    height="30">
    </a>  &nbsp;&nbsp;
    <a href="https://github.com/joseluisgs" target="_blank">
        <img src="https://distreau.com/github.svg" 
    height="30">
    </a> &nbsp;&nbsp;
        <a href="https://twitter.com/JoseLuisGS_" target="_blank">
        <img src="https://i.imgur.com/U4Uiaef.png" 
    height="30">
    </a> &nbsp;&nbsp;
    <a href="https://www.linkedin.com/in/joseluisgonsan" target="_blank">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/ca/LinkedIn_logo_initials.png/768px-LinkedIn_logo_initials.png" 
    height="30">
    </a>  &nbsp;&nbsp;
    <a href="https://g.dev/joseluisgs" target="_blank">
        <img loading="lazy" src="https://googlediscovery.com/wp-content/uploads/google-developers.png" 
    height="30">
    </a>  &nbsp;&nbsp;
<a href="https://www.youtube.com/@joseluisgs" target="_blank">
        <img loading="lazy" src="https://upload.wikimedia.org/wikipedia/commons/e/ef/Youtube_logo.png" 
    height="30">
    </a>  
</p>

## Licencia de uso

Este repositorio y todo su contenido está licenciado bajo licencia **Creative Commons**, si desea saber más, vea
la [LICENSE](https://joseluisgs.dev/docs/license/). Por favor si compartes, usas o modificas este proyecto cita a su
autor, y usa las mismas condiciones para su uso docente, formativo o educativo y no comercial.

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Licencia de Creative Commons" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">
JoseLuisGS</span>
by <a xmlns:cc="http://creativecommons.org/ns#" href="https://joseluisgs.dev/" property="cc:attributionName" rel="cc:attributionURL">
José Luis González Sánchez</a> is licensed under
a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons
Reconocimiento-NoComercial-CompartirIgual 4.0 Internacional License</a>.<br />Creado a partir de la obra
en <a xmlns:dct="http://purl.org/dc/terms/" href="https://github.com/joseluisgs" rel="dct:source">https://github.com/joseluisgs</a>.