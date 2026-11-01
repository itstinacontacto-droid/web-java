# Condicionales en Java

## ¿Qué son las estructuras condicionales?

Las estructuras condicionales permiten que un programa tome decisiones según se cumpla o no una condición.

En Java, las estructuras condicionales más habituales son `if`, `else` y `switch`.

## La estructura if y else

- `if`: ejecuta un bloque de código si una condición es verdadera.
- `else`: permite ejecutar otro bloque cuando la condición no se cumple.

### Ejemplo

```java
public class Condicional {
    public static void main(String[] args) {
        int edad = 18;

        if (edad >= 18) {
            System.out.println("Eres mayor de edad");
        } else {
            System.out.println("Eres menor de edad");
        }
    }
}
```

En este ejemplo, el programa comprueba si la variable `edad` es mayor o igual que 18.

## La estructura switch

`switch` permite elegir entre diferentes opciones según el valor de una expresión.

### Ejemplo

```java
public class DiaSemana {
    public static void main(String[] args) {
        int dia = 1;

        switch (dia) {
            case 1:
                System.out.println("Lunes");
                break;
            case 2:
                System.out.println("Martes");
                break;
            default:
                System.out.println("Otro día");
                break;
        }
    }
}
```

La instrucción `break` termina el bloque correspondiente y evita continuar ejecutando los siguientes casos de este `switch`.

!!! info "¿Qué hace default?"
    El bloque `default` se ejecuta cuando no coincide ninguno de los casos definidos, siempre que el flujo llegue a él.

!!! tip "Consejo"
    Utiliza `if` y `else` para practicar condiciones y `switch` cuando quieras trabajar con diferentes opciones.