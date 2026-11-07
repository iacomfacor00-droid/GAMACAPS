# GAMA CAPS

Tienda online estática de gorras (HTML, CSS y JavaScript, sin dependencias).

## Configuración
Abre `index.html` y edita el bloque `CONFIGURACIÓN` al inicio del `<script>`:
- `WHATSAPP`: número con código de país, sin + ni espacios.
- `SOCIAL`: enlaces de Instagram, Facebook y TikTok (las vacías no se muestran).
- `products`: catálogo (nombre, tipo, color, precio y foto opcional en `img`).
- Video: `video/gama-caps.mp4` (y su portada `video/poster.jpg`). Reemplaza el archivo para cambiar el video.

## Publicar
- **Vercel:** importa el repositorio de GitHub, framework "Other", sin build command. Se despliega `index.html` directamente.
- **GitHub Pages:** Settings > Pages > Deploy from branch > `main` / root.
