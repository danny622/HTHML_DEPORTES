# Guía de Computadoras - Proyecto HTML

## Lo que aprendí en este proyecto:

1. **Estructura HTML semántica**:
   - Uso correcto de `<header>`, `<nav>`, `<main>`, `<article>`, `<section>` y `<footer>`
   - Importancia de la jerarquía de encabezados (`<h1>` a `<h6>`)

2. **Formateo de texto**:
   - Diferencias entre `<b>` (solo estilo) y `<strong>` (importancia semántica)
   - Cuándo usar `<i>` vs `<em>`
   - Aplicación de `<mark>`, `<small>`, `<del>`, `<ins>`, `<sub>`, `<sup>`

3. **Citas y referencias**:
   - `<blockquote>` para citas largas con atributo `cite`
   - `<q>` para citas cortas (automáticamente entre comillas)
   - `<abbr>` con `title` para abreviaturas y acrónimos

4. **Estilos CSS**:
   - Tres formas de aplicar estilos (inline, interno y externo)
   - Selectores básicos (elementos, clases, IDs)
   - Propiedades como `color`, `background-color`, `font-family`, `padding`, `margin`

5. **Imágenes**:
   - Atributos esenciales: `src`, `alt` (accesibilidad), `title` (tooltip)
   - Organización en carpetas dedicadas
   - Buenas prácticas para nombres de archivos

6. **Navegación**:
   - Creación de menús consistentes
   - Rutas relativas (`../` para subir niveles)
   - Estilización de enlaces

7. **Tablas**:
   - Estructura básica con `<table>`, `<tr>`, `<th>`, `<td>`
   - Atributo `border` para debugging (no recomendado en producción)

8. **Proyecto organizado**:
   - Estructura de carpetas (css, images)
   - Archivos separados para diferentes propósitos
   - Importancia del README para documentación

## Ejemplos de aplicación:
```html
<!-- Ejemplo de semántica + estilo -->
<article style="border: 1px solid #ddd; padding: 15px;">
    <h2>Título del artículo</h2>
    <p>Contenido <mark>resaltado</mark> y <small>secundario</small>.</p>
</article>

<!-- Ejemplo de cita con referencia -->
<blockquote cite="https://ejemplo.com">
    "Texto citado"
    <footer>- Autor</footer>
</blockquote>
```

## Validación:
- Todas las páginas pasan el validador W3C HTML5
- CSS organizado y minificado para producción