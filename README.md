# Ordenamiento Burbuja en Java (Bubble Sort)

Implementación básica y optimizada del algoritmo de ordenamiento de burbuja en Java. El programa toma un arreglo de números enteros desordenados y los organiza de forma ascendente.

## Requisitos previos

* Tener instalado el *Java Development Kit (JDK)* (versión 8 o superior).
* Tener instalado *Git* para clonar el repositorio.

## Instrucciones de uso

### 1. Clonar el repositorio

Abre tu terminal o línea de comandos y ejecuta el siguiente comando:

bash
git clone https://github.com
cd proyecto-bubble-sort


### 2. Compilar el programa

Ubícate en la carpeta raíz del proyecto y compila los archivos fuente ubicados en src:

bash
javac -d bin src/*.java


(Nota: Si tienes los archivos en la misma carpeta sin subdirectorios, simplemente ejecuta javac Burbuja.java Main.java).

### 3. Ejecutar el programa

Una vez compilado sin errores, ejecuta la clase principal:

bash
java -cp bin Main


(Si compilaste sin la carpeta bin, ejecuta únicamente java Main).

## Ejemplo de salida en consola

text
Arreglo original:
[6, 1, 5, 8, 3, 2, 7, 4]
Arreglo ordenado:
[1, 2, 3, 4, 5, 6, 7, 8]
