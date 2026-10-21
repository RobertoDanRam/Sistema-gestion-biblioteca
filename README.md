# Sistema de Gestión de Biblioteca (Clase 4)

Programa de consola desarrollado en Java para la administración de un catálogo de libros. El sistema permite gestionar una colección bibliográfica utilizando principios de Programación Orientada a Objetos y estructuras de datos dinámicas.

**Autor:** Roberto Daniel Ramos Flores

## Características Principales

- **Registro de Libros:** Permite ingresar nuevos títulos al catálogo especificando autor, título, género y código de barras.
- **Búsqueda por Código:** Localiza y muestra la información de un libro en específico utilizando su código de barras único.
- **Búsqueda por Género:** Filtra la lista de libros y muestra todos aquellos que coincidan con un género literario determinado (ignorando mayúsculas y minúsculas).
- **Listado Completo:** Imprime en consola todos los libros registrados en el sistema mediante el uso del método sobreescrito `toString()`.
- **Datos Pre-cargados:** El sistema se inicializa con una lista de libros de prueba precargados para facilitar la demostración de sus funciones.

## Tecnologías Utilizadas

- **Lenguaje:** Java
- **Estructuras de datos:** `ArrayList` y `List` para el almacenamiento dinámico de objetos en memoria.
- **Manejo de entrada:** `Scanner` para la interacción en consola.
- **Entorno de desarrollo:** Visual Studio Code (VSCode)

## Estructura del Código

- `App.java`: Clase principal que contiene el método `main`. Implementa el menú interactivo mediante un ciclo `do-while` y contiene los métodos estáticos para gestionar las búsquedas y el registro de la información capturada por el usuario.
- `Libro.java`: Modelo de datos que representa un libro. Implementa encapsulamiento con atributos privados, métodos *getters* y *setters*, múltiples constructores (por defecto y parametrizado) y la sobreescritura del método `toString()` para formatear la impresión de los datos del libro.
