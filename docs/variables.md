# Variables y tipos de datos en Java

## ¿Qué es una variable?

Una variable es un espacio donde un programa almacena un dato que puede utilizar durante su ejecución.

En Java, al declarar una variable, debemos indicar su tipo de dato y su nombre.

## Tipos de datos básicos

| Tipo | Descripción | Ejemplo |
|---|---|---|
| `int` | Números enteros | `int edad = 20;` |
| `double` | Números decimales | `double precio = 12.5;` |
| `char` | Un carácter | `char letra = 'A';` |
| `boolean` | Verdadero o falso | `boolean activo = true;` |
| `String` | Una cadena de texto | `String nombre = "Ana";` |

## Ejemplo de declaración de variables

```java
public class Variables {
    public static void main(String[] args) {
        int edad = 20;
        double nota = 8.5;
        String nombre = "Ana";
        boolean aprobado = true;

        System.out.println(nombre);
        System.out.println(edad);
        System.out.println(nota);
        System.out.println(aprobado);
    }
}
```

## ¿Cómo se declara una variable?

La estructura general es:

```java
tipo nombre = valor;
```

Por ejemplo:

```java
int numero = 10;
```

En este caso:

- `int` es el tipo de dato.
- `numero` es el nombre de la variable.
- `10` es el valor almacenado.

!!! warning "Recuerda"
    En Java, las instrucciones suelen terminar con un punto y coma (`;`).

!!! tip "Practica"
    Cambia el valor de `numero` y observa cómo cambiaría el resultado al mostrarlo por pantalla.condicionales.md