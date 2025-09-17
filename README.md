# TAREA1.MARKDOWN.DESPLIEGUE

# Hola mundo en VS code.

## Hecho con java, paso a paso.

---
### ¿Qué es VS code?
VS Code es un editor de código fuente gratuito y multiplataforma que se puede usar para escribir, depurar y probar código en una amplia variedad de lenguajes de programación
   
### ¿Qué es Java?
Java es un lenguaje de programación orientado a objetos, diseñado para la plataforma Java Virtual Machine (JVM).

--- 
### Paso a paso:

* PASO 1: Instalar VS Code
  * Configurar VS Code para su uso.
  * Descargar la extensión de Java para VS Code.
    
* PASO 2: Crear un nuevo proyecto Java.
  1. Damos click derecho en el área de trabajo y seleccionamos "Crear nuevo proyecto".
  2. Seleccionamos "Java" como el lenguaje de nuestro proyecto.
  3. Establecemos un nombre para el proyecto.
  4. Hacemos click en "Crear" para crear el proyecto y comenzar a escribir nuestro código Java.
     
* PASO 3: El codigo.
  1. Para hacer un "Hola mundo" en Java, simplemente escribimos la siguiente línea de código en nuestro archivo que hemos creado:
    > *System.out.println("Hola mundo!");*
  2. Para ejecutar nuestro código, hacemos click derecho en la línea de código y seleccionamos "Ejecutar Java" o presionamos el botón de play en la barra de herramientas.
  3. VS Code se abrirá una ventana emergente con el resultado de la ejecución.
  4. La salida de la línea de código se muestra en la consola de VS Code, donde puede verse la frase "Hola mundo!".

---
### Un poco más de personalización:
Si queremos, podrimos hacer que en vez de "Hola mundo!", nuestro programa imprima un mensaje personalizado. Para eso, simplemente cambiamos la línea de código a lo siguiente:
> *System.out.println("Hola, " + nombre + "!");*

Para que este codigo funcione correctamente, debemos introducir un nombre en la consola de VS Code antes de ejecutarlo.

* ¿Cómo añado mi nombre al mensaje personalizado?
    1. Debemos incluir al principio del codigo la línea: 
    > *import java.util.Scanner;* 
    2. A continuación, debemos crear una variable Scanner para obtener el nombre del usuario:
    > *Scanner sc = new Scanner(System.in);* (El sc es el nombre de nuestra variable Scanner, pero puede ser cualquier nombre que le guste).
    3. Después de la declaración de la variable Scanner, debemos leer el nombre del usuario:
    > *System.out.print("Ingrese su nombre: ");*
    4. Finalmente, debemos almacenar el nombre en la variable Scanner:
    > *nombre = sc.nextLine();*
    5. Ahora, podemos usar la variable nombre en nuestra línea de código:
    > *System.out.println("Hola, " + nombre + "!");*
    6. Ejecutamos nuestro código como lo hemos hecho antes.

---

#### CÓMO QUEDARIA NUESTRO CODIGO FINAL:

##### Para la version basica del "Hola mundo!" en Java:

  ```JAVA
  public static void main(String[] args) {
    System.out.println("Hola mundo!");
  }
  ```

##### Para la version personalizada del "Hola mundo!" en Java:

```JAVA
    import java.util.Scanner;

    public static void main(String[] args) {
      Scanner sc = new Scanner(System.in);
      System.out.print("Ingrese su nombre: ");
      Scanner sc = new Scanner(System.in);
      System.out.print("Ingrese su nombre: ");
      String nombre = sc.nextLine();
      System.out.println("Hola, " + nombre + "!");
      sc.close();
    }
   ``` 
---
##### Más información sobre VS Code:
[PAGINA OFICIAL VSCode](https://code.visualstudio.com/)

##### Más información sobre Java:
[PÁGINAL OFICIAL JAVA](https://www.java.com/es/)

##### Lenguaje utilizado en este tutorial:
[PÁGINAL OFICIAL MARKDOWN](https://markdown.es/)

[PAGINA 1 DE COMANDOS DE MARKDOWN](https://www.markdownguide.org/cheat-sheet/)

[PAGINA 2 DE COMANDOS DE MARKDOWN](https://markdown.es/sintaxis-markdown/)

---


Una vez puesta una de las dos versiones de los códigos, ¡solo tienes que ejecutarlo en VS Code para ver el resultado!

![Despedida](https://github.com/Stephyshere/TAREA1.MARKDOWN.DESPLIEGUE/blob/main/Imagenes/Gracias.jpg)
