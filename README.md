# 🧹 Rotación de limpieza de la casa

Página de un solo archivo (`index.html`) con la rotación de limpieza de Astrid, Jimmy y Sole.
No necesita servidor ni instalar nada: se puede abrir directamente en el navegador.

## Publicarla gratis en GitHub Pages

1. Crea una cuenta en [github.com](https://github.com) si no tienes una.
2. Arriba a la derecha, toca **+ → New repository**.
   - Nombre: por ejemplo `limpieza-casa`.
   - Visibilidad: **Public** (GitHub Pages gratis requiere repositorio público).
   - Toca **Create repository**.
3. En el repositorio nuevo, toca **uploading an existing file** (o **Add file → Upload files**),
   arrastra `index.html` (y este `README.md` si quieres) y toca **Commit changes**.
4. Ve a **Settings → Pages**.
   - En **Source** elige **Deploy from a branch**.
   - En **Branch** elige `main` y la carpeta `/ (root)`. Toca **Save**.
5. Espera 1–2 minutos y recarga la página de Settings → Pages. Aparecerá el enlace:
   `https://TU-USUARIO.github.io/limpieza-casa/`
6. Comparte ese enlace con la casa. En el celular, desde el menú del navegador, usa
   **“Agregar a pantalla de inicio”** para tenerla como si fuera una app.

Para actualizarla después, sube de nuevo `index.html` (reemplaza el anterior); los cambios
aparecen en uno o dos minutos.

## Cambios rápidos

Todo lo editable está al inicio del `<script>` en `index.html`:

- `FECHA_INICIO`: el lunes en que empieza la Semana 1 (formato `AAAA-MM-DD`).
- `PERSONAS`, `BLOQUES`: nombres, tareas, íconos y minutos.
- `BASURA_DIAS_ASTRID_IMPAR` y `ASPIRADO`: días de basura y de aspirado.

## Bueno saber

- La semana actual se calcula con la hora de Lima (America/Lima), de lunes a domingo.
- Los checks se guardan **solo en el celular o navegador de cada persona** (no se comparten).
- Se puede enlazar una semana concreta añadiendo `#semana-5` al final de la dirección.
