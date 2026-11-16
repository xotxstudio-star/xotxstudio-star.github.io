# Mikel Artola | Piloto de rallyes 2026

Web estática (HTML, CSS y JavaScript sin dependencias).

## Estructura
- `index.html`: contenido y SEO básico
- `css/styles.css`: estilos
- `js/main.js`: pantalla de carga, parallax, animaciones, contadores y menú. Al principio del archivo está el objeto `IMAGES` con la ruta de cada foto
- `img/`: fotografías

## Cambiar o añadir fotos
Pon la imagen en `img/` y escribe su ruta en `IMAGES` (`js/main.js`). Los huecos de 2023 (`c2023`) y 2026 (`c2026`) están vacíos y ocultos hasta que tengan foto.

## Publicar en GitHub Pages
1. Sube todo el contenido de esta carpeta a la raíz del repositorio.
2. En el repositorio: Settings, Pages, Source: Deploy from a branch, rama `main`, carpeta `/ (root)`.
3. La web quedará en `https://TU-USUARIO.github.io/NOMBRE-REPO/`.
