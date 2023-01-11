# 1 Presentación e introducción a la asignatura


# 2 **GitHub**

**GitHub** facilita la colaboración con **git**. Es una plataforma que puede mantener repositorios de código en almacenamiento basado en la nube para que varios desarrolladores puedan trabajar en un solo proyecto y ver las ediciones de cada uno en tiempo real:

El **github** es una herramienta que usan los programadores que permite guardar en la nube los codigos y archivos que se esta usando para el desarollo de un software, deberes, etc.

![github](C:\Users\fabia\Desktop\ProgramaciónI\markdown\include\github.jpg)



El **github** permite guardar el progreso de codigos y archivos esto mediante la conectividad con la IDE que se use, en nuestro caso en el VSCode permite iniciar sesion con el **github** y desde la IDE mandamos los trabajos a la nube.

Esto es útil por varias razones. Por ejemplo, facilita la resolución de errores y la corrección de otros errores que puedan ocurrir durante el desarrollo. También puede anotar los cambios en cada versión, para ayudar a cualquier miembro del equipo a mantenerse al día sobre lo que se ha completado y lo que aún queda por hacer.


# 3 **Git**

**Git** es un software de VCS local que permite a los desarrolladores guardar instantáneas de sus proyectos a lo largo del tiempo. Generalmente es mejor para uso individual.

Con el **git** podemos observar al momento de trabajar los cambios que se realizan en nuestros proyectos, esta herramienta se puede usar mediante comandos como:

    - **git** init: ingresa el **git** al archivo que queremos que nos  guarde todos los cambios.

    -**git** ignored: herramienta que nos permite descartar archivos del **git** para que no se guarden en la nube o para que no guarde los cambios de dichos archivos.

    -**git** add: comando que nos permite agregar archivos al **git**.

**imagen del git**

![git](C:\Users\fabia\Desktop\ProgramaciónI\markdown\include\git.PNG)

# 4 Workshop

En el workshop de la primera semana trabajamos en equipo esto para aprender a comunicarnos y trabajar con compañeros, esto es debido a que en el ambito laboral de la programación nunca se trabaja solo, siempre hay que saber trabajar con compañeros.

**imagen trabajo en quipo**
![github](C:\Users\fabia\Desktop\ProgramaciónI\markdown\include\equipo.PNG)

# 5 IDE-VSCode

***Una IDE  es un entorno de desarrolo integrado.***

Para la materia de programacion vamos a usar una IDE que podemos personalizar a nuestro antojo ya que permite el uso de varias herramientas para que el usuario se sienta lo mas comodo posible.

***VSCode + git***

con la combinación del VScode y el git vamos a poder realizar nuestro trabajos con las herramientas necesarias para programar.

a parte del git el vs code permite descargar extensiones dentro de la herramienta, esto permite usar varios programas que permita el desarrollo de programas en cualquier tipo de lenguaje de programación, aparte de que las extensiones permiten personalizar de cualquier forma la IDE.

**imagen de las extensiones**

# 6 Markdown

**Markdown herramienta para etiquetar**

***Para el uso del markdown se debe utilizar la extension (.md).***
El mark down es una herramienta que nos permite crear archivos y documentar nuestros proyectos.

Para usar esta herramienta existen varios comandos que permetiran personalizar nuestros trabajos.

Por ejemplo este archivo que contiene la información de las clases de programacion está realizado en el mark down.

Para aprender a usar el markdown existen varias guias en internet donde se detallan los comandos.

**ingresar imgen del markdown**

# 7 Introducción a C vaiables, palabras, reservas

Una vez configurada y personalizada nuestra IDE ya se puede comenzar a programar, en este caso la clase sera de C, un tipo de lenguaje de programación que sirvio como base para la creación de mas lenguajes de programación.

## Librerias

El comando ***#include*** ayuda a incluir librerias a nuestro codigo, las librerias son recursos que uno va a utilizar en un programa como el ***stdio.h*** que es una libreria que permite imprimir y obtener información.

## Compilador
 El compilador que usaremos es el git bash que permite correr programas de c y c++, para compilar debemos escribir en la terminal el siguiente comando:

     gcc src/main.c -o output/main.exe

**¿qué hace un compilador?**

el compilador hace un analisis de sintaxis y un analisis de semantica que lo traduce a lenguaje de computador y ejecuta las instrucciones escritas.

## Palabras reservadas

**int** : declara a una variable como entero

**printf**: permite la salida de texto

**scanf**: permite la entrada de variables

**for**: genera una secuencia

## Declaracion de variables

**variable local**: son variables que se usaran en una sola parte del codigo. 

**variable global**: son variables que se usaran en cualquier parte del codigo.

las variables pueden ser de cualquier tipo: int,char,float,etc.


## **Mi Primer Codigo**

El primer codigo de este curso va a ser el ***"Hello world"***.

Para este codigo usaremos la libreria ***stdio.h***, la cual se a�ade usando ***#include<>***.

Para la funcion **main** se usara la funcion ***int*** como se muestra a continuaci�n:


**Codigo**
___

```c
#include <stdio.h>

int main()
{
	printf("Hello World!\n");

	return (0);
}
```

# 8 Algoritmo, estructura de datos y programas

## Algoritmia

***la algoritmia es el camino para resolver problemas***

1. Problema
2. Solución

    Algoritmos (pseuducódigo)

    Diagrama de flujo

    Código (debuggin)

    Traza (trace) - prueba de escritorio+

1. **PROBLEMA**: ¿Determinar el ára de un rectángulo?
2. **SOLUCIÓN**: areaRectangulo = largo * ancho (metros)
    1. **ALGORITMO** (pseudocódigo)
    ```c
        printf("introduzca longitud");
        scanf("%i",&long);
        printf("introduzca anchura");
        scanf("%i",&anch);
        area=long*anch;
        printf("%i",&area);
    ```
    2. **DIAGRAMA DE FLUJO**

    ![Diagrama](C:\Users\fabia\Desktop\ProgramaciónI\markdown\include\diagrama1.PNG)

# 9-10 Analisis de algoritmos 1

1. **PROBLEMA**: Determinar el mayor de 2 números
2. **SOLUCIÓN**: 10, 30, 5
    **VARIABLES**: a=10, b=30, c=5
    1. **ALGORITMO** (pseudocódigo)
    ```c
        Imprimir "Ingrese el primer valor: "
        Leer a
        Imprimir "Ingrese el segundo valor: "
        Leer b
        Imprimir "Ingrese el tercer valor: "
        Leer c
        Si (a>=b) y (a>=c)
        imprimir "el mayor valor es: " a
        terminar
        Si (b>=a) y (b>=c)
        imprimir "el mayor valor es: " b
        terminar
        Si (c>=a) y (c>=b)
        imprimir "el mayor valor es: " c
        terminar
    ```
    2. **DIAGRAMA DE FLUJO**

    ![Diagrama2](C:\Users\fabia\Desktop\ProgramaciónI\markdown\include\diagrama2.PNG)

# 11 Conceptos básicos y estructura general de un programa



# 12 Tipos, operadores y expresiones

# 13 Control de flujo

# 14 Array

# 15 Estructuras y uniones 

# 16 Enumeradores

# 17 Archivos

# 18 Operaciones con archivos

# 19 Aplicaciones con archivos y estructuras

# 20 ARCHIVOS-entradas y salidas

# 21 Funciones y Módulos
