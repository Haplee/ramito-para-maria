# Nota de recuperación y ajuste del ramo

Fuente del proyecto: despliegue de producción `ramito-para-maria-9nov` en Vercel, consultado el 10-11-2026.

Archivos recuperados del despliegue o de los recursos disponibles:
- `index.html`
- `bouquet.svg`
- `favicon.svg`
- `app-icon.svg`
- `manifest.webmanifest`
- `sw.js`
- `apple-touch-icon.png`

Ajuste realizado para que el ramo se muestre de forma fiable:
- La página utiliza ahora el archivo visual `bouquet.svg` directamente como imagen principal, en lugar de la variante SVG inline anterior.
- La imagen declara dimensiones y relación de aspecto 520:530.
- El CSS de la imagen principal fuerza ancho completo, altura automática, visibilidad y ausencia de altura mínima heredada.
- El service worker pasa a `ramito-maria-v6` y precarga expresamente el ramo y los iconos para su disponibilidad offline.

La ilustración se ha validado como SVG XML y se ha comprobado que la página referencia `/bouquet.svg`.

La música se deja expresamente para la siguiente sesión: no se incluye MP3 ni lógica de reproducción en esta entrega.
