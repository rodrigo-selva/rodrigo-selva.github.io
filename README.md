# 🚀 Portfolio — Rodrigo Selva

Portfolio personal construido con [Astro](https://astro.build/), desplegado en GitHub Pages.

🌐 **Live:** https://rodrigo-selva.github.io

## Stack

- **Framework:** Astro 4
- **Estilos:** CSS puro con variables (sin librerías externas)
- **Deploy:** GitHub Pages vía GitHub Actions

## Desarrollo local

```bash
# Instalar dependencias
npm install

# Servidor de desarrollo (http://localhost:4321)
npm run dev

# Build de producción
npm run build

# Preview del build
npm run preview
```

## Estructura

```
src/
├── components/
│   ├── Nav.astro
│   ├── Hero.astro
│   ├── About.astro
│   ├── Skills.astro
│   ├── Projects.astro
│   └── Contact.astro
├── layouts/
│   └── Layout.astro
└── pages/
    └── index.astro
```

## Deploy

El deploy es automático al hacer push a `main` gracias al workflow de GitHub Actions en `.github/workflows/deploy.yml`.

Para activarlo:
1. Ve a **Settings → Pages** en tu repo
2. En **Source** selecciona **GitHub Actions**
3. Haz push y listo 🎉
