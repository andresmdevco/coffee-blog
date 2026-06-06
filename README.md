# ☕ Blog de Café

Sitio web estático de un blog de café. Incluye secciones de blog, cursos, sobre nosotros y un formulario de contacto.

## 📄 Páginas

| Archivo | Descripción |
|---|---|
| `index.html` | Página principal con listado de entradas del blog y sidebar de cursos |
| `nosotros.html` | Sección "Sobre Nosotros" con imagen y texto descriptivo |
| `entrada.html` | Vista de detalle de una entrada del blog |
| `cursos.html` | Listado de cursos y talleres disponibles |
| `contacto.html` | Formulario de contacto con imagen de fondo |

## 🛠️ Tecnologías utilizadas

- **HTML5** — Estructura semántica con etiquetas como `<header>`, `<main>`, `<aside>`, `<article>`, `<footer>`
- **CSS3** — Estilos con variables CSS, Flexbox y CSS Grid para el layout responsivo
- **Google Fonts** — Tipografías `PT Sans` y `Open Sans`
- **Modernizr** — Detección de características del navegador (soporte de imágenes WebP)

## ✨ Características

- **Diseño responsivo** — Layout adaptable a móviles y escritorio mediante media queries (`min-width: 768px`)
- **CSS Grid y Flexbox** — Utilizados para estructurar el contenido principal, la sección de cursos y el formulario de contacto
- **Imágenes optimizadas** — Uso del elemento `<picture>` con fuentes en formato `.webp` y `.jpg` como fallback
- **Lazy loading** — Las imágenes cargan de forma diferida con el atributo `loading="lazy"`
- **Optimización de carga** — Uso de `<link rel="preload">`, `<link rel="prefetch">` y `<link rel="preconnect">` para mejorar el rendimiento
- **Variables CSS** — Paleta de colores y tipografías centralizadas con custom properties en `:root`
- **Detección de WebP** — Mediante Modernizr, se aplica la imagen de banner en `.webp` o `.jpg` según soporte del navegador

## 🎨 Paleta de colores

| Variable | Color |
|---|---|
| `--primario` | `#784D3C` |
| `--gris` | `#E1E1E1` |
| `--blanco` | `#FFFFFF` |
| `--negro` | `#000000` |

## 🚀 Cómo ejecutar el proyecto

Al ser un sitio completamente estático, no requiere instalación ni dependencias adicionales.

1. Clonar o descargar el repositorio.
2. Abrir el archivo `index.html` directamente en el navegador.

```bash
# Opcionalmente, puedes usar la extensión Live Server de VS Code
# o cualquier servidor local estático
```

## 📚 Conceptos practicados

- Maquetación con **CSS Grid** y **Flexbox**
- Uso de **variables CSS** (custom properties)
- Metodología de nomenclatura de clases con estilo **BEM**
- Optimización de rendimiento web con `preload`, `prefetch` y `preconnect`
- Imágenes responsivas con el elemento `<picture>` y formatos modernos (**WebP**)
- Detección de soporte de características con **Modernizr**
