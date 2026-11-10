# Un ramito para María

Experiencia web romántica e interactiva creada como regalo personal, para uso privado y sin fines comerciales.

## Contenido recuperado

Este paquete se ha reconstruido a partir de la última versión que estaba publicada en Vercel y de los recursos locales disponibles en esta conversación.

- `index.html`: página principal con estilos y JavaScript integrados.
- `bouquet.svg`: ilustración SVG independiente del ramo.
- `favicon.svg` y `app-icon.svg`: iconos.
- `apple-touch-icon.png`: icono móvil local de 180 × 180 px; el despliegue consultado devolvía 404 para esta ruta.
- `manifest.webmanifest`: metadatos PWA.
- `sw.js`: service worker y caché offline.
- `assets/music/`: canción MP3 que proporcionaste anteriormente.

## Funciones que aparecen en el código recuperado

- Diseño responsive en tonos ciruela y violeta.
- Ramo SVG integrado directamente en la página.
- Pétalos animados y efecto de floración al tocar el ramo.
- Sobre interactivo y carta con efecto de escritura.
- Frase sorpresa al final de la carta.
- Dos tarjetas rasca y gana secuenciales.
- Acciones para volver a leer la carta y ver los regalos.
- Aviso de instalación PWA y service worker.

## Música

La canción `CONTIGO - Lucho RK (Visualizer).mp3` se incluye como archivo aportado por el usuario. **La versión recuperada de `index.html` no contiene todavía integración de reproducción**: no añade audio ni controla el inicio al abrir el sobre ni el corte al final del segundo estribillo. Se conserva el archivo para no perderlo, sin inventar un punto de corte que no está documentado en el código publicado.

## Ejecutar localmente

Abre una terminal en esta carpeta y ejecuta:

```bash
python -m http.server 8000
```

Visita `http://localhost:8000`. Para probar service workers e instalación PWA, usa `localhost` o un origen HTTPS.

## Desplegar en Vercel

Es un sitio estático, sin proceso de build:

1. Sube el contenido de esta carpeta a la raíz del repositorio.
2. En Vercel selecciona el proyecto y configura el directorio raíz en esta carpeta (si no está en la raíz del repositorio).
3. Deja el comando de build vacío y el output directory vacío.
4. Despliega.

## Uso privado y no comercial

Consulta `LICENSE.md` y `RIGHTS.md`. El propósito no comercial no concede derechos sobre música u otros materiales de terceros. Como el paquete contiene una grabación comercial, mantén el repositorio en **Private** y no redistribuyas públicamente el MP3 salvo que tengas autorización.

## Estado de la recuperación

El HTML, SVG de ramo, favicon, icono de aplicación, manifiesto y service worker se recuperaron del despliegue publicado. El icono PNG se rescató del directorio de trabajo local porque la ruta consultada en producción devolvía 404. La música procede del archivo que habías proporcionado.

Este paquete preserva el código recuperado; no implica que se hayan corregido o probado todos los fallos móviles comunicados anteriormente.
