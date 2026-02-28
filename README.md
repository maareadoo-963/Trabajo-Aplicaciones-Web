# Jornada Tecnológica 2025 - Web informativa

Proyecto de página web estática para la **Jornada Tecnológica 2025**, un evento de tres días sobre innovación, desarrollo y futuro digital. Desarrollada con **Bootstrap 5** y **CSS personalizado**.

## Estructura y secciones

- **Navbar**: menú responsive con enlaces a las secciones.
- **Hero**: presentación principal con imagen de fondo, título, fecha, lugar y botón.
- **Sección 1 (Información)**: grid de 2 columnas (col-md-6) con tarjetas para fechas y lugar.
- **Sección 2 (Ponentes)**: grid de 3 columnas (col-md-6 col-lg-4) con cards de ponentes destacados.
- **Componente extra (Agenda)**: acordeón de Bootstrap con la programación por días.
- **Footer**: información de contacto y enlaces legales.

## Componentes de Bootstrap utilizados

- Navbar
- Cards
- Accordion
- Sistema de grid (row, col)
- Botones
- Utilidades de espaciado, color y tipografía

## CSS personalizado

Se ha creado el archivo `estilo.css` para añadir:
- Efectos hover en las cards (sombra y elevación)
- Transiciones suaves
- Ajustes de tipografía en navbar
- Mejoras responsive para móviles

## Commits realizados

### Commit 1: `Initial commit - Estructura HTML, navbar y hero section`
*Primera versión del proyecto. Se crea la estructura base con navbar, hero y footer básico.*

### Commit 2: `Añadidas secciones de información, ponentes y acordeón`
*Se completa el contenido: secciones con grid, ponentes con imágenes y acordeón de agenda.*

### Commit 3: `PRINCIPAL - Añadido CSS personalizado y documentación completa`
*Se añade archivo `estilo.css` con estilos propios, se enlaza en el HTML y se completa la documentación con capturas.*

## Dificultad encontrada y solución

**Dificultad:** Conseguir que las cards de los ponentes mantuvieran la misma altura y tuvieran un efecto visual atractivo sin afectar al responsive.

**Solución:** Se utilizó la clase `h-100` de Bootstrap para igualar alturas y se creó un archivo CSS externo con efectos hover (transform y box-shadow) que mejoran la experiencia sin romper el diseño en móviles.

## Capturas

Las capturas están en la carpeta [`CAPTURAS`](./CAPTURAS):

- `web-final.png`
- `thunderbird.png`
- `configuracion-correo.png`
- `GitHubDesktop`
- `GitHubDesktop-2`
