# 🌟 Premium Hero Section - Instituto de Estética y Belleza

¡Bienvenido/a! Este proyecto es un componente de interfaz de usuario (UI) avanzado para una sección Hero interactiva, diseñada específicamente para negocios de estética, spas o salones de belleza premium. El objetivo principal fue lograr un diseño inmersivo y fluido con altos estándares de rendimiento y accesibilidad.

🌐 **Ver el proyecto en vivo:** [Haz clic aquí para ver en GitHub Pages](https://maquetacion77.github.io/premium-hero-section/)
🎨 **Caso de estudio visual:** [Ver presentación completa en Behance](TU_ENLACE_DE_BEHANCE_AQUÍ_O_LO_AGREGAS_DESPUÉS)

---

## 🛠️ Características Técnicas & Arquitectura

Para este desarrollo apliqué un enfoque basado en **componentes independientes (estilos modulares)**, lo que permite que esta sección sea completamente reutilizable en cualquier otro proyecto web sin generar colisiones de código.

*   **Estructura Semántica:** HTML5 avanzado utilizando etiquetas apropiadas (`<article>`, `<nav>`, `<section>`) optimizadas para SEO básico.
*   **Diseño Fluido (Layout):** Implementación de **CSS Grid** (matriz de 10x10) para el solapamiento perfecto de capas de texto, imágenes y navegación inferior.
*   **Botones Hexagonales Custom:** Diseñados mediante polígonos **SVG en línea (Data URLs)** incrustados directamente en el CSS para optimizar las peticiones del servidor y garantizar bordes perfectos en pantallas 4K.
*   **Interactividad Autónoma:** Slider controlado con **Vanilla JavaScript (ES6+)** bajo el evento `DOMContentLoaded` y lógica blindada con reajuste de temporizador automático (*autoplay* inteligente).
*   **Accesibilidad (WCAG):** Inclusión de atributos `aria-label` en la navegación y ocultación de elementos puramente estéticos mediante `aria-hidden`.
*   **Responsive Web Design:** Adaptación total a dispositivos móviles mediante Media Queries, reorganizando el grid para priorizar la legibilidad del texto en pantallas pequeñas.

---

## 📂 Estructura del Repositorio

├── index.html       # Estructura del componente y maquetación semántica.
├── hero01.css       # Estilos modulares, animaciones, SVG custom y responsive.
└── hero.js          # Lógica del slider interactivo, eventos y temporizador autónomo.
