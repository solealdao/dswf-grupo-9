# TPO1: Trabajo Práctico Grupal 1

Este proyecto consiste en clonar la estructura y el diseño general del sitio web Tienda de Café para crear una nueva tienda temática dedicada a la venta de vinos. Aunque mantenemos la estructura, fuentes y estilos del sitio original, hemos adaptado los colores y el contenido para representar la elegancia y sofisticación del mundo del vino.

## Objetivos del proyecto:

-  Clonación de interfaces web: reproducir la estructura y estilos del sitio original con una nueva temática.
-  Trabajo en equipo: aprender a colaborar en grupo, comunicarnos de manera efectiva y mejorar nuestras habilidades blandas.
-  Gestión de proyectos: usar Git y GitHub para trabajar de forma colaborativa y gestionar el código.

## Tecnologías Utilizadas

-  HTML y CSS: para la estructura y estilización de las páginas.
-  Git y GitHub: gestión de versiones y trabajo colaborativo.
-  Diseño Responsivo: uso de unidades relativas y media queries para adaptar la página a diferentes dispositivos.

## Estructura de Archivos

```bash
tpo-grupo-9/
├── css/
│   └── styles.css   # Archivo CSS para estilizar las páginas
│
├── assets/
│   └── images/      # Carpeta de imágenes
│
├── views/                # Carpeta que contiene los archivos HTML
│   ├── index.html        # Página principal de la tienda de vinos
│   ├── tienda.html       # Página "Nuestra Bodega"
│   ├── tutoriales.html   # Página "Catas y Maridajes"
│   ├── menu-tienda.html  # Página "Menú de la Bodega"
│   ├── trabaja-en-tdc.html # Página "Trabajá con Nosotros"
│   ├── franquicias.html  # Página "Franquicias"
│   └── contacto.html     # Página "Contacto"
│
└── README.md             # Archivo README del proyecto
```

## Aclaraciones

Para lograr el funcionamiento de estas vistas y su renderización en cualquier navegador, se optó por repetir el código del `header` y `footer` en cada archivo HTML.

Si bien entendemos los conceptos de modularización y la importancia de evitar la repetición de código, en este proyecto decidimos mantener la estructura simple y compatible con cualquier entorno, sin requerir el uso de un servidor local o tecnologías adicionales como Node.js.

Intentamos una solución utilizando `fetch` para cargar los fragmentos del `header` y `footer` de manera dinámica, pero esto presentaba problemas con las restricciones de CORS en navegadores al abrir archivos locales (`file://`). Para garantizar que el proyecto sea evaluado y corregido correctamente desde cualquier medio, decidimos replicar los elementos compartidos en cada vista.

## Cómo bajarse el proyecto

Para clonar el repositorio en Github:

```
git clone git@github.com:solealdao/dswf-grupo-9.git
```
