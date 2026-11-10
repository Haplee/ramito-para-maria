# Nota de recuperación

Fuente principal: despliegue de producción `ramito-para-maria-9nov` en Vercel, consultado el 10-11-2026.

Archivos recuperados del despliegue:
- index.html
- bouquet.svg
- favicon.svg
- app-icon.svg
- manifest.webmanifest
- sw.js

Recurso recuperado del espacio de trabajo:
- apple-touch-icon.png
- assets/music/CONTIGO - Lucho RK (Visualizer).mp3

Limitaciones conocidas:
- No aparece ningún archivo MP3 en el árbol de archivos del despliegue consultado.
- El HTML desplegado no contiene un elemento de audio ni integra reproducción musical.
- La ruta `/apple-touch-icon.png` respondía 404 en el despliegue, aunque existía un icono local; se incorpora este último para completar la carpeta.
- El paquete es una recuperación del código desplegado, no una corrección certificada de todos los problemas de interacción móvil.
