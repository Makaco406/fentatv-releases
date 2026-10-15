# FentaTV · descargas

Aquí se publica el APK de **FentaTV** para Android móvil, Google TV, Android TV y Fire TV. Aquí no hay código: solo el instalador de cada versión.

FentaTV no aloja contenido propio: conecta con servicios de terceros y se usa bajo la responsabilidad de cada persona.

## Instalar en la tele con Downloader

1. Instala la app **Downloader** (Fire TV: tienda de Amazon; Google TV y Android TV: Play Store).
2. Ábrela y, cuando te lo pida, permite **«instalar apps desconocidas»** para Downloader.
3. En el recuadro de la dirección escribe exactamente:

   `https://github.com/Makaco406/fentatv-releases/releases/latest/download/FentaTV.apk`

4. Pulsa **Ir**, espera a que termine la descarga y elige **Instalar**.

Esa dirección siempre lleva a la última versión: no hay que cambiarla cuando salga una nueva.

## Instalar en el móvil

Abre la última versión en [Releases](../../releases/latest), descarga `FentaTV.apk` y ábrelo. Android te pedirá permiso para instalar apps desde tu navegador o gestor de archivos.

## Primer arranque

1. Elige **Móvil** o **TV / Android TV** y acepta el aviso.
2. Pide tu clave gratuita de TMDB en `themoviedb.org/settings/api` y escríbela en la pantalla «Claves de API». En la tele es más cómodo teclearla con la app de mando del móvil (Google TV o Fire TV).
3. La clave de OMDb es opcional.

## Actualizar

Instala el APK nuevo encima del anterior (con Downloader, la misma dirección de arriba). No hace falta desinstalar ni se pierden los datos.

## Comprobar que el archivo es el original

Cada versión indica su huella **SHA-256** en las notas. En Windows: `Get-FileHash FentaTV.apk -Algorithm SHA256`.
