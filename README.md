# Quesos

## Propósito del proyecto

Esta página web fue creada como parte de una tarea para la clase de Diseño Web. El propósito es presentar información sobre distintos tipos de queso de forma clara y organizada, aplicando buenas prácticas de HTML5 semántico y accesibilidad.

## Características

- `index.html`: Página principal con definición y enlaces a cada tipo de queso.
- `cheddar.html`, `gouda.html`, `camembert.html`, `brie.html`, `emmental.html`.: Páginas individuales de cada queso, definición, origen y proceso de elaboración.
- `estilo.css`: Archivo de estilos externa compartida entre las páginas.
- `assets/`: Carpeta que contiene imágenes usadas en la página (`cheddar.webp`, `brie.webp`, `camembert.jpg`, `gouda.jpg`, `emmental.jpg`.).
- Diseño centrado, fondo oscuro y texto blanco para mejor legibilidad. Títulos en amarillo para resaltar las secciones de la página.
- Navegación sencilla y amigable.

## Estructura del proyecto

```
├── index.html                # Página principal
├── camembert.html            # Página individual: Queso Camembert
├── gouda.html                # Página individual: Queso Gouda
├── emmental.html             # Página individual: Queso Emmental
├── brie.html                 # Página individual: Queso Brie
├── cheddar.html              # Página individual: Queso Cheddar
├── README.md                 # Este archivo
├── assets/
│   ├── style.css             # Archivo con los estilos CSS
│   ├── camembert.jpg         # Imágenes de los quesos
│   ├── gouda.jpg
│   ├── emmental.jpg
│   ├── brie.jpg
│   ├── cheddar.jpg
```

## Semántica y accesibilidad

- Se utilizaron etiquetas semánticas como `<header>`, `<main>`, `<section>`, `<nav>`, `<footer>`, `<ul>`, `<li>`, `<h1>`–`<h2>`, para estructurar la información correctamente.
- El atributo `lang="es"` en la etiqueta `<html>` indica el idioma principal del sitio, ayudando a los lectores de pantalla y motores de búsqueda. 
- Se incluyeron atributos `alt` en todas las imágenes para usuarios con lectores de pantalla.
- Los enlaces (`<a>`) son descriptivos y permiten regresar fácilmente al menú.
- La navegación puede hacerse con teclado (usando `Tab`) gracias a elementos enfocados correctamente.
- Se agregó soporte visual de `:focus` en los estilos para mejorar la experiencia con teclado.
- Los colores y el tamaño de fuente dan buen contraste y legibilidad para personas con baja visión.
- El diseño responsive y el uso de bloques grandes y centrados se adapta dispositivos móviles y la navegación táctil.

## Cómo ver la página

1. Descarga el proyecto (o clónalo desde GitHub).
2. Abre el archivo `index.html` con tu navegador.
3. Navega entre las páginas usando los enlaces disponibles.

## Autor

Valeria Hernández Vargas  
Clase: Diseño Web – Universidad  
Año: 2025
