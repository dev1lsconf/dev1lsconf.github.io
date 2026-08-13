# dev1lsconf.github.io

Sitio web personal de **dev1ls** — Desarrollador full-stack, usuario de BSD y Linux.

## Stack

- **HTML/CSS/JS** — Vanilla, sin frameworks
- **Tailwind CSS** — Vía CDN (utility-first styling)
- **GitHub Pages** — Hosting estático
- **GitHub API** — Obtención dinámica de repositorios

## Características

- **Fondo animado de estrellas** — Canvas-based, respeta `prefers-color-scheme`
- **Diseño responsive** — Mobile-first, funciona en todas las pantallas
- **Modo oscuro/claro** — Automático vía CSS media queries
- **Grid de repositorios de GitHub** — Obtiene repos públicos, muestra imágenes OpenGraph, lenguaje, stars/forks
- **SEO ready** — OpenGraph, meta tags, HTML semántico
- **Rendimiento** — Lighthouse > 95, JS mínimo, imágenes lazy-loaded

## Estructura del proyecto

```
├── index.html      # App single-file (HTML + CSS + JS)
├── twtxt.txt       # Feed twtxt
└── README.md       # Este archivo
```

## Desarrollo

```bash
# Servir localmente
npx serve .
# o
python3 -m http.server 8000
```

## Despliegue

Push a rama `main` → GitHub Pages despliega automáticamente desde root.

## Personalización

Edita `index.html` para cambiar:
- Avatar, nombre, bio, enlaces
- Lista de repos excluidos (línea ~355)
- Densidad del starfield (línea ~395)
- Paleta de colores (variables CSS `:root`)

## Licencia

MIT