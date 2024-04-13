# Aprende java

## 05 -> Estrutura de Repeticion
### Estrutura **For**
  Definicion de For:
  
  - Es una estrutura de control de flujo que facilita la ejecucion de un bloque de codigo de variras veces
  - Se utiliza para realizar bucles con un contador y una variable.
    
    ```JAVA
    for (int i = 1; i <= 5; i++){
      System.out,println("Iteracion " + i);
    }
    ```
### Estrutura **If-Else**    
  Definicion de If-else:
  - Es una estrutura de control de flujo de programa que permite tomar decisiones condicionales.
  - Se ejecuta si una condicion es verdadera `if` y si no `else`.
    
    ```java
    int x = 10;
    for (x > 5){
      System.out,println("x es mayor que 5 ");
    }else{
      System.out.println("x no es mayor que 5");
    }
    ```
      
## 07 -> Paquete `java.util` clase `Scanner`
Scanner es una clase en Java que se encuentra en el paquete `java.util` y se utiliza para obtener la entrada de datos del usuario `import java.util.Scanner;`.

```java
import java. util. Scanner;

public class Ejemplo {
  public static void main (String argz [] ) {
    Scanner in = new Scanner(System.in);

    System.out.println("Ingresa un numero: ");
    int numero = in.nextInt();

    System.out.println("El numero ingresado es: "+numero);
  }
}
```
> **RECUERDA:**
>> (System.in): Representa la entrada de teclado.
>>> **Luego se utilizan los metodo:**
>>> nextLine(): Para leer una linea de Texto.
>>> nextInt(): Para leer un numero entero.

## 08 -> Compara cadenas de texto
###  Metodo `equals()`
En java el metodo `equals()`, es un metodo de la clase `OBJECT` que se utiliza para comparar si dos objetos son iguales en terminos de contenido.
El metodo `equals()`, se puede usar con `Cadenas`.
```java
if(texto_1.equals(texto_2)){
  System.out.println("Son iguales");
}
```

###  Metodo `length()`
El metodo `length()` es un metodo utilizado para obtener la longitud o el numero de elementos de un secuencia, como una **Cadena de texto**, un **arreglo** o una **coleccion**
```java
String txtOriginal = "Ajolote";
int txtConvertido = txtOriginal.length();
```

## 10 -> Arrelgos Bidimensionales
###  Matrices
Los arreglos Bidimensionales tambien conocidos como matrices, son estructuras de datos que se contienen en filas y columnas.
```java
int numeros[][] = new int [Filas][Columnas];
```
Asignacion de valores:
En Filas`0` Columnas`1` Contenido`10`
```java
numeros[0][1] = 10;
```
Impresion:
Puedes imprimir valores individuales de la matriz segun sea necesario, esto tambien se puede optimizar con bucles como: **FOR**
```java
  System.out.println("numeros[Filas][Columnas]");
```

## 10 -> Operadores Relacionales
Los operadores **Relacionales** comparan dos valores y devuelven un resultado booleano (`true` o `false`). Estos operadores se utilizan para establecer relaciones de orden entre valores.
| Operador | Nombre | Ejemplo |
|----------------|----------------|----------------|
| **<** | Menor que | `5<4` |
| **>** | Mayor que | `A>B` |
| **==** | Igual a | `14==14` |
| **!=** | No igual a *(diferente)* | `perro != gato` |
| **<=** | Menor que o igual a | `A<=B` |
| **>=** | Mayor que o igual a | `A>=B` |

```java
int a = 10;
int b = 10;
if(a==b){
  System.out.println(a+" y "+b+" Son iguales");
}else{
  System.out.println("No son iguales");
}
```

## 13 -> Estrutura de Control
### Switch - Case
Switch toma desiciones basadas en el valor de una exprexion, ejecutando diferentes bloques de codigo segun los casos posibles, siendo una alternativa concisa a multiples **If-Else**.
```java
switch(expresion){
  case valor1:
    //Codigo a ejecutar
    break;
  case valor2:
      //Codigo a ejecutar
      break;
  default:
      //Codigo a ejecutar
      break;
}
```


