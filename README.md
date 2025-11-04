# Lenguaje de Cartas - Diccionario Visual (A-Frame)

Este proyecto presenta un entorno 3D interactivo desarrollado con **A-Frame**, en el que se asocian elementos del póker con conceptos básicos de programación.  
El usuario puede explorar el entorno girando la vista en distintas direcciones.

## Descripción general

El entorno está dividido en tres secciones principales:

### 1. Panel delantero – Cartas lógicas
Representa las cartas como estructuras lógicas del lenguaje de programación:
- **A♠:** Marca el comienzo y fin del programa.  
- **Q♠:** Condicional *if*, ejecuta si la condición es verdadera.  
- **Q♥:** Condicional *else*, ejecuta si la condición es falsa.  
- **K♥:** Representa bucles o iteraciones.

Incluye un botón interactivo para cambiar entre las distintas cartas.

### 2. Panel trasero – Palos clásicos
En el lado opuesto, las cartas de los distintos palos representan conceptos de programación:
- **Trébol:** Variables.  
- **Pica:** Elementos comparadores.  
- **Corazón:** Valores literales.  
- **Diamante:** Aritmética.  

También cuenta con un botón para alternar entre los distintos palos.

### 3. Mesa de póker
Ubicada a 90° de los paneles principales.  
Consiste en una **mesa verde** con **ocho montones de fichas de colores** y algunas fichas sueltas distribuidas sobre la superficie, simulando una escena de juego realista.

## Tecnologías utilizadas
- **A-Frame 1.5.0**
- **HTML5**
- **JavaScript**

## Interacción
- Se utiliza el cursor (controlado por el ratón o la vista) para interactuar con los botones.  
- Al hacer clic, las cartas giran mediante una animación de rotación que muestra la siguiente carta o palo.  
- El usuario puede girar 180° para ver el otro panel y 90° para observar la mesa.

## Estructura del proyecto
- `index.html`: Contiene toda la definición del entorno A-Frame, los elementos 3D y el script principal.
- Carpeta de imágenes: Contiene los recursos visuales de las cartas, palos y fondo.

## Autor
Proyecto creado por **Fernando Melero Muñoz, Giordano Castilla y Hernán Renero** para la asignatura de **Lenguajes y Paradigmas de Programación**, como representación visual e interactiva del lenguaje de cartas en un entorno 3D.
