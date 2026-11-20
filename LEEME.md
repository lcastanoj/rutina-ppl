# Rutina PPL lumbar: web app instalable

## Publicar en GitHub Pages (una vez)
1. En GitHub crea un repositorio **público** nuevo (ej. `rutina-ppl`). Marca "Add a README" para que no quede vacío.
2. Dentro del repo: **Add file → Upload files** y arrastra TODO el contenido de esta carpeta
   (`index.html`, `manifest.webmanifest`, `sw.js` y la carpeta `icons`). Commit.
3. **Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: main / (root) → Save.**
4. Espera 1–2 minutos. Tu app queda en `https://TU-USUARIO.github.io/rutina-ppl/`.

## Instalar en el iPhone
1. Abre esa URL en **Safari** (tiene que ser Safari).
2. Compartir → **Añadir a pantalla de inicio**.
3. Ábrela una vez con conexión para que quede guardada para usarla sin internet.

## Pasar tus datos de la versión de claude.ai
En la versión anterior: Datos → Exportar. En la app nueva: Datos → Importar → Reemplazar todo.

## Actualizar la app más adelante
Sube los archivos nuevos al repo y cambia `VERSION` en `sw.js` (ej. `ppl-lumbar-v2`).
Cierra y abre la app dos veces para que tome la versión nueva.
