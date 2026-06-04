# Kinday — Sitio legal

Sitio estático con landing, Aviso de Privacidad y Términos. Listo para hospedar en cualquier servicio de hosting estático.

## Opción más rápida: Netlify Drop (30 segundos, sin git, sin cuenta)

1. Ve a [https://app.netlify.com/drop](https://app.netlify.com/drop)
2. Arrastra **toda esta carpeta** (`legal-site/`) a la zona de "Drag and drop your site folder here"
3. Espera 5 segundos
4. Netlify te da una URL tipo `https://random-words-12345.netlify.app`
5. Esa es tu URL pública

**Tus URLs serán:**
- Privacy Policy: `https://[tu-url].netlify.app/privacy.html`
- Terms: `https://[tu-url].netlify.app/terms.html`

Para personalizar el subdominio:
1. Click en "Site settings" → "Change site name"
2. Cámbialo a `kinday-app` → URL queda `https://kinday-app.netlify.app`

## Opción 2: GitHub Pages (gratis, requiere cuenta GitHub)

1. Crea repo nuevo en GitHub: `kinday-legal`
2. Sube los 3 archivos (`index.html`, `privacy.html`, `terms.html`)
3. Settings → Pages → Source: `main` branch, `/` (root)
4. Tu URL: `https://[tu-user].github.io/kinday-legal/privacy.html`

## Opción 3: Vercel (también drag & drop)

1. Ve a [vercel.com/new](https://vercel.com/new)
2. Importa esta carpeta o conéctala a GitHub
3. Deploy

## Cuando ya tengas dominio kinday.app

Apunta el dominio al hosting que elegiste y las URLs quedan:
- `https://kinday.app/privacy.html`
- `https://kinday.app/terms.html`

## Pegar URL en App Store Connect

Cuando subas la app a App Store:
- En la sección **Privacy Policy URL** → pega la URL de `privacy.html`
- En **Support URL** → pega la URL de `index.html`
- En **Marketing URL** (opcional) → también `index.html`
