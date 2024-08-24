Diferencia entre un **IDE** y un **editor de texto**.

**Los editores de texto** son ideales para quienes necesitan un entorno rápido y flexible. Son la mejor opción para tareas ligeras, configuraciones personalizadas y cuando se necesita un programa que consuma pocos recursos.

**Los IDE** son más adecuados para proyectos grandes y complejos donde se necesita un conjunto completo de herramientas integradas.

Tipos de lenguajes de programación (tipados y no tipados).

**Tipados:** Los lenguajes tipados se caracterizan porque requieren que definamos el tipo de dato específico de las variables y expresiones que vamos a utilizar.

**No tipados:** Los lenguajes no tipados no necesitan que indiquemos el tipo de variables y expresiones al declarar la variable.

Java tiene varios tipos de datos numéricos, tanto enteros como de punto flotante:

* **Enteros:**  
  * **byte:** Un entero de 8 bits con un rango de \-128 a 127\.  
  * **short**: Un entero de 16 bits con un rango de \-32,768 a 32,767.  
  * **int:** Un entero de 32 bits con un rango de \-2^31 a 2^31 \- 1\.  
  * **Long:** Un entero de 64 bits con un rango de \-2^63 a 2^63 \- 1\.  
* **Punto Flotante:**  
  * **float:** Un número de punto flotante de 32 bits con precisión simple.  
  * **double:** Un número de punto flotante de 64 bits con precisión doble.

En Java, las cadenas de texto se manejan con el tipo de dato String:

* **String:** Representa una secuencia de caracteres. Es una clase en Java y proporciona numerosos métodos para manipular cadenas de texto, como length(), substring(), toUpperCase(), y más.

Java no tiene un tipo de dato primitivo para fechas y horas, pero proporciona varias clases en el paquete java.time (introducido en Java 8\) y en el paquete java.util para trabajar con fechas y horas.

* **Paquete java.time:**  
  * LocalDate: Representa una fecha sin hora (año, mes, día).  
  * LocalTime: Representa una hora sin fecha.  
  * LocalDateTime: Representa una combinación de fecha y hora.  
  * ZonedDateTime: Representa una fecha y hora con una zona horaria específica.  
  * Instant: Representa un punto específico en el tiempo (con precisión de milisegundos).

**Paquete java.util:**

* Date: Una clase antigua que representa una fecha y hora (en milisegundos desde el 1 de enero de 1970, GMT). Aunque se sigue utilizando, se recomienda usar las clases del paquete java.time para nuevas aplicaciones debido a su mayor flexibilidad y funcionalidad.


### **Ejemplo c\#** 

int numero \= 10;

if(numero\>5){  
   Console.WriteLine(“El numero es mayor que 5”);  
}

Java  
Public class Main{  
  Public static void main(String\[ \] args {

int numero1 \= 10;  
int numero2 \= 15;

if(numero1\<numero2){  
  System.out.print(“Esto es verdadero”);  
     }  
  }  
}

Python

edad=18  
if edad\>=18:  
  print(“Es mayor de edad”)

JavaScript

let número=15;  
if(numero\>10){  
   console.log(“El número es mayor que 10”);  
}

PHP

$edad=25;  
if ($edad\>=18){  
  echo”Eres mayor de edad. Puedes votar.”;  
}  
