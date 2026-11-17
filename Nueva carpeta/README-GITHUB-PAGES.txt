CONTROL DE STOCK: DEPOSITO & LOCAL

Publicacion en GitHub Pages

1. Crea un repositorio nuevo en GitHub.
2. Sube al directorio raiz del repositorio estos archivos:
   index.html, styles.css, app.js, storageService.js, manifest.json, sw.js e icon.svg.
3. En GitHub abre Settings > Pages.
4. En Build and deployment selecciona Deploy from a branch, elige la rama main y la carpeta /(root), y guarda.
5. Abre la URL que GitHub Pages muestra. La primera publicacion puede tardar unos minutos.

Tambien puedes extraer todos los archivos de este ZIP directamente en la raiz del repositorio.

La aplicacion guarda los datos en localStorage del navegador. Cada telefono o PC tiene sus propios datos; esta version no sincroniza dispositivos. Exporta un respaldo JSON antes de cambiar o borrar los datos del navegador.

GitHub Pages usa HTTPS, requerido por el service worker para habilitar el funcionamiento sin conexion.
