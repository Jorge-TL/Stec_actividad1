# Stec_Actividad_1
Semana Tec Actividad 1 PAINT
Este repositorio cuenta con coommits y branches que fueron creados para realizar lo pedido en la actividad 1.

## Tabla de Contenidos
1. [Información General](#general-info)
2. [Collaboration](#collaboration)

## Información General
En esta actividad se busca que el equipo comience a familiarizarse con el uso de los repositorios en GIThub. Es por esto que es necesario crear un nuevo repositorio en donde se ira modificando en diferentes branches el codigo de paint.py con distintas caracteristicas, logrando al final combinar ambas branches en una sola.

Este programa tiene como objetivo simular la famosa aplicación de paint. Nuestro programa cuenta con distinitos modos de dibujo al igual que varias opciones de colores para nuestras figuras.

## Opciones de dibujo (según la tecla que el ususario presione)
### Editar Color
K - Negro
</br>
W - Blanco
</br>
G - Verde
</br>
B - Azul
</br>
R - Rojo
</br>
M - Magenta *Color Agregado al original
</br>
### Editar Modo de Dibujo
l - Linea
</br>
s - Cuadrado
</br>
r - Rectángulo
</br>
c - Círculo
</br>
t - Triángulo
</br>
</br>
Para cada modo fue necesario crear distintas funciones las cuales serán llamadas según la teclea presionada (onkey).
</br>
Asi mismo hcimos modificaciones en las líneas 38 a 43, de la 47 a la 58, de la 62 a la 71 y la 99.
Todos estas modificaciones fueron hechas para optimizar los "juegos" que aparecen en Free Python Games
</br>

## Creación Círculo (Chava27)
Para la creación de la función circulo fue necesario renombrar la función a  circ() a partir de la linea 37, ya que su nombre anterior estaba causando
problemas al momento de utilizar la función circle de turtle. Con esto en mente el programa toma la distancia del primer click en la pantalla con respecto al segundo click, para así calcular el radio del círculo. Despúes de crear el contorno se utilizó la función end_fill() para rellenar el círculo.

## Añadir color extra (Chava27)
Para esta función fue necesario agregar una nueva función onkey en la línea 102, la cual se le asignaba la tecla M con el color magenta, 
por lo que el usuario al presionar esta el color cambiaria al deseado.

## Crear triángulo (Jorge-TL)
Para crear la función de triángulo se basó en el código presentado en el cuadrado, al notar que es una línea que avanza la distancia entre los click y va girando ciertos grados que son predeterminados, en este caso gira 120 grados a la izquierda para formar el angulo interno de 60 que identifica a los triángulos equiláteros, y al ser un triángulo solo repite 3 veces la indicación de avanzar y rotar para cerrar la figura

## Crear rectángulo (Jorge-TL)
Para el rectángulo se basó aún más en el código del cuadrado ya que son figuras similares solo que ahora avanza 2 ocasiones por ciclo, primero va la distancia entre las X y después entre las y, así formamos los dos lados distintos y se repite el ciclo una segunda vez para terminar de cerrar la figura y al igual que el cuadrado avanza de 90 en

## Colaboration
<br/>
Salvador Salgado A01422874 (Chava_27) </br>
Jorge Tamariz A01367223 (Jorge-TL)</br>
