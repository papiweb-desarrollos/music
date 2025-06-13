Repositorio para archivos estáticos accesibles vía CDN usando jsDelivr en Papiweb.

Uso como CDN
Puedes servir cualquier archivo de este repositorio usando jsDelivr. La estructura de la URL es:

Code
https://cdn.jsdelivr.net/gh/papiweb-desarrollos/music@<versión>/<ruta-al-archivo>
Reemplaza <versión> por una rama (por ejemplo, main), tag o commit.
Reemplaza <ruta-al-archivo> por la ruta relativa del archivo en el repositorio.
Ejemplo
Archivo: audio/theme.mp3 en la rama main:

Code
https://cdn.jsdelivr.net/gh/papiweb-desarrollos/music@main/audio/theme.mp3
O para la última versión de la rama principal:

Code
https://cdn.jsdelivr.net/gh/papiweb-desarrollos/music/audio/theme.mp3
Usar en HTML
HTML
<audio controls>
  <source src="https://cdn.jsdelivr.net/gh/papiweb-desarrollos/music/audio/theme.mp3" type="audio/mpeg">
  Tu navegador no soporta la etiqueta de audio.
</audio>
Recursos
Documentación de jsDelivr
Repositorio en GitHub

