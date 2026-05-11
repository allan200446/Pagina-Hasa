# Comercializadora HASA | Moda & Estilo

Este proyecto es una plataforma de comercio electrónico de alta gama diseñada para **Comercializadora HASA**, enfocada en la venta de moda exclusiva para hombres y mujeres. El sitio prioriza la elegancia, la experiencia de usuario (UX) y la accesibilidad técnica.

##  Propósito del Proyecto

El objetivo principal es proporcionar una vitrina digital sofisticada que refleje la identidad de marca de HASA. La página funciona como una landing page de conversión que utiliza elementos visuales modernos, tipografía clásica y animaciones fluidas para ofrecer una experiencia de compra inmersiva y de lujo.

---

##  Buenas Prácticas Aplicadas

### 1. Semántica y Accesibilidad (A11y)
Se ha implementado una robusta capa de accesibilidad para garantizar la inclusión:
- **Estructura Semántica**: Uso correcto de etiquetas HTML5 (`<header>`, `<main>`, `<footer>`, `<section>`).
- **Atributos ARIA**: Implementación de `aria-label`, `aria-hidden`, `aria-expanded` y roles específicos para lectores de pantalla.
- **Navegación**: Inclusión de clases `.sr-only` para texto oculto visualmente pero disponible para tecnologías de asistencia.
- **Contraste y Legibilidad**: Paleta de colores de alto contraste y tipografías optimizadas para lectura.

### 2. Arquitectura de CSS y Diseño
- **Variables CSS (:root)**: Centralización de la paleta de colores (Dorado #c9a84c, Negro #111, Blanco), tipografías y tiempos de transición para facilitar el mantenimiento.
- **Responsive Design**: Diseño adaptativo utilizando CSS Grid y Flexbox, optimizado para dispositivos móviles, tablets y desktops.
- **Animaciones de Rendimiento**: Uso de transiciones CSS optimizadas y `IntersectionObserver` para efectos de "reveal on scroll" sin penalizar el rendimiento.

### 3. Experiencia de Usuario (UX)
- **Micro-interacciones**: Cursor personalizado en escritorio, efectos de hover en tarjetas de producto y botones con transiciones suaves.
- **Componentes Dinámicos**: Slider hero con autoplay, carrito de compras lateral (drawer) y menú hamburguesa para navegación móvil.
- **Optimización de Fuentes**: Uso de `preconnect` para Google Fonts (Cormorant Garamond y Montserrat) mejorando el tiempo de renderizado inicial.

### 4. Organización del Código
- **Comentarios Técnicos**: Código debidamente comentado para facilitar la colaboración y el escalado del proyecto.
- **Reset de Estilos**: Aplicación de un reset consistente (`box-sizing: border-box`) para asegurar un comportamiento predecible del layout.

---

##  Tecnologías Utilizadas

- **HTML5**: Estructura y semántica.
- **CSS3**: Diseño, animaciones y layout responsivo.
- **JavaScript (Vanilla)**: Gestión de estado del carrito, manipulación del DOM y eventos de scroll.
- **Google Fonts**: Tipografías premium para el branding.

---

## 📁 Estructura Principal
- `index.html`: Estructura base, metadatos SEO y contenido semántico.
- `style.css`: Lógica visual, variables de marca y media queries.
