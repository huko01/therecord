# The Record

PWA local para tu biblioteca de álbumes. Datos de iTunes Search API (sin clave), guardado en IndexedDB.

## Publicarla (gratis, necesita HTTPS)
- **Netlify Drop**: entra en app.netlify.com/drop y arrastra esta carpeta.
- **Cloudflare Pages / GitHub Pages**: sube estos archivos tal cual a la raíz del sitio.

## Instalarla en el móvil
- iPhone: abre el enlace en Safari > Compartir > Añadir a pantalla de inicio.
- Android: Chrome > menú > Instalar app.

## Archivos
index.html (toda la app), manifest.json, sw.js (offline), icons/.

## Biblioteca
Botón junto a los de vista (abajo): ver todos/favoritos/pendientes, filtrar por artista o color, ordenar y mostrar solo álbumes o EPs. Al añadir un álbum a la biblioteca (+) el botón desaparece y abajo, junto a los botones de info y reproducir, aparecen favorito (★), pendiente y borrar (papelera roja, pide confirmación).

## Ajustes
Icono de engranaje (arriba). Hoja con perfil (nombre + foto + contadores), idioma ES/EN, tema oscuro/claro (con transición circular), servicio de reproducción, país de la tienda, exportar/importar copia en JSON, recordatorio de copia y borrado de biblioteca con confirmación. Se cierra arrastrando hacia abajo.
