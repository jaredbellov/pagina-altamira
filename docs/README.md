# Altamira Chile — Sitio demo

Sitio estático (HTML) listo para publicar en **GitHub Pages**. Todo usa rutas relativas; no requiere build ni servidor.

## Páginas
- `index.html` — Altamira Chile (holding) · página de inicio
- `altamirachile-cl.html` — Altamira Chile (copia con nombre de dominio)
- `procesadora-teno-norte.html` — Procesadora Teno Norte
- `altamira-frozen.html` — Altamira Frozen
- `assets/` — logos, banderas de idioma, certificaciones e imágenes de frutas

## Idiomas
Selector de banderas arriba a la derecha: Español · English · 中文 · 日本語.

## Cómo publicarlo en GitHub Pages
1. Crea un repositorio en GitHub (por ejemplo `altamira-chile`).
2. Sube **el contenido de esta carpeta** a la raíz del repo (que `index.html` quede en la raíz).
3. En el repo: **Settings → Pages**.
4. En *Build and deployment → Source* elige **Deploy from a branch**.
5. Branch: `main` (o `master`) · carpeta: `/ (root)` · **Save**.
6. En 1–2 minutos quedará disponible en:
   `https://TU-USUARIO.github.io/altamira-chile/`

> El archivo `.nojekyll` ya está incluido para que GitHub sirva todos los archivos tal cual.

## Formulario de contacto
- Cada página tiene un formulario que, al enviarlo, abre el correo del cliente con el mensaje prellenado hacia **jfv@altamirachile.cl** (asunto + Nombre / Correo / Empresa / Mensaje).
- Es un sitio estático (sin servidor), por eso usa el cliente de correo del visitante. Si más adelante quieres que el envío sea automático sin abrir el correo, se puede conectar un servicio de formularios (ej. Formspree) — avísame.

## SEO
- Cada página incluye título optimizado, meta description, Open Graph/Twitter (para compartir en redes/WhatsApp) y datos estructurados JSON-LD (Organization) para Google.
- Antes de publicar definitivamente: reemplaza `https://TU-DOMINIO/` en `robots.txt` y `sitemap.xml` por tu dominio real (o `https://TU-USUARIO.github.io/REPO/`) y envía el sitemap en Google Search Console.
- Para mejor posicionamiento local, registra el negocio en Google Business Profile con la misma dirección (Teno, Región del Maule).

## Notas
- Las imágenes de planta/campos están incrustadas; para subirlas en mayor resolución, reemplázalas con los originales en alta.
- Los logos de certificación y de marca están en `assets/` por si quieres actualizarlos.
