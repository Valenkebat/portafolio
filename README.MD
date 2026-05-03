# Valentín Kebat — Portfolio

Portfolio personal de Valentín Kebat, Ingeniero de Datos.  
Construido con [Astro](https://astro.build) y desplegado en [Cloudflare Pages](https://pages.cloudflare.com).

## Stack

- **Framework**: Astro 6
- **Hosting**: Cloudflare Pages (adapter `@astrojs/cloudflare`)
- **CSS**: Vanilla CSS con glassmorphism y dark mode
- **i18n**: Español (default) y English

## Comandos

| Comando | Descripción |
|---|---|
| `npm install` | Instalar dependencias |
| `npm run dev` | Servidor local en `localhost:4321` |
| `npm run build` | Build de producción |
| `npm run preview` | Preview del build |

## Despliegue

Conectado a Cloudflare Pages. Cada `git push` a `main` dispara un deploy automático.

- **Build command**: `npm run build`
- **Output directory**: `dist/`
