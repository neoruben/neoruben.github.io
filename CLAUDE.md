# neoruben.github.io — notas para Claude

Web estática (un solo `index.html`, sin compilación) publicada con GitHub Pages en https://neoruben.github.io
desde la rama `main`. Cada push se publica solo en un minuto.

- Muestra los repos **públicos** de neoruben (igual que la tabla del perfil `neoruben/neoruben`). Si un repo pasa a
  privado, quitar su tarjeta; si se publica uno nuevo, añadirla.
- Las imágenes están **copiadas** en `img/` como WebP (no enlazar a raw.githubusercontent: a veces no carga y su
  caché sirve versiones viejas). Si cambia una captura en un repo, regenerarla aquí. Las capturas de MercaStats y
  LidlStats llevan difuminados gasto total, ticket medio, tiendas y productos: no usar versiones sin difuminar.
- Textos en español e inglés con `data-es` / `data-en` y botón ES/EN. Tema claro/oscuro por tokens en `:root`.
- Probar en local: `python -m http.server 8765` en esta carpeta y abrir http://localhost:8765 (abrir el archivo
  directamente con `file://` en el panel no carga las imágenes).
