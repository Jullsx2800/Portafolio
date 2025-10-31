# 1️⃣UNIDAD 1📚
## 🧠⚙️ ALGORITMOS, PSEUDOCODIGOS, DIAGRAMAS DE FLUJO.

### ➡️Algoritmos🪜
Defimos algoritmo como: Conjunto ordenado y finito de operaciones que permite hallar la solución de un problema [1]. Usamos esta misma definición para la materia de Computación, sirviendo para el análisis previo, antes de la definición de datos, Establecimiento de valores en la variables, entre otros.

| 🔢 ***Algoritmos Cuantitativos** | 💬 **Algoritmos Cualitativos** | 
| :---:| :---: |
| Los algoritmos cuantitativos son aquellos que involucran cálculos matemáticos y se basan exclusivamente en el procesamiento de datos numéricos (cantidades). | Los algoritmos cualitativos son aquellos cuyas instrucciones se centran en realizar secuencias lógicas u operaciones no numéricas. | 
> Tabla 1.1: Comparación de los tipos de algoritmos.

- A continuación presentaremos un ejemplo que demuestre el aprendizaje, basandonos en los algoritmos de PSeint.

<p align="center">
  <img src="https://intef.es/wp-content/uploads/2023/05/5.jpg" alt="Descripción" width="60%">
</p>

> Fig 1. Algoritmo Pseint

El tema de la misma sera calculo de valores de x mediante la formula general.

En la cual se siguio los siguientes pasos:

1. Definir nombre del algoritmo y sus variables.

2. Pedimos al usuario que ingrese los datos necesarios para llevar a cabo estos procesos, tal como lo son a, b, c (Datos de entrada). Usando el comando:

| **Definir** |
| :---:| 
| **Leer** |

3. Definimos el procedimiento (Proceso) que se debe llevar a cabo el algoritmo. (La fórmula para resolver ecuaciones cuadráticas)

  | **x = (-b ± sqrt(b^2 - 4ac)) / (2a)** |              
| :---:|

- (sqrt) significa raiz cuadrada

4. Mostramos la respuesta basada en el proceso. (Datos de salida).

| **x1 = ....** |
| :---:| 
| **x2 = ....** |
---

### ➡️Pseudocodigo📜
El pseudocódigo es una herramienta utilizada para representar de manera abstracta y simplificada los pasos que un algoritmo debe seguir [2]. Usando una combinacion simple del lenguaje natural y elementos  de programacion, sin seguir especificaciones fijas de un lenguaje avanzado. Siendo de mucha importancia para usuarios que inician en el mundo de la programación.

##### 📁✅Trabajos realizados en Pseudocódigo
Para ello se empleo el programa **PSeint** que es un programa multiplataforma que permite
1) Escribir lgoritmos en pseudocódigo.
2) Ejecutar eficintemente los mismos.
3) Adjuntar diagramas de flujo a los algoritmos empleados.

- A continuación presentaremos un ejemplo que demuestre el aprendizaje:

En el cual usamos el lenguaje de PSeudocódigo "PSeint" donde el lenguaje base para establecer los algoritmos, es el Español (Castellano), donde facilmente podremos realizar un borrador y una vez validado, pasarlo o transformarlo a un lenguaje de programación formal.

<div align="center">
  <img src="https://blogger.googleusercontent.com/img/a/AVvXsEgASFcMGCHpaicoNGQJxAfmW8GQXX0fy7np1aBxMXXFnD8hQ-NnwtboluuZEpR96RfRxNO-Q2XwBgTmjQUlf8s_EduoGeOkwD7xNT8Xl3gXhQP4zYn3sPAkQaE1lgJJomO4sPlzeMWwaRTVU13D9YIqUrjJfnL6IPnVUm6NAzJtWPNA3yQYqpxrc9stZMw=w400-h163" width="800">
</div>

> Fig 2. Pseudocódigo Pseint

En el cual se siguio los siguientes pasos para su correcta isntitucion.

1) Definimos las variables en las cuales se guardaran nuestros valores.

| CambioRecibido | dineroDisponible | costoProducto | 
| :---:| :---: | :---: | 

2) Definimos el proceso que se llevara a cabo en el cual: El usuario establecera el valor de el producto que desea adquirir y cuanto efectivo posee.

Para luego realizar una resta, la cual mostrara cual es el cambio que recibirá. 

| CambioRecibido <- dineroDisponible-costoProducto| 
| :---:| 

3) Para demostrar mas seguridad en nuestro codigo, lo mas correcto seria realizar "Pruebas de escritorio", que son prubas realizadas externamente con varios valores para demostrar que el codigo actua de forma eficiente.

| **dineroDisponible** | **costoProducto** | **Proceso** | **CambioRecibido** |
| :---:| :---: | :---: | :---: | 
| 50 $ | 17.50 $ | 50 $ - 17.50 $ | 32.5 $ |
| 57.36 $ | 35 $ | 57.36 $ - 35 $ | 22.36 $ |
| 85.90 $ | 80.99 $ | 85.90 $ - 80.99 $ | 4.91 $ |
> Tabla 2.1: Pruebas de escritorio.
---

