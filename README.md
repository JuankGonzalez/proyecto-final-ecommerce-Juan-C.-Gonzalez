# Proyecto Talento Lab - Sitio Web Interactivo

## Descripción del Proyecto
Este proyecto es una aplicación web responsiva desarrollada como entrega intermedia para el curso de **Front-End JS** de Talento Tech. La página representa el sitio oficial de Talento Lab, incluyendo secciones de información, productos/servicios, reseñas de usuarios y un formulario de contacto funcional.

## Requisitos Técnicos Implementados
- **Estructura HTML5 Semántica**: Uso de `<header>`, `<nav>`, `<main>`, `<section>`, `<article>` y `<footer>`.
- **Estilos CSS3 Externos**: Uso de variables, Google Fonts (`Roboto` y `Open Sans`), fondo con degradados modernos y reset CSS.
- **Diseño Responsivo**:
  - **Flexbox**: Aplicado a la barra de navegación y las tarjetas de productos.
  - **CSS Grid Layout**: Aplicado a la sección de reseñas de usuarios.
  - **Media Queries**: Adaptación completa para dispositivos móviles (pantallas menores a 768px).
- **Contenido Multimedia**: Inclusión de imágenes decorativas e integración de iframe de video.
- **Formulario Funcional**: Integración con [Formspree](https://formspree.io) para recibir mensajes directamente.

## Configuración de Formspree
El formulario ubicado en la página de contacto está conectado al servicio Formspree mediante el método `POST`. Esto permite procesar y enviar las consultas enviadas por los usuarios directamente al correo electrónico configurado sin necesidad de disponer de un servidor propio (Back-End).