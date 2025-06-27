# Robotica 2025-1 Laboratorio 3

En este repositorio analizaremos y explicaremos las principales diferencias que tienen los manipuladores Motoman MH6 y el IRB140 de ABB, ademas de la comparativa entre los sistemas de desarrollo que usan cada uno para sus simulaciones, RoboDK y RobotStudio. Veremos tambien caracteristicas particulares del robot Motoman MH6 como su velocidad, modos de manejo y su uso manual y remoto.



## Archivos del repositorio
- Lab03_TovarOspina.rdk: Proyecto completo realizado en RoboDK
- RosPolar.py: Scrip diseñado para dibujar una rosa polar en un cuerpo (work-object) determinado.
- README.md: este documento.
- images: carpeta de archivos de imágen usada en README.md.
- video: carpeta donde se encuentra el video de la simulación y la prueba con el robot



## Contenidos
- [Cuadro comparativo entre los dos manipuladores](#cuadro-comparativo)
- [Posiciones de Home](#posiciones-de-home)
- [Movimientos manuales](#movimientos-manuales)
- [Niveles de velocidad](#niveles-de-velocidad)
- [RoboDK](#robodk)
- [Código](#código)
- [Video de implementación](#video-simulación-e-implementación)



## Cuadro Comparativo
Detalles | Motoman MH6 | IRB 140
---------|-------------|-------------
Carga max | ## | ##
Alcance  | ## | ##
GL(Grados Libertad) | ## | ##
Velocidad | ## | ##
Aplicaciones típicas | ## | ## 



## Posiciones de HOME
El manipulador Motoman MH6 tiene guardadas dos configuraciones de referencia (home) que nos permiten garantizar un buen uso de este. Haremos una comparación de estas posiciones y definiremos cual es mejor:

### Home 1:

![](images/home1_1.jpeg)
![](images/home1_2.jpeg)

> Posición de HOME 1.

En esta posición vemos que el robot tiene todas sus articulaciones lo mas cerca posible a su sistema de coordenadas base, el cual se encuentra en la articulacion 1 (la que se ve mas abajo de la imagen). Esta posición permite que el robot ocupe un menor espacio.

### Home 2:

![](images/home2_1.jpeg)
![](images/home2_1.jpeg)

> Posición de HOME 2.

A diferencia de la anterior, en esta posicion vemos una postura mucho mas amplia, con el efector final posicionado de forma que este apunta hacia abajo a una altura determinada por el segundo eslabón. Ademas que su distancia de la base del sistema es aproximadamente la hipotenusa generada por los eslabones 2, 3 y 4, que generan un triangulo rectangulo.

### ¿Cuál es mejor?
Esta pregunta depende mucho del contexto en el que se hace, pues si se requiere realizar un proyecto, algún trabajo u operación, la posición 2 es mucho mejor, pues dispone sus articulaciones mejor hacia un objeto que se encuentre frente al manipulador. Sin embargo, si se requiere simplemente trasladar el robot a algún lugar, o simplemente se quiere almacenar, la posición 1 es mucho mejor, pues es mucho mas compacta.



## Movimientos manuales
El robot Motoman MH6 dispone de un controlador DX100



## Niveles de velocidad
Niveles



## RoboDK
Manual de robodk

### RoboDK vs. RobotStudio
Comparacion


## Código
Codigo en python



## Video: simulación e implementación
Se presenta la simulación e implementación correspondientes a lo descrito anteriormente en el siguiente enlace de YouTube: https://youtu.be/p57teWZQysk