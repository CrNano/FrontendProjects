# Basic HTML Website

Sitio web multi-página implementado con HTML semántico, CSS moderno y navegación completa.

## Implementación

Este proyecto demuestra la implementación de:
- Sitios web multi-página con navegación
- Formularios HTML5 con validación
- CSS Grid y Flexbox para layouts
- Diseño responsive complejo
- Organización de proyectos profesionales

## Tecnologías Utilizadas

### Navegación Multi-página
```html
<!-- Navegación consistente en todas las páginas -->
<nav>
    <a href="index.html">Home</a>
    <a href="projects.html">Projects</a>
    <a href="articles.html">Articles</a>
    <a href="contact.html">Contact</a>
</nav>
```

### Formularios HTML5
```html
<!-- Formulario de contacto con validación -->
<form action="#" method="post">
    <label for="name">Nombre:</label>
    <input type="text" id="name" name="name" required>
    
    <label for="email">Email:</label>
    <input type="email" id="email" name="email" required>
    
    <label for="message">Mensaje:</label>
    <textarea id="message" name="message" required></textarea>
    
    <button type="submit">Enviar</button>
</form>
```

### CSS Grid y Flexbox
```css
/* CSS Grid para layout de 3 columnas */
section:nth-of-type(2) {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 20px;
}

/* Flexbox para navegación */
nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
}
```

## Estructura del Proyecto

```
02-basic-html-website/
├── index.html              # Página de inicio
├── projects.html           # Página de proyectos
├── articles.html           # Página de artículos
├── contact.html            # Página de contacto
├── styles.css              # Estilos CSS del sitio
├── BasicHTMLWebsite.html   # Archivo original (backup)
└── README.md               # Documentación
```

### Archivos

- **`index.html`** - Página de inicio con hero section y layout de 3 columnas
- **`projects.html`** - Lista de proyectos con enlaces
- **`articles.html`** - Página de artículos del blog
- **`contact.html`** - Formulario de contacto con validación HTML5
- **`styles.css`** - Estilos CSS con Grid, Flexbox y responsive design

## Uso

1. Abrir `index.html` en cualquier navegador
2. Navegar entre las diferentes páginas usando el menú
3. Probar el formulario de contacto
4. Verificar el diseño responsive redimensionando la ventana

## Referencias

- [roadmap.sh - Basic HTML Website Project](https://roadmap.sh/projects/basic-html-website)
- [MDN CSS Grid](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout)
- [MDN Flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout)
- [MDN Forms](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/form)