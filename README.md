# Eddy Wine - Experiencias Gourmet 🍷

Sitio web elegante y optimizado para SEO de una compañía especializada en catas de vino y experiencias gourmet en Saltillo, Coahuila.

## 🌟 Características

- ✨ **Diseño Elegante**: Interfaz moderna con colores vino y dorado
- 📱 **Responsive**: Totalmente adaptable a dispositivos móviles
- 🚀 **Alto Rendimiento**: Construido con Astro para máxima velocidad
- 🔍 **SEO Optimizado**: Meta tags y keywords optimizados para "catas de vino en Saltillo"
- 🖼️ **Galería Interactiva**: PhotoSwipe para experiencia de visualización premium
- 🎨 **Hero Impactante**: Imagen a pantalla completa con filtro elegante

## 📦 Tecnologías

- **Astro** - Framework web moderno
- **PhotoSwipe** - Galería de imágenes lightbox
- **Google Fonts** - Playfair Display & Raleway
- **CSS Modern** - Grid, Flexbox, Animaciones

## 🚀 Inicio Rápido

### Instalación

```bash
npm install
```

### Desarrollo

```bash
npm run dev
```

El sitio estará disponible en `http://localhost:4321`

### Build para Producción

```bash
npm run build
```

### Preview del Build

```bash
npm run preview
```

## 📸 Imágenes Requeridas

⚠️ **IMPORTANTE**: Antes de desplegar, debes agregar imágenes en `public/images/`

Ver archivo `IMAGENES.md` para instrucciones detalladas.

Archivos necesarios:
- `hero-wine.jpg` (1920x1080px) - Imagen principal del hero
- `about-wine.jpg` (800x800px) - Imagen de la sección About
- `gallery-1.jpg` a `gallery-6.jpg` (1200x800px) - Imágenes de la galería

## 🌐 Despliegue en Vercel

### Opción 1: Desde GitHub

1. Sube el proyecto a GitHub
2. Ve a [vercel.com](https://vercel.com)
3. Haz clic en "New Project"
4. Importa tu repositorio
5. Vercel detectará automáticamente Astro
6. Haz clic en "Deploy"

### Opción 2: Vercel CLI

```bash
npm i -g vercel
vercel
```

### Opción 3: Conectar Git

```bash
git init
git add .
git commit -m "Initial commit"
git remote add origin [tu-repositorio]
git push -u origin main
```

Luego conecta desde Vercel Dashboard.

## 🎨 Personalización

### Colores

Edita las variables CSS en `src/components/Layout.astro`:

```css
:root {
  --color-primary: #8B1538;    /* Vino */
  --color-secondary: #D4AF37;  /* Dorado */
  --color-dark: #1a1a1a;       /* Negro */
  --color-light: #f8f5f0;      /* Beige */
}
```

### Contenido

- **Hero**: `src/components/Hero.astro`
- **About**: `src/components/About.astro`
- **Galería**: `src/components/Gallery.astro`
- **Redes Sociales**: `src/components/Social.astro`
- **Footer**: `src/components/Footer.astro`

### SEO

Edita los meta tags en `src/components/Layout.astro` y `src/pages/index.astro`

## 📱 Redes Sociales

Actualiza los enlaces en `src/components/Social.astro`:

- Facebook
- Instagram  
- WhatsApp (actualiza el número de teléfono)
- Email

## 📞 Contacto

Actualiza la información de contacto en `src/components/Social.astro`:

- Teléfono: `+52 (811) 123-4567`
- Email: `contacto@eddywine.com`
- Ubicación: `Saltillo, Coahuila, México`

## 🔧 Scripts Disponibles

- `npm run dev` - Servidor de desarrollo
- `npm run build` - Construir para producción
- `npm run preview` - Previsualizar build
- `npm run astro` - CLI de Astro

## 📂 Estructura del Proyecto

```
eddywine/
├── public/
│   ├── images/           # ⚠️ Agregar imágenes aquí
│   ├── favicon.svg
│   └── robots.txt
├── src/
│   ├── components/
│   │   ├── Layout.astro
│   │   ├── Hero.astro
│   │   ├── About.astro
│   │   ├── Gallery.astro
│   │   ├── Social.astro
│   │   └── Footer.astro
│   └── pages/
│       └── index.astro
├── astro.config.mjs
├── vercel.json
└── package.json
```

## 🎯 SEO Keywords

- Catas de vino en Saltillo
- Experiencias gourmet Saltillo
- Maridaje vino Saltillo
- Eventos de vino Saltillo
- Degustación de vinos Coahuila
- Cata privada de vinos

## 📄 Licencia

Copyright © 2025 Eddy Wine - Experiencias Gourmet

---

**Próximos Pasos:**
1. ✅ Proyecto creado
2. 📸 Agregar imágenes (ver IMAGENES.md)
3. 🔧 Personalizar contenido
4. 🚀 Deploy a Vercel

Desarrollado con ❤️ y 🍷
