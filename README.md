# Tarea 3 · La factura bajo el microscopio

Alumno: Curro Romero Díaz · GitHub: WhiteCurriX

## Reto 1 · Compilar desde la terminal

- Comando usado: `javac -version` (sale `javac 25.0.4.1`) y después `javac Factura.java`. No compila: javac muestra 2 errores y, al hacer `dir`, no aparece `Factura.class` (captura: capturas/reto1.png).
- **Factura.java** es el código fuente: el programa escrito en Java, legible por personas.
- **Factura.class** será el bytecode: el resultado de compilar el fuente con `javac`. No es código máquina de un procesador concreto, sino un código intermedio.
- **¿Quién ejecuta el .class?** La JVM (Máquina Virtual de Java), con el comando `java Factura`. La JVM traduce el bytecode al sistema donde se ejecuta, por eso Java es portable.
- **¿Por qué no se ha generado Factura.class?** Porque el código tiene errores de compilación. Si `javac` encuentra algún error no genera bytecode: solo crea el .class cuando el código fuente es correcto.

## Reto 2 · Errores de compilación

| Nº | Línea | Mensaje de javac | Tipo (léxico / sintaxis / semántica) | Corrección |
|----|-------|------------------|--------------------------------------|------------|
| 1 | | | | |
| 2 | | | | |
| 3 | | | | |

Captura del programa funcionando: capturas/reto2.png

## Reto 3 · Depuración del error lógico

| Variable | Valor esperado | Valor real |
|----------|----------------|------------|
| descuento | | |
| total | | |

- Línea del error y explicación:
- Corrección:
- Mi propia prueba (producto, precio, cantidad, socio → total):

Captura del depurador: capturas/reto3.png

## Reto 4 · Reutilización

- Métodos creados y para qué sirve cada uno:
- ¿Qué ventaja tiene frente al código anterior?

## Reto 5 · ¿Qué lenguaje elegirías?

- Caso A (web de la tienda):
- Caso B (propuesta en ensamblador):