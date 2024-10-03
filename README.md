# S-DES De-cryption

Este repositorio contiene una implementación del algoritmo S-DES (Simplified Data Encryption Standard) para cifrar imágenes. El proyecto está desarrollado en Python y utiliza operaciones básicas de permutación y suma XOR para cifrar una imagen y luego descifrarla, generando un archivo de imagen encriptado.

## Integrantes del equipo:

| Nombre                        | Matrícula  |
|-------------------------------|------------|
| Alejandra Cantú González      | 1908866    |
| Victor Torres Cavazos         | 1922988    |
| Daniel Gilberto Escobar Castañeda | 1921830 |

## Descripción del Proyecto

Este proyecto utiliza el algoritmo S-DES para cifrar una imagen mediante una clave de 10 bits proporcionada por el usuario. El flujo del programa es el siguiente:

1. Leer la imagen original y convertir su contenido a una representación binaria.
2. Solicitar al usuario una clave de 10 bits.
3. Realizar operaciones de permutación y suma XOR sobre la clave para generar subclaves.
4. Utilizar la representación binaria de la imagen y aplicar el cifrado S-DES para obtener una versión cifrada de la imagen.
5. Guardar la imagen cifrada en el archivo `decrypt.png`.
