# Implementación de ordenamientos

## Descripción:

El programa consiste en ordenar un dataset de 1000 canciones con 4 formas de ordenamientos:

1. BinaryInsertionSort    
2. MergeSort    
3. QuickSort
4. RadixSort

Nuestra base de datos es el dataset, el cual contiene 1000 canciones con métricas de flujo de cada artista y sus respectivas canciones. Las columnas del dataset son las siguientes:

- Position: Es el ranking en Spotify
- Artist Name: Nombre del artista
- Song name: Nombre de la canción
- Days: Días desde el lanzamiento de la canción
- Top 10(xTimes): Número de veces dentro del top 10
- Peak Position: Posición máxima alcanzada
- Peak Position (xTimes): Número de veces que se alcanzó la posición máxima
- Peak Streams: Número total de flujos durante la posición pico
- Total Streams: Transmisiones totales de canciones

El programa consiste en ordenar el conjunto de datos de acuerdo a dos de las nueve columnas(métricas) del dataset. El usuario puede ordenar de acuerdo a los nombres de las canciones o el número de días desde el lanzamiento, así como si desea que el ordenamiento sea ascendente o descendente.

* En el caso de elegir un ordenamiento por nombres de la canciones, entonces el programa ordenará con los métodos:

    1. BinaryInsertionSort
    2. MergeSort
    3. QuickSort


* Si elige un ordenamiento por días de lanzamiento, entonces el programa ordenará por todos los métodos:

    1. BinaryInsertionSort
    2. MergeSort
    3. QuickSort
    4. RadixSort

En ambos casos se creará un archivo llamado "Métricas.csv" el cual se encuentra en la carpeta -orderData- donde se recaba un resumen de los métodos de ordenamiento y métricas como:
- Tiempo de ejecución (en milisegundos)
- Número de comparaciones
- Número de intercambios

De igual manera se crea un archivo por cada método de ordenamiento que se utilice donde se almacenarán los datos ordenados de cada método.

## Clonar el repositorio

1. En dado caso no tenga la carpeta donde desee clonar el repositorio, cree la carpeta.
2. Abra una terminal 
3. Con la terminal, ubíquese en la carpeta creada.
4. Despues escriba lo siguiente: 

    git clone https://github.com/JL-Puc/ADA06_E3.git

Con ello el repositorio se clonará en la carpeta que ha especificado.

## Compilar y ejecutar el programa

1. Abra una terminal 
2. Con la terminal, ubíquese en la carpeta "ADA06_E3" (la cual es donde se encuentra el programa).
3. Seguidamente, para compilar escriba en la consola:

    javac src/App.java

4. Por último para ejecutar el programa escriba:

    javac src\App.java 



