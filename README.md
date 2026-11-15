# Ian Toledo — Portfolio v11

Portfolio en HTML, CSS y JavaScript. Abrí `index.html` en Chrome para probarlo.

## Video principal del hero
En la carpeta `videos`, colocá un único video horizontal llamado `hero-showcase.mp4` (relación 16:9). Aparecerá en el panel principal con controles de reproducción y borde Solar Lime. La etiqueta debajo dice: “UNA IMAGEN, CONTENIDO SIN LÍMITE”.

## Imágenes
Carpeta `images`:
- `persona-01.jpg` a `persona-05.jpg`: personas reales para el primer carrusel.
- `avatar-01.jpg` a `avatar-05.jpg`: avatares IA para el segundo carrusel.

Las imágenes de los carruseles deben ser cuadradas (1:1). Los carruseles cambian solos cada 5 segundos y también tienen flechas y navegación por deslizamiento.

## Otros videos
Carpeta `videos`:
- `reel-01.mp4`, `reel-02.mp4`, `reel-03.mp4`: los tres reels de referencia.
- `avatar-01.mp4`, `avatar-02.mp4`: videos de las tarjetas de avatares.

Usá MP4 (H.264), preferentemente comprimidos para que la página cargue rápido.

## Antes de publicar
- Reemplazá `TU_EMAIL@EJEMPLO.COM` por tu correo real.
- Colocá cada imagen y video en su carpeta usando exactamente los nombres indicados.
- Usá solamente material propio o con autorización.

## Publicar gratis con GitHub Pages
1. Creá un repositorio público llamado `portfolio` en GitHub.
2. Subí el contenido de esta carpeta; `index.html` debe quedar en la raíz del repositorio.
3. Abrí Settings → Pages.
4. Elegí Deploy from a branch, rama `main` y carpeta `/ (root)`.
5. Guardá. GitHub Pages publicará el sitio en una dirección del tipo `https://usuario.github.io/portfolio/`.

Nota: si el video principal es pesado, comprimilo o alojalo en una plataforma de video y embeberlo en la web.


## Navegación de carruseles (v12)
- Las flechas visibles se eliminaron.
- Hacé clic en la imagen lateral para llevarla al centro.
- En celular, deslizá con el dedo; en computadora, podés arrastrar con el mouse.
- Los carruseles avanzan automáticamente cada 5 segundos.
- Al pasar el mouse por encima, la reproducción automática se pausa y vuelve al salir.
- También se puede enfocar una imagen lateral con Tab y seleccionarla con Enter o espacio.


## Navegación de carruseles (V13)
- Posicionamiento corregido: cada imagen se centra desde el contenedor, evitando que la imagen activa se corte por un desplazamiento acumulado.
- Una imagen central completa y las imágenes vecinas parcialmente visibles a los costados.
- Sin flechas: clic en las imágenes laterales, arrastre con mouse o swipe en celular.
- Avance automático cada 5 segundos.
- El autoplay se pausa al pasar el mouse por encima y vuelve a activarse al salir.
