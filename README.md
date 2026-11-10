# Un ramito para María

Experiencia web romántica e interactiva creada como regalo personal, para uso privado y sin fines comerciales.

## Proyecto

La versión incluida conserva la composición visual original en tonos ciruela y violeta: ramo de violetas enmarcado, carta, sobre animado y sorpresas. El diseño general no se ha rediseñado.

## Contenido

- `index.html`: página principal con HTML, CSS y JavaScript.
- `bouquet.svg`: ilustración principal del ramo de violetas, mostrada como imagen SVG externa.
- `favicon.svg`, `app-icon.svg` y `apple-touch-icon.png`: iconos.
- `manifest.webmanifest`: configuración PWA.
- `sw.js`: service worker y recursos esenciales de caché offline.
- `assets/music/README.md`: nota para la integración musical pendiente.

## Funciones presentes

- Diseño responsive.
- Ramo SVG con proporción y tamaño explícitos para evitar que desaparezca en pantallas móviles.
- Pétalos animados y efecto de floración al tocar el ramo.
- Sobre interactivo y carta con efecto de escritura.
- Frase sorpresa al final de la carta.
- Dos tarjetas rasca y gana secuenciales.
- Acciones para volver a leer la carta y ver los regalos.
- Aviso de instalación PWA y service worker con caché actualizado (v6).

## Música (pendiente)

La integración de `CONTIGO` queda expresamente pendiente para la siguiente sesión. No se incluye ningún archivo de audio en este paquete, para que el repositorio pueda subirse ahora sin la pista musical.

## Ejecutar localmente

```bash
python -m http.server 8000
```

Abre `http://localhost:8000`. Usa `localhost` o HTTPS para probar service workers e instalación PWA.

## Despliegue en Vercel

Es un sitio estático. Sube los archivos de esta carpeta a la raíz del repositorio, importa el repositorio en Vercel y deja vacíos el comando de build y el directorio de salida.

## Uso privado y no comercial

Consulta `LICENSE.md` y `RIGHTS.md`. Mantén el repositorio como **Private** para evitar que terceros puedan consultar el contenido. Los recursos de terceros mantienen los derechos de sus titulares.

## Verificación

El ramo independiente se ha validado como SVG y el HTML apunta explícitamente a `/bouquet.svg`. La experiencia debe probarse también en el móvil real después de subirla y desplegarla.
