Pura Genética - Tienda de Suplementos (Proyecto HTML+SCSS)

Pura Genética es un sitio web estático de e-commerce enfocado en la venta de suplementos deportivos (whey protein, creatina, pre-workouts y más). Fue desarrollado usando únicamente HTML5, SCSS y Bootstrap 4, y representa uno de mis primeros proyectos de desarrollo front-end.

Características

Maquetación responsive con Grid y Flexbox.

Estilos escritos en SCSS con organización modular (partials para contacto, galería, preguntas frecuentes).

Carrusel de imágenes implementado con Bootstrap 4 Carousel.

Sección de productos con imágenes de fondo, efectos hover y layout fluido.

Formulario de contacto con validación nativa de HTML5 y estilos personalizados.

Navegación adaptativa con menú hamburguesa en dispositivos móviles.

Estructura del proyecto

Proyecto_Pura_Genetica/
├── css/
│   ├── images/           # Imágenes del sitio
│   ├── _contacto.scss    # Estilos sección Contacto
│   ├── _galeria.scss     # Estilos sección Galería
│   ├── _preguntas.scss   # Estilos FAQ
│   ├── styles.scss       # SCSS principal
│   ├── styles.css        # CSS compilado
│   └── styles.css.map    # Mapa de origen
├── index.html            # Página principal
├── productos.html        # Listado de productos
├── galeria.html          # Galería de videos e imágenes
├── preguntasfrecuentes.html # FAQ
├── contacto.html         # Formulario de contacto
└── README.md             # Documentación del proyecto

## Cómo usar

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/JohnnyPegaduro/Proyecto_Pura_Genetica.git

Compilar SCSS a CSS:

sass css/styles.scss css/styles.css --no-source-map --style=compressed

Abrir index.html en un navegador.

Notas

Este proyecto me ayudó a familiarizarme con Sass, Bootstrap y responsive design.

Aprende a organizar estilos en partials y a usar tareas build simples sin Node.js.

© 2025 Matías Ariel Deluca



