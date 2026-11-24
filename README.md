# Penagos & Aké · Firma Legal — sitio web (vista previa)

Sitio estático preparado por digiLab. Se publica tal cual en GitHub Pages.

## Contenido

- `index.html` — menú de bienvenida con las dos versiones.
- `v3/index.html` — **Versión A (v3)**: portada con el emblema animado.
- `v4/index.html` — **Versión B (v4)**: portada con video de la plumilla.
- `assets/` — logo, emblema, video y fotografías.
- `.nojekyll` — indica a GitHub Pages que publique los archivos sin procesarlos.

## Publicar en GitHub Pages

1. Cree un repositorio nuevo en GitHub (por ejemplo `penagos-ake-web`).
2. Suba **el contenido** de esta carpeta a la raíz del repositorio. En GitHub: *Add file → Upload files*, arrastre todo y confirme.
3. Vaya a *Settings → Pages*. En *Build and deployment* elija *Deploy from a branch*, la rama `main` y la carpeta `/ (root)`. Guarde.
4. En uno o dos minutos el sitio queda en `https://<usuario>.github.io/penagos-ake-web/`. Al abrir el enlace aparece el menú; las versiones están en `/v3/` y `/v4/`.

## Antes del lanzamiento

- Los datos entre [corchetes] son pendientes del despacho (formulario enviado).
- Al elegir la versión final, reemplace `index.html` por la página de esa versión (y ajuste las rutas `../assets/` a `assets/`).
- Cada página tiene `<meta name="robots" content="noindex">` para que Google no indexe la vista previa. Quítela al lanzar.
- El formulario de contacto aún no envía mensajes: muestra los teléfonos. Para activarlo se puede conectar un servicio como Formspree.
- Las fuentes cargan desde Google Fonts.

## Créditos de imágenes

- Video de la plumilla: Pexels (licencia Pexels, uso comercial gratuito).
- Fotografías de Tulum y Playa del Carmen: Unsplash (licencia Unsplash, uso comercial gratuito).
- Logo y emblema: Penagos & Aké.
