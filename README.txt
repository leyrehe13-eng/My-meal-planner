# My Meal Planner 🌸 — versión app

Esta carpeta es una Progressive Web App (PWA) de My Meal Planner.

## Para instalarla como una app en Android
1. Sube esta carpeta a un alojamiento HTTPS (por ejemplo GitHub Pages, Netlify o Vercel).
2. Abre la URL resultante en Chrome en el móvil.
3. En Chrome, elige **Instalar aplicación** / **Añadir a pantalla de inicio**.
4. Se abrirá como una app independiente, sin la barra normal del navegador.

## Importante
- El HTML conserva la aplicación actual.
- Los datos siguen guardándose en el almacenamiento local del navegador.
- El Service Worker permite que la app cargue incluso sin conexión después de haberla abierto una vez.
- Para actualizar una versión futura, cambia el identificador CACHE en `sw.js` (por ejemplo v2).
