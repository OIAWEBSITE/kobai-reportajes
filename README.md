# Kōbai Reportajes

Página estática para el índice de reportajes de la Revista Kōbai del Centro del Japón, Universidad de los Andes.

## Publicación en GitHub Pages

1. Crear un repositorio **público** llamado `kobai-reportajes` en `oiawebsite`.
2. Subir **index.html**, **styles.css** y **script.js** en la raíz del repositorio (no dentro de una carpeta).
3. En **Settings → Pages**, seleccionar **Deploy from a branch**, rama **main**, carpeta **/(root)** y guardar.
4. Visitar `https://oiawebsite.github.io/kobai-reportajes/` cuando finalice la publicación.

## Imágenes

Las imágenes actuales son **ilustrativas** y se cargan desde Unsplash. **No son las fotografías oficiales de los reportajes**. Antes de publicación institucional, reemplazar los valores `image` de `script.js` por archivos originales autorizados guardados en una carpeta `images/`, por ejemplo: `image:'images/krudo.jpg'`.

## Edición

Los reportajes están definidos en el arreglo `articles` de `script.js`: modifica título, fecha, descripción, autor, slug e imagen allí. Todos los botones enlazan a sus reportajes originales en el sitio institucional. No es necesario npm ni instalar paquetes.

## Nota

Este proyecto es una adaptación independiente para navegación de los reportajes; los textos extensos de los artículos permanecen en el sitio institucional original.
