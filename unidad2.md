# 1️⃣UNIDAD 2📚

---

---

## ESTRUCTURAS CONDICIONALES ##
### Estructura Condicional Simple -- "if" ###
El if es un mecanismo escencial en el código, que perimte ejecutar un cierto bloque de código en base a una condición específica, o una toma selectiva de desiciones en base a una condición definida.
#### Ejemplo usando la estructura condicional "if" ####

- Descripción del Problema
  
El problema que se plantea consiste en que el usuario establesca dos numeros reales por teclado y en base a sus valores. Si el segundo numero es mayor o igual al primer numero estos se sumaran, caso contrario, culminará el programa.

- Codigo en C

```

 #include <stdio.h>

 int main ( ){

    float valor1, valor2, resultadoPo;

    printf ("Escriba el primer valor: \n ");
    scanf ("%f", &valor1);

    printf ("Escriba el segundo valor: \n ");
    scanf ("%f", &valor2);

    if (valor1 <= valor2 ){

        resultadoPo = valor1 + valor2;

        printf(" La suma de los numeros son: %.2f \n", resultadoPo); 

    }

    return 0;

 }

```
> Cuadro de código 1: Suma de valores definidos

##### Explicación del código C #####
Se incluyó primeramente la librería principal de C, posteriormente el inicializador y seguido el código, el cual define lo valore como reales y pide al usuario ingresar 2 valores. Luego de ejecutara una condición, que consta en sumar los numeros SI el segundo valor es mayor o igual al primero, si esto no se lleva a cabo el programa finalizará. 

- Pruebas de escritorio.

| **Valor 1** | **Valor 2** | 
| :---:| :---: |
| 50 | 17.5 |
| 55 | 129 | 

> Tabla 1: Pruebas de escritorio (Condicional Simple).


<div>
  <img src="https://cdn.discordapp.com/attachments/1347778788964040717/1447440652936941629/image.png?ex=6937a1a7&is=69365027&hm=deea87047460ae4104d9ba1087fecddbd166e8ea794d0e01b459b6dcb61654db&" width="600">
</div>

> Fig 1.1: Primer caso PE


<div>
  <img src="https://cdn.discordapp.com/attachments/1347778788964040717/1447441087625957416/image.png?ex=6937a20f&is=6936508f&hm=a1f169d4345f3fee3f462bb1f2c53edc4e5a1ae4cd1694631bcdbd4f8f0d2d01&" width="600">
</div>

> Fig 1.2: Segundo caso PE

>

- Diagrama de flujo (Estructura condicional simple)

<div align="center">
  <img src="https://cdn.discordapp.com/attachments/1347778788964040717/1447442409523908658/image.png?ex=6937a34a&is=693651ca&hm=ec7b675ae0689bab584244fec1539d93737827d4cb50735722dc4a285d6b9e91&" width="600">
</div>

> Fig 2: Diagrama de flujo (Estructura condicional simple)

---

### Estructura Condicional Doble -- "if-else" ###
Se utiliza para definir dos caminos de ejecución, que se excluyen mutuamente, permitiendo que solo se lleve a cabo una, en base a las condiciones propuestas. Si se cumple la condición Se cumple algo, y si no se cumple se ejectuta otra alternativa de código.
#### Ejemplo usando la estructura condicional "if-else" ####

- Descripción del Problema
  
El problema que se plantea consiste en que el usuario establesca un número entero, y en base a una condición doble, se mostrará un mensaje determinado.

- Codigo en C

```

 #include <stdio.h>

int main ( ){

    int numero;

    printf ("Ingrese el numero de desea analizar \n ");
    scanf("%i", &numero);

    if (numero >=10 && numero <=20)
    {
        printf ("El numero se encuentra en el rango \n");
    }else{

        printf ("El numero no se encuentra en el rango \n");
    }


    return 0;

}

```
> Cuadro de código 2: Determinar el rango

##### Explicación del código C #####
Se solicita al uuario ingresar un número y en base a ello, se evalua que se encuentre en un rango determinado, si cumple la condicion y se encuentra dentro del rango se mostrará el mensaje correspondiente y si no tambien se mostrará un menaje correspondiente. 

- Pruebas de escritorio.

| **Número** | 
| :---:| 
| 15 | 
| 30 |

> Tabla 2: Pruebas de escritorio (Condicional Doble).


<div>
  <img src="https://cdn.discordapp.com/attachments/1347778788964040717/1447447614864883854/image.png?ex=6937a823&is=693656a3&hm=319f972cc18ca5a8edb74a8a2440c742b2951918fc8e112777aaf3335d4f73f5&" width="600">
</div>

> Fig 3.1: Primer caso PE


<div>
  <img src="https://cdn.discordapp.com/attachments/1347778788964040717/1447447947653419121/image.png?ex=6937a873&is=693656f3&hm=6d045792d017e27a50b554e33b8960cdc34f10a5c145b0233ad14639415484e7&" width="600">
</div>

> Fig 3.2: Segundo caso PE

>

- Diagrama de flujo (Estructura condicional doble)

<div align="center">
  <img src="https://cdn.discordapp.com/attachments/1347778788964040717/1447448554061692928/image.png?ex=6937a903&is=69365783&hm=36dc3da72bf0556317ffec0a4356f27af4f580e6f99c25267c6acf10d808e10a&" width="700">
</div>

> Fig 4: Diagrama de flujo (Estructura condicional doble)

---

### Estructura Condicional Múltiple -- "switch" ###
Se emplea para ejecutar diversos bloques de código basandose en el valor de una unica variable, que se compara con una lista de casos predefinidos. Simplificando así varias líneas de código complejas para tomar una desición con múltiples alternativas.
#### Ejemplo usando la estructura condicional "switch" ####

- Descripción del Problema
  
Este problema solicita al usuario ingresar un número por teclado del uno al cinco (día laborable de la semana) y que se muestre el dia que es, proporcionalmente al número ingresado.

- Codigo en C

```

 #include <stdio.h>

int main ( ){

  int dia;
  
  printf ("Ingrese el dia de la semana del 1 al 5,dependiendo del dia laborable (excluyendo sabado y domingo) \n \n");
  scanf("%i", &dia);
  printf("-------------------------- \n");
  getchar ();
  
  switch (dia)
  {
      case 1:
          printf ("Es lunes \n");
          break;
  
      case 2:
          printf ("Es martes \n");
          break;
  
      case 3:
          printf ("Es miercoles \n");
          break;
  
      case 4:
          printf ("Es jueves \n");
          break;
  
      case 5:
          printf ("Es viernes \n");
          break;
  
  }
  return 0;

}

```
> Cuadro de código 3: Determinar el rango

##### Explicación del código C #####
Se solicita al uuario ingresar un número y en base a ello, se evalua que se encuentre en un rango determinado, si cumple la condicion y se encuentra dentro del rango se mostrará el mensaje correspondiente y si no tambien se mostrará un menaje correspondiente. 

- Pruebas de escritorio.

| **Valor Ingresado** | 
| :---:| 
| 4 | 
| 1 |

> Tabla 3: Pruebas de escritorio (Condicional Múltiple).


<div>
  <img src="https://cdn.discordapp.com/attachments/1347778788964040717/1447619909763993772/image.png?ex=69384899&is=6936f719&hm=c330722b105a791657f0f68c56dea1987d18f2fbdd8dfcde2d0e146459aaa28f&" width="600">
</div>

> Fig 5.1: Primer caso PE


<div>
  <img src="https://cdn.discordapp.com/attachments/1347778788964040717/1447620046137458892/image.png?ex=693848ba&is=6936f73a&hm=4533c6781ed8fe5f1bbbbcf1c5c822bca25390a3cdafe29537c73feef318613c&" width="600">
</div>

> Fig 5.2: Segundo caso PE

>

- Diagrama de flujo (Estructura condicional múltiple)

<div align="center">
  <img src="https://cdn.discordapp.com/attachments/1347778788964040717/1447622662603018441/image.png?ex=69384b2a&is=6936f9aa&hm=42b0ebed54dd25868c352fbe821c1a537f362325a6882562b24e5c7038208a87&" width="750">
</div>

> Fig 6: Diagrama de flujo (Estructura condicional múltiple)

---

---

## ESTRUCTURAS REPETITIVAS ##
### Estructura Repetitiva -- "while" ###
While se usa en cualquier expresión simple que al evaluarse devuelve el valor verdadero o falso. El bucle se repite mientras la condición sea verdadera. Cuando es falsa, el programa pasa a la instrucción siguiente, después del cuerpo de la estructura [1].
#### Ejemplo usando la estructura condicional "while" ####

- Descripción del Problema
  
El problema se basa en que el usuario ingrese 3 valores por teclado, donde cada uno de estos se sumaran progresivamente para mostrar al usuario la suma total.

- Codigo en C

```

#include <stdio.h>
 
int main () {

    int suma = 0;
    int cantidad = 1;
    int valorAgregado;

    while (cantidad <=3) 
    {
      
      printf ("\n Ingerese el valor agregado: \n");
       scanf ("%i", &valorAgregado);

       suma = suma + valorAgregado; 
       cantidad += 1; 

    }

    printf ("La suma acumulada es: %i", suma);


    return 0;
}

```
> Cuadro de código 4: Suma de valores definidos

##### Explicación del código C #####
Se incluyen los principales fundamentos del lenguaje C, luego se pide al usuario igresar tres valores de manera progresiva, para luego ser sumados y mostrar el producto al usuario.

- Pruebas de escritorio.

| **Valores** | 
| :---:| 
| 5, 9, 6 | 

> Tabla 1: Pruebas de escritorio (Condicional Simple).


<div>
  <img src="https://cdn.discordapp.com/attachments/1347778788964040717/1447649887175839927/image.png?ex=69386485&is=69371305&hm=366fb6d3834b18e7e777e82159f1d578a43f238bb42cead0e3b8d52378a4b7ba&" width="700">
</div>

> Fig 1.1: Primer caso PE

>

- Diagrama de flujo (Estructura Repetitiva)

<div align="center">
  <img src="https://cdn.discordapp.com/attachments/1347778788964040717/1447652182827733255/image.png?ex=693866a8&is=69371528&hm=2c26314ba3c4ce1046ad20240686ce6fa9fcb3e83090d8d39afbacdd6655301c&" width="450">
</div>

> Fig 2: Diagrama de flujo (Estructura Repetitiva)

---

### Estructura Repetitiva -- "do-while" ###
Para el elemento do-while se evalúa la condición después de que se ejecute el cuerpo del bucle. Por consiguiente, el cuerpo del bucle se ejecuta siempre al
menos una vez[2].
#### Ejemplo usando la estructura condicional "do-while" ####

- Descripción del Problema
  
El usuario ingresa valores numericos por teclado, mientras estos sean positivos se contaran y si se ingresa un número negativo el programa muestra cuantos números positivos se ingresaron.

- Codigo en C

```

#include <stdio.h>

   int main () {

   float numero;
   int contador = 0;

    do { 
        
        printf("Ingrese el numero deseado: \n");
        scanf("%f", &numero);
        getchar();

        if (numero > 0) 
        {
           contador = contador + 1;
        }

    }while (numero > 0);
        
    printf ("Los valores positivos fueron: %i", contador);

    return 0;
}

```
> Cuadro de código 4: Suma de valores definidos

##### Explicación del código C #####
Se incluyen los principales fundamentos del lenguaje C, luego se pide al usuario igresar números mayores a cero, mientras esta instrucción se lleve a cabo, se iran contando cuantos valores positivos se ingresen y si el valor ingresado rompe la regla se mostrara cuantos valores positivos se contaron y el programa finalizará. 
- Pruebas de escritorio.

| **Valores** | 
| :---:| 
| 7, 4, 45, 69, -20 | 

> Tabla 1: Pruebas de escritorio (Condicional Simple).


<div>
  <img src="https://cdn.discordapp.com/attachments/1347778788964040717/1447663321091276920/image.png?ex=69387108&is=69371f88&hm=3e367fc7b1bc7e0dd2bed16b62a7684bbf81cc88ab7d279e8262bcc450a55ef4&" width="700">
</div>

> Fig 1.1: Primer caso PE

>

- Diagrama de flujo (Estructura Repetitiva)

<div align="center">
  <img src="https://cdn.discordapp.com/attachments/1347778788964040717/1447664053735391462/image.png?ex=693871b6&is=69372036&hm=346f4c25da989778e2577fc913417d75dc6daa22eee5e4e399f9fbc58ca42e2f&" width="450">
</div>

> Fig 2: Diagrama de flujo (Estructura Repetitiva)

---

### Estructura Repetitiva -- "for" ###
La estructura for se usa en aquellas situaciones en las cuales CONOCEMOS la cantidad de veces que queremos que se ejecute el bloque de instrucciones[3]. Manejando iteraciones definidas o limitadas o bucles controladas por contador.

#### Ejemplo usando la estructura condicional "do-while" ####

- Descripción del Problema
  
El problema se basa en la suma progresiva de los numeros dentro del rango [1, 38], y el programa mostrará el resultado.

- Codigo en C

```

#include <stdio.h>

int main () {

    float suma;
    int numero;
    
    suma = 0;
    numero = 1;

    for (numero = 1 ;numero <= 38;  numero ++)
    {
        suma+= numero;

    }
    
    printf("La suma total es : %.2f \n", suma);

    return 0;
}

```
> Cuadro de código 4: Suma de valores definidos

##### Explicación del código C #####
Se incluyen los principales fundamentos del lenguaje C, luego se aplica el bucle for para realizar la suma progresiva de los numeros dentro del rango y mostrar al usuario el resultado final.
- Pruebas de escritorio.

| **Valores** | 
| :---:| 
| [1, 38] | 

> Tabla 1: Pruebas de escritorio (Condicional Simple).


<div>
  <img src="https://cdn.discordapp.com/attachments/1347778788964040717/1447669879971909773/image.png?ex=69387723&is=693725a3&hm=48bc97a20a85be590ddda0b4d2e0390dc3cd5d3f166bd4a9016d3f74c3fa13ed&" width="700">
</div>

> Fig 1.1: Primer caso PE

>

- Diagrama de flujo (Estructura Repetitiva)

<div align="center">
  <img src="https://cdn.discordapp.com/attachments/1347778788964040717/1447671088581578874/image.png?ex=69387843&is=693726c3&hm=3b2dcda732c61441deeaff81383cdc48cfa899c8cb9a04df20fca71f3923408c&" width="450">
</div>

> Fig 2: Diagrama de flujo (Estructura Repetitiva)

---



















