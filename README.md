# Invitación XV años de Nicole

## Publicar en GitHub Pages
1. Crea un repositorio público en GitHub, por ejemplo `invitacion-Nicole`.
2. Sube `index.html` y la carpeta `assets`.
3. En Settings → Pages, selecciona Deploy from a branch, rama `main`, carpeta `/ (root)`, y guarda.
4. Espera a que GitHub publique el sitio.

## Antes de publicar
Abre `index.html` y busca `const CONFIG` al final:
- `whatsapp`: reemplaza `51999999999` por el número familiar real, con código de país y solo números.
- `eventDate`, `dateLabel`, `calendarMonth`, `calendarYear`, `calendarDay`: actualiza la fecha y hora correctas.
- Revisa la dirección y el enlace de Google Maps en la sección `id="lugar"`.

## Archivos multimedia
- `assets/cancion.mp3`: añade la canción que quieras reproducir al tocar el corazón. Usa un archivo que tengas derecho a publicar.
- `assets/trailer.mp4`: añade un video que tengas autorización para usar. El reproductor lo mantiene silenciado.
- Las imágenes de referencia recibidas están guardadas en `assets/*-referencia.webp`. Son referencias de diseño; puedes sustituirlas por imágenes propias o con licencia.

## Funcionalidad de los formularios
Los formularios abren WhatsApp con el mensaje rellenado. El invitado debe pulsar enviar dentro de WhatsApp. Para guardar respuestas automáticamente en una base de datos se necesitaría integrar un servicio adicional.

## Nota sobre derechos de autor
La película *La princesa y el sapo*, sus personajes, tráiler y música tienen derechos de autor. No se incluye el tráiler ni la canción en este paquete. Utiliza contenido autorizado o enlaza un video oficial permitido. La temática correcta es La Bella y la Bestia: rosas encantadas, castillo, baile de gala y una estética de cuento de hadas en tonos dorados, marfil y azul/rojo de la rosa encantada. No usar personajes ni elementos de La princesa y el sapo.
