# Nutrición & Entrenamiento – Landing Page

Landing estática (HTML/CSS/JS) optimizada para clientes de clase media–alta. Incluye secciones de héroe, beneficios, método Z‑FIT 180, planes, testimonios, formulario de contacto y dos espacios de video.

## Estructura
- `index.html` – página principal
- `assets/favicon.svg` – icono del sitio
- `.gitignore` – ignora archivos temporales
- `LICENSE` – MIT

## Cómo publicar en **GitHub Pages**
1. Crea un repositorio nuevo (público) y sube estos archivos.
2. En **Settings → Pages**:
   - Source: `Deploy from a branch`
   - Branch: `main` y carpeta `/root`
3. Tu sitio quedará disponible en `https://<tu-usuario>.github.io/<tu-repo>/`

> Tip: Si quieres dominio propio, crea un archivo `CNAME` con tu dominio y apunta un CNAME en tu DNS a `<tu-usuario>.github.io`.

## Edita tus datos
- Formulario: en `index.html` busca `action="https://formspree.io/f/xxxxxxxx"` y reemplázalo por tu endpoint de Formspree.
- WhatsApp: reemplaza `https://wa.me/5210000000000` por tu número en formato internacional.
- Videos: reemplaza los `src=""` de los `<video>` o usa embeds de YouTube/Vimeo.

## Alternativas de hosting gratis
- **Netlify** (drag & drop) – sube la carpeta y listo.
- **Vercel** – importa el repo y despliega a `.vercel.app`.
- **Cloudflare Pages** – conecta el repo para CDN global.
- **Surge** – `npm i -g surge` y `surge ./` para publicar a `.surge.sh`.

## Desarrollo local
Solo abre `index.html` en tu navegador. No requiere Node ni backend.

## Licencia
MIT © 2025 Nutrición & Performance
