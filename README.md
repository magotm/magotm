# Mago TM — Sitio web

Página del canal de YouTube **Mago TM** (diseño de intros 3D): Inicio, Lecciones y Tienda.

## Estructura del proyecto

```
mago-tm-site/
├── index.html      → contenido y estructura de la página
├── css/
│   └── style.css   → todos los estilos
└── README.md
```

## Antes de publicar

Edita `index.html` y reemplaza:

- **`TUNUMERO`** dentro del botón "Comprar Introducción 3D" (en la sección Tienda) por tu número de WhatsApp, con código de país y sin espacios ni `+`. Ejemplo: `51987654321`.
- **`$XX`** por el precio real de la intro, o déjalo como "a confirmar".
- El contenido de las 6 tarjetas de "Lecciones" y la descripción del producto, si quieres personalizarlos.

## Cómo subirlo a GitHub

1. Crea un repositorio nuevo en GitHub (puede llamarse `mago-tm` o como prefieras).
2. Desde esta carpeta, en una terminal:

```bash
git init
git add .
git commit -m "Primera versión del sitio Mago TM"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/TU_REPO.git
git push -u origin main
```

## Cómo publicarlo gratis con GitHub Pages

1. En tu repositorio en GitHub, ve a **Settings → Pages**.
2. En "Source", selecciona la rama `main` y la carpeta `/root` (o `/ (root)`).
3. Guarda. En un par de minutos tu página quedará disponible en:
   `https://TU_USUARIO.github.io/TU_REPO/`

No necesitas backend ni servidor: es un sitio estático (HTML + CSS), así que GitHub Pages es suficiente.