### 📉Diagramas de flujo🧠

Un diagrama de flujo es un diagrama que describe un proceso, sistema o algoritmo informático [3]. Muestra de manera detallada el proceso que se lleva a cabo despues de planificar el algoritmo y definir cada parametro del codigo. Ademas su estructura basada en flechas facilita en entendimiento del mismo y el orden que sigue.

<div align="center">
  <img src="https://blogger.googleusercontent.com/img/a/AVvXsEh8h9mSYbgFCcsH4gZhYOy75xwVk5GG7OLzxiw_2VfqTeyOZhY9FamNpYcdSx-ctPES9kHpQ6QldPPYqCJd5p0Bie4cRzV4hs8YEtuPiUZC6UVyKERYM2u_o0RU9O8KCV5NTtasKMo7lzV1gBk_L9IiaOhsEJquu2uwZAPL_KDwaolVl0FT9SmEMeXV_xM" width="400">
</div>

> Fig 3. Diagramas de flujo

Explicacion del diagrama de flujo:

1) Los recuadros del comienzo y del final en forma de óvalo, determinan el inicio y el final del algorimo como se muestra en la imagen.
2) Los paralelogramos son Los datos de entrada y salida.

**Datos de entrada** -> Datos que necesita el algoritmo para llevar a cabo el proceso establecido en el mismo.

**Datos de salida** -> Datos que arrojara el algoritmo una vez finalizado, en base al proceso y los datos establecidos.

3) Los rectangulos son asiganaciones o proceso que se lleva a cabo en el algoritmo o Pseudocódigo.
 ---
 ## 🧱PROGRAMACION POR BLOQUES🧩
Es un método visual de programacion facil y eficaz,donde se usan bloques gráficos de colores que se arrastran y se sueltan de manera ordenada para que las acciones tomen un rumbo coherente. Evitando lineas de código complejas para principiantes en el mundo de la programación.

A continuacion describiremos un ejemplo de programacion por bloques, en forma de juego interactivo de el sitio "Blockly Games".

<div align="center">
  <img src="https://blogger.googleusercontent.com/img/a/AVvXsEiGREH6F1Fl5MZLRDU2anYC9jDdQHK8IQgOpq1wlx5Usq8ga18tXYP-91b1jB3BhB2qfOVd20c5D6t92P73nIL7z5-Bp3DgTVhwvgZEBc4VjW_vH8QoiANbrf2TJ0NF2RhcTZkPOK22aC1Kzgp4evItC6CyanlRpWYMlHhCe9V1VCrG86HrkWAM0f1-ABc" width="400">
</div>

> Fig 4. Programacion por bloques

En este ejemplo que se presenta a continuacion se utilizo el siguiente proceso:

- Se uso el bloque "Al empezar ejecutar", el cual ejecutara los demas bloques que se le asignen al iniciar el programa.
- Asignamos movimientos como "Mover a la derecha" hasta llevar al tigre al recuadro del churrasco.
- Asignamos al final el bloque "Comer churrasco" para que el tigre coma el churrasco, y finalize el algoritmo.
---

## 🧮EJEMPLOS DE ALGORITMOS CON ESTRUCTURAS LINEALES/SECUENCIALES
Para llevar a cabo este parametro he utilizado un caso basado en la vida real en el cual calculamos el descuento de una prenda, con datos como el precio general, el porcentaje de descuento que tiene, entre otros. Donde usare Pseint y lo transformare a código en C. Usando cada uno para un propósito claro, siendo PSeint un tipo de borrador y luego fue transformado a un lenguaje formal como C.

- ### Ejecución en Pseint (Cálculo del área de un terreno).

<div align="center">
  <img src="https://blogger.googleusercontent.com/img/a/AVvXsEjS3jbmQQ7T-bxl2Xv9i4u2Dk1KJNbT95L9JrAoSVWvOlifz-f7qNRnBsG-Ym5HJxGOjyUqcXmDOuk78YBog4nkBKx-tZ7UKpGOHn4BfsmyZrjoAN_EQkmj0ToGPVZDnJLY7Z_LCTQko-vmzGlXDQ7iKElYlHSHw3OZmNvR_eTuK1trTcS3xKaJabtdXBM" width="700">
</div>

> Fig 5. Código PSeint

- **Pasos a seguir**

1. Definir variables como lo son el largo, ancho, y m2 que resultaran.

2. Pedir al usuario que defina los valores de el alto y ancho del terreno, mediantes los comandos "Definir" y "Leer", donde se guardara el valo de las variables.

| **Definir** |
| :---:| 
| **Leer** |

3. Definimos el proceso que se llevará a cabo para obtener los metros cuadrados totales del terreno.

 | m2 = largo * ancho |              
| :---:|

4. Mostramos el resultado que concluyó el programa, mediante el comando "Escribir". Y para mayor seguridad de los resultados, realizamos pruebas de escritorio de manera oportuna.

| **largo** | **ancho** | **proceso** | **m2** |
| :---:| :---: | :---: | :---: |
| 15 | 16 | 15 * 16 | 240 m2 |
| 5 | 9 | 5 * 9 | 45 m2 |
| 10 | 17 | 10 * 17 | 170 m2 |
> Tabla 3.1: Pruebas de escritorio.

- ### Ejecución en C (Cálculo del área de un terreno).

<div align="center">
  <img src="https://blogger.googleusercontent.com/img/a/AVvXsEg5qGIGy9dfbZ3O0NEXECcnE5FKJVPitlSCMH8mlcKDeS3XMLbSsRVPfSlTjz4d9d0XGyWEpxcVLpINxOOPVO_qlTxBRHS37iH65UONhWo1rqh3wdsppJ0GqVtDPtlpmPN2ZS3yhOedfMsZ1EbnX32rlKI0dp24l3FpgOwDybqA-ZqX0V6zZtAwF5h4ixk" width="700">
</div>

> Fig 6. Código en C

- **Pasos a seguir**

Ya que este lenguaje es un tanto avnzado, incluimos más comandos y el lenguaje base para la elaboracion del algoritmo, por lo que sus pasos son: 

1. Incluir la biblioteca principal de C al inicio del panel.

| **#include <stdio.h>** |
| :---:| 

2. Definimos que tipo de dato tiene cada variable, en este caso usamos datos reales por ello el tipo de dato es "**float**"

  | **float largo, ancho, m2;** |
| :---:| 

3. Integramos en el código, el comando que determina el inicio del algoritmo y otro que determina el fin del algoritmo.

| **int main ( ){** | comienzo |
| :---:| :---:|
| **return 0;  }** | fin |

4. Pedimos al usuario que ingrese los valores que nesecitamos como lo son el largo y ancho del terreno. Mediante el comando "Printf", y al final usando el "\n" para realizar el salto de línea. Ademas el comentario que deseamos que se imprima debe estar parentesis y comillas.

| **printf ("Defina el largo del terreno en metros \n");** | 
| :---:|

5. Usamos el comando "scanf" para pedir al usuario que ingrese los datos necesarios, usando la respectiva máscara del tipo de número y antes de definir en que variable queremos que se almacene el dato usamos el signo "&".

| **scanf ("%f", &largo);** | 
| :---:|

6. Despues de pedir e ingresar todos los datos necesarios, realizamos el proceso debido para el cálculo del área del terreno.

| **m2 = largo * ancho;** | 
| :---:|

7. Definimos los datos de salida, mediante el comando printf, sin olvidarnos de usar la máscara con la que esta registrada el tipo de dato y el salto de línea para mejorar la estética del código.

| **printf ("El area del terreno en metros cuadrados es: \n %f", m2);** | 
| :---:|

- **Dato importante** -> Poner el ";" al final de cada lpinea de código establecida.


Para realizar la correcta comprobación del código usamos las pruebas de escritorio, con lo mismo datos, propuestos en PSeint.

| **largo** | **ancho** | **proceso** | **m2** |
| :---:| :---: | :---: | :---: |
| 15 | 16 | 15 * 16 | 240 m2 |
| 5 | 9 | 5 * 9 | 45 m2 |
| 10 | 17 | 10 * 17 | 170 m2 |
> Tabla 3.1: Pruebas de escritorio (Lenguaje C).
 
---

## 🚧PRINCIPALES DIFICULTADES EN LA APLICACIÓN DE LOS CONTENIDOS🔑

1) Aprendizaje de terminos nuevos en lenguajes como C, ya que usamos el ingles como idioma general para ejecutar los codigos.
2) Memorizacion de terminos nuevos usados para la correcta utilizacion de C como: Mascaras, Bibliotecas, etc.
3) Adaptarse a la simbologia que requiere el funcionamiento de todas las lineas de texto en C.

---

## 🤔REFLEXIÓN CRÍTICA DE LOS APRENDIZAJES DE LA UNIDAD🔍

Durante esta primera unidad en la materia mis conocimientos crecieron de forma considerable, aquellos que mas adelante serviran para mi vida profecional. Tanto su logica, estructura, analisis entre otros. O bien me sirve como punto de partida para lenguajes de códigos mas avanzados. Ademas mi interes aumento en la creación de códigos que ayuden a la gente en su dia a dia. 

---

## 🔗Anexos

En Drive adjuntamos demás ejercicios realizados en cada parámetro de la unidad 1.


📌 [Ejercicios en C](https://drive.google.com/drive/folders/1Fpr3HlxHp85rScE3oWsy1oygDJMRh75y?usp=sharing)

📌 [Ejercicios](https://drive.google.com/drive/folders/15evrrCx_uRe3LYr671QAzcNhpFIH1PBP?usp=sharing)

📌 [Programacion por Bloques](https://drive.google.com/drive/folders/1LI_jRRE-TeBmFX4k9kCq5gXB3iQAo-t-?usp=sharing)

📌 [Diagramas de Flujo - PSeint](https://drive.google.com/drive/folders/18dUN0Wn1Gr08Sr0UUEW3hDAabQzOM_PC?usp=sharing)

📌 [Ejercicios PSeint](https://drive.google.com/drive/folders/17QheQEfBIS9Ezvk9A3kTxGypchW17sva?usp=sharing)

<p align="right">
  <a href="index.md">Volver a la página principal</a>
</p>

