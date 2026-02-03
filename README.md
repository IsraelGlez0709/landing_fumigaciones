# PLAGA Soluciones - Sitio Web Oficial

> Landing page profesional y responsiva desarrollada para **PLAGA Soluciones**, empresa especializada en el manejo integrado de plagas, desinfección y venta de equipos en Tehuacán, Puebla.

![PLAGA Preview](./assets/logo.png)

## Descripción del Proyecto

Este proyecto consiste en el desarrollo de un sitio web estático (Landing Page) enfocado en la conversión de clientes y la difusión de información corporativa. El diseño prioriza la experiencia de usuario en dispositivos móviles (Mobile First) y la facilidad de contacto.

El sitio incluye secciones detalladas sobre:
* **Identidad Corporativa:** Misión, Visión, Valores y certificaciones (Licencia Sanitaria).
* **Servicios:** Desinsectación, Desrodentización, Tratamientos de Madera y Desinfección.
* **Catálogo de Equipos:** Sección tipo grid para la exhibición de productos de control de plagas.
* **Contacto Directo:** Integración con API de WhatsApp y llamadas telefónicas directas.

## Características Principales

* **Diseño 100% Responsivo:** Optimizado para visualizarse perfectamente en iPhone, Android, Tablets y Escritorio.
* **Navegación Intuitiva:** Menú de navegación fijo (Sticky Header) con Smooth Scroll y menú de hamburguesa para móviles.
* **Animaciones:** Efectos de entrada (Fade-in/Zoom) utilizando la librería **AOS (Animate On Scroll)**.
* **Interacción:** Botón flotante de WhatsApp permanente y botones de "Cotizar Ahora" con mensajes predefinidos.
* **Optimización Visual:** Uso de CSS Grid y Flexbox para layouts modernos (diseños en Zig-Zag y Tarjetas).
* **Assets Locales:** Carga optimizada de imágenes desde carpeta local.

## Tecnologías Utilizadas

* **HTML5:** Estructura semántica.
* **CSS3:** Estilos personalizados, variables CSS (`:root`), Flexbox, CSS Grid y Media Queries.
* **JavaScript (Vanilla):** Lógica para el menú hamburguesa y configuración de librerías.
* **Librerías Externas:**
    * [AOS (Animate On Scroll)](https://michalsnik.github.io/aos/) - Para animaciones al bajar.
    * [FontAwesome 6](https://fontawesome.com/) - Para iconos vectoriales.
    * [Google Fonts](https://fonts.google.com/) - Tipografía 'Poppins'.

## Estructura del Proyecto

```text
├── assets/              # Carpeta de imágenes (Logos, fondos, productos)
│   ├── logo.png
│   ├── portada.jpg
│   ├── mision.jpg
│   ├── ...
├── index.html           # Archivo principal HTML
├── styles.css           # Hoja de estilos principal
└── README.md            # Documentación del proyecto
