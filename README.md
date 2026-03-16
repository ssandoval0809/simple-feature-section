# 🚀 Simple Feature Section - devChallenges

Este proyecto es una sección de características diseñada para productos SaaS (Software as a Service). El reto se centró en implementar un diseño adaptable que utiliza Flexbox anidado y optimización de imágenes para mejorar el rendimiento y la experiencia de usuario en diversos dispositivos.

## 🛠️ Tecnologías Utilizadas

* **HTML5:** Estructura semántica avanzada para mejorar el SEO y la accesibilidad.
* **CSS3:** Uso de Flexbox, Media Queries y técnicas modernas de diseño responsivo.
* **Google Fonts:** Implementación de la tipografía *Outfit* para un acabado limpio y moderno.

## ✨ Características Principales

* **Diseño Responsivo (Mobile-First):** La interfaz fluye desde una disposición vertical en móviles hasta una cuadrícula de tres columnas en pantallas de escritorio.
* **Optimización de Imágenes:** Uso de la etiqueta `<picture>` con múltiples fuentes (`srcset`) para servir imágenes de alta resolución solo cuando el dispositivo lo requiere, mejorando los tiempos de carga.
* **Interactividad Sutil:** Implementación de efectos de transición (`hover`) que mejoran la retroalimentación visual al usuario.
* **Accesibilidad (A11y):** Estructura jerárquica de encabezados y atributos ARIA para una mejor interpretación por lectores de pantalla.

## 🧠 Conceptos Clave Aplicados

* **Flexbox Anidado:** Distribución precisa de elementos tanto en el contenedor principal como dentro de cada tarjeta individual.
* **Arquitectura de Nomenclatura:** Uso de clases específicas (estilo BEM) para garantizar que el código sea escalable y fácil de mantener.
* **Gestión de Viewport:** Uso de `min-height: 100vh` para asegurar que el fondo y el contenido se comporten correctamente independientemente del tamaño de la pantalla.
* **Semántica Web:** Uso de `<article>`, `<section>`, `<figure>` y `<header>` para definir claramente el propósito de cada bloque de contenido.

## 📦 Instrucciones de Instalación y Uso

Para ejecutar este proyecto de forma local, sigue estos pasos:

1.  **Clona el repositorio**
2.  **Estructura de archivos:**
    Asegúrate de mantener la jerarquía de carpetas para que las rutas de imagen y estilos funcionen:
    ```text
    ├── index.html
    ├── styles.css
    └── /img
        ├── Background_image@3x.png
        ├── photo_1.png
        ├── photo_1@2x.png
        ├── ... (resto de fotos)
        └── favicon.ico
    ```
3.  **Ejecución:**
    Abre el archivo `index.html` en tu navegador web preferido.

## ✒️ Autora

* **Sara Sandoval** - Diseño
* Proyecto basado en el reto de [devChallenges.io](https://www.devchallenges.io)
