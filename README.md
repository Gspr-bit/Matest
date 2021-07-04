# Matest

Una sencilla aplicación en Java diseñada para desarrollar la habilidad de resolver operaciones matemáticas básicas rápidamente.

Disponible en Español, Portugués e Inglés, para agregar más idiomas modificar el archivo src/matest/Lenguaje.java

A simple Java application designed to develop skills in solving basic math operations fast.

Available in Spanish, Portuguese and English, to add more languages edit the file src/matest/Lenguaje.java

![](https://github.com/Gspr-bit/Matest/blob/main/screenshots/01-configurar-test-suma.png)
![](https://github.com/Gspr-bit/Matest/blob/main/screenshots/02-pantalla-principal.png)
![](https://github.com/Gspr-bit/Matest/blob/main/screenshots/03-test-resta.png)
![](https://github.com/Gspr-bit/Matest/blob/main/screenshots/04-resumen.png)

## Español

Esta aplicación permite practicar sumas, restas, multiplicaciones, divisiones y porcentajes.

Los test pueden ser por tiempo o por cantidad de ejercicios, también se puede elegir la cantidad máxima de digitos en cada cifra, y la cantidad de sumandos o multiplicandos.

Proximamente la aplicación será capaz de guardar un historial con los resultados obtenidos en los tests (incompleto).

El código fuente tiene el formato de un proyecto de Netbeans, entonces puede ser facilmente modificada usando **Netbeans**.

## 2021 - 07 - 04

- Si es ejecutado en us sistema operativo con laf diferente a windows, GTK+ o aqua, intenta forzar el uso de GTK+, si falla utiliza nimbus.

### 2021 - 07 - 02

- Guarda los resultados de los tests en un archivo en logs/logs.csv
- Se corrigieron varios errores

### 2021 - 04 - 23

- Ahora también está disponible en Portugués.
- Ya toma el tema de cualquier sistema operativo y no solo de Linux.
- Ahora solo genera números del largo especificado y no menores.

### Como usar

[Descargar](https://github.com/Gspr-bit/Matest/raw/main/dist/matest.jar) el archivo dist/matest.jar y ejecutarlo, dando doble clic en el archivo o con `java -jar matest.jar`. Es necesario tener instalado Java. Esta aplicación fue probada en openjdk 11. Si no funciona en otra versión de java tal vez haya que instalar openjdk 11 o jdk 11.

## English

This application helps to practice addition, substraction, multiplication, division and percentage.

The test can be by time limit of by amount of exercises, the max amount of digits by number and the amount of  addends or miltiplicands can be choosen.

In the future the application will save a history of the results obtained in the tests.

The source code has the format of a Netbeans project, so it can be easily modified using **Netbeans**.

### 2021 - 07 - 04

- If it is executed in a SO with a default laf different to Windows, GTK+ or aqua, tries to force the use of GTK+, if fails, takes the nimbus laf.

### 2021 - 07 - 02

- Now it saves the tests results in logs/logs.csv
- Bugs were fixed

### How to use

[Download](https://github.com/Gspr-bit/Matest/raw/main/dist/matest.jar) the file dist/matest.jar and execute it with double click in the file or with `java -jar matest.jar`. It is needed to have installed Java previously. This application was proved in openjdk 11. If it doesn't work with another java version you may need to install openjdk 11 or jdk 11.
