# 1️⃣UNIDAD 2📚
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


<div align="center">
  <img src="https://cdn.discordapp.com/attachments/1347778788964040717/1447440652936941629/image.png?ex=6937a1a7&is=69365027&hm=deea87047460ae4104d9ba1087fecddbd166e8ea794d0e01b459b6dcb61654db&" width="600">
</div>

> Fig 1.1: Primer caso de escritorio


<div align="center">
  <img src="https://cdn.discordapp.com/attachments/1347778788964040717/1447441087625957416/image.png?ex=6937a20f&is=6936508f&hm=a1f169d4345f3fee3f462bb1f2c53edc4e5a1ae4cd1694631bcdbd4f8f0d2d01&" width="600">
</div>

> Fig 1.2: Segundo caso de escritorio

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


<div align="center">
  <img src="https://cdn.discordapp.com/attachments/1347778788964040717/1447447614864883854/image.png?ex=6937a823&is=693656a3&hm=319f972cc18ca5a8edb74a8a2440c742b2951918fc8e112777aaf3335d4f73f5&" width="600">
</div>

> Fig 3.1: Primer caso de escritorio


<div align="center">
  <img src="https://cdn.discordapp.com/attachments/1347778788964040717/1447447947653419121/image.png?ex=6937a873&is=693656f3&hm=6d045792d017e27a50b554e33b8960cdc34f10a5c145b0233ad14639415484e7&" width="600">
</div>

> Fig 3.2: Segundo caso de escritorio

>

- Diagrama de flujo (Estructura condicional doble)

<div align="center">
  <img src="https://cdn.discordapp.com/attachments/1347778788964040717/1447448554061692928/image.png?ex=6937a903&is=69365783&hm=36dc3da72bf0556317ffec0a4356f27af4f580e6f99c25267c6acf10d808e10a&" width="600">
</div>

> Fig 4: Diagrama de flujo (Estructura condicional doble)
