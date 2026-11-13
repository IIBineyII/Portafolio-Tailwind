# Portafolio | Brayan Garcia Ruiz

Página de presentación hecha con HTML y **Tailwind CSS v4** (build en el navegador por CDN, sin instalar nada).

## Estructura

```
portafolio-brayan/
├── index.html
├── assets/img/
│   ├── caballero-casco.svg
│   └── caballero-hoguera.svg
├── .gitignore
└── README.md
```

## Ver en local

Abre `index.html` en el navegador (o usa Live Server en VS Code). Necesita internet para cargar Tailwind y las fuentes.

## Subir a GitHub

```bash
git init
git add .
git commit -m "Portafolio inicial"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/portafolio-brayan.git
git push -u origin main
```

## Publicar con GitHub Pages

Settings → Pages → Branch `main` → carpeta `/ (root)` → Save.

## Personalizar

- Colores y fuentes: bloque `@theme` dentro de `index.html`.
- Imágenes: reemplaza los SVG de `assets/img/` (conserva los nombres o actualiza las rutas).
