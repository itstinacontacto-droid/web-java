# Introducción a Java

## ¿Qué es Java?

Java es un lenguaje de programación de propósito general que permite desarrollar diferentes tipos de aplicaciones.

Se utiliza para crear aplicaciones de escritorio, aplicaciones empresariales y servicios web, entre otros.

## Características principales

- **Orientado a objetos:** permite organizar el programa mediante clases y objetos.
- **Multiplataforma:** los programas Java pueden ejecutarse en diferentes sistemas operativos si disponen de un entorno de ejecución compatible.
- **Tipado estático:** las variables tienen un tipo de dato definido.
- **Amplio ecosistema:** dispone de numerosas bibliotecas y herramientas para desarrollar aplicaciones.

## ¿Cómo funciona Java?

El proceso básico de ejecución de un programa Java es el siguiente:

1. El programador escribe el código en un archivo `.java`.
2. El compilador transforma el código en bytecode.
3. La máquina virtual de Java (JVM) ejecuta ese bytecode.

## Ejemplo de un programa Java

El siguiente programa muestra un mensaje por pantalla:

```java
public class HolaMundo {
    public static void main(String[] args) {
        System.out.println("Hola, mundo");
    }
}
```

### ¿Qué hace este programa?

- `public class HolaMundo` declara una clase llamada `HolaMundo`.
- `main` es el método desde el que comienza la ejecución del programa.
- `System.out.println()` muestra un mensaje por pantalla.

!!! info "Importante"
    Java distingue entre mayúsculas y minúsculas. Por ejemplo, `HolaMundo` y `holamundo` son nombres diferentes.

## Herramientas para programar en Java

Para empezar a programar con Java, puedes utilizar un entorno de desarrollo como [Eclipse](https://eclipseide.org/).

También puedes consultar la [documentación oficial de Java](https://docs.oracle.com/en/java/).

!!! tip "Consejo"
    Cuando empieces a programar, prueba a cambiar el mensaje de `Hola, mundo` por una frase escrita por ti.