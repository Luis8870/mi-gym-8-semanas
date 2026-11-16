MI GYM — INSTALACIÓN EN IPHONE (GRATIS)

IMPORTANTE: NO abras index.html directamente desde Archivos. Una PWA debe servirse desde HTTPS para poder instalarse y funcionar sin conexión.

1. En GitHub.com, crea una cuenta (si aún no tienes).
2. Crea un repositorio PÚBLICO nuevo, por ejemplo: mi-gym-8-semanas.
3. En el repositorio, pulsa Add file > Upload files y sube los CINCO archivos de esta carpeta: index.html, manifest.webmanifest, sw.js, icon-192.png e icon-512.png. NO subas solamente el ZIP.
4. Pulsa Commit changes.
5. Ve a Settings > Pages > Build and deployment > Source: Deploy from a branch > Branch: main / (root) > Save.
6. Cuando GitHub publique la página, verás una dirección parecida a https://TU-USUARIO.github.io/mi-gym-8-semanas/ . Usa la dirección REAL que te muestre GitHub Pages.
7. En el iPhone, abre esa dirección en SAFARI (no en la vista previa de ChatGPT ni en Archivos).
8. Pulsa Compartir > Añadir a pantalla de inicio > Añadir. Abre Mi Gym desde el nuevo ícono.
9. Abre la app una primera vez CON internet. Después de cargarla, prueba modo avión: debe abrir sin conexión desde el ícono.

DATOS Y SEGURIDAD
- Tus entrenamientos se guardan en el almacenamiento local del iPhone; no se envían a GitHub.
- Exporta un JSON de respaldo periódicamente, sobre todo antes de borrar datos del navegador, cambiar de iPhone o reinstalar la aplicación.
- Los datos guardados en la versión HTML abierta desde Archivos no se transfieren automáticamente a la PWA; si puedes abrir la anterior, exporta JSON y luego impórtalo en la PWA.
- No uses modo privado. iOS puede eliminar datos locales si libera espacio o borras datos del sitio.
- Si no puedes ver “Añadir a pantalla de inicio”, confirma que estás usando Safari y la dirección HTTPS publicada.
- Para actualizar la app después de cambiar archivos en GitHub, vuelve a abrirla con internet; luego ciérrala y ábrela de nuevo.
