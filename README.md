# TypeStudy — Tarjetas de tipografía

Aplicación web estática para practicar la identificación de familias tipográficas con tarjetas aleatorias. Incluye las imágenes y los nombres que se exportaron de la colección original.

## Publicar con GitHub Pages

1. Crea un repositorio nuevo en GitHub (por ejemplo, `typestudy`).
2. Sube **todo el contenido** de esta carpeta al nivel principal del repositorio: `index.html`, `fonts.json`, `images/` y `.nojekyll`.
3. En GitHub, abre **Settings → Pages**.
4. En **Build and deployment**, elige **Deploy from a branch**; selecciona `main` y la carpeta `/ (root)`, y guarda.
5. Espera a que termine la publicación. GitHub mostrará la URL pública de la web en esa misma sección.

## Editar la colección incluida

- Las tarjetas preinstaladas están descritas en `fonts.json`.
- Las imágenes correspondientes están en `images/`.
- Para añadir una tarjeta incluida para todos, copia la imagen a `images/` y añade una entrada a `fonts.json` con `name`, `note` e `image`.
- Las tarjetas que alguien añade desde la web se guardan solo en el navegador de esa persona. No se sincronizan automáticamente con el resto.

## Copia de seguridad

En la sección **Mis tipografías**, usa **Exportar colección** para guardar las tarjetas de la colección en un archivo JSON.
