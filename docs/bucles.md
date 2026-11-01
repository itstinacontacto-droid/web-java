# Bucles en Java

## ¿Qué es un bucle?

Un bucle es una estructura que permite repetir un bloque de instrucciones varias veces.

Los bucles ayudan a evitar que tengamos que escribir repetidamente las mismas instrucciones.

## El bucle for

El bucle `for` se utiliza habitualmente cuando conocemos el número de repeticiones que queremos realizar.

### Ejemplo

```java
public class BucleFor {
    public static void main(String[] args) {
        for (int i = 1; i <= 5; i++) {
            System.out.println(i);
        }
    }
}
```

Este programa muestra los números del 1 al 5.

En la cabecera del bucle:

- `int i = 1` inicializa la variable.
- `i <= 5` establece la condición.
- `i++` incrementa el contador en una unidad.

## El bucle while

El bucle `while` repite las instrucciones mientras la condición sea verdadera.

### Ejemplo

```java
public class BucleWhile {
    public static void main(String[] args) {
        int numero = 1;

        while (numero <= 3) {
            System.out.println(numero);
            numero++;
        }
    }
}
```

En este caso, el programa muestra los números del 1 al 3.

## Diferencias entre for y while

| Bucle | Uso habitual |
|---|---|
| `for` | Cuando conocemos el número de repeticiones o trabajamos con un contador. |
| `while` | Cuando queremos repetir instrucciones mientras se cumpla una condición. |

!!! warning "Evita los bucles infinitos"
    Asegúrate de que la condición de un bucle puede llegar a ser falsa cuando el programa deba terminar.

!!! tip "Practica"
    Modifica los ejemplos para mostrar otros números y observa cómo cambia el resultado.