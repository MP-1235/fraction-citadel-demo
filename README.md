# Fraction Citadel Demo

Página estática para compartir la demo del juego "Fraction Citadel" mediante GitHub Pages.

Estructura:

- `index.html` → página principal
- `assets/logo.png` → (opcional) imagen del logo que se muestra arriba
- `files/FractionCitadelDemo.zip` → (opcional) archivo .zip con la demo para descargar

Cómo añadir el logo y el .zip (desde la web):

1. Ve al repositorio: https://github.com/MP-1235/fraction-citadel-demo
2. Haz clic en "Add file" → "Upload files".
3. Para el logo: arrastra el archivo de imagen y nómbralo `assets/logo.png` (si la carpeta no existe, GitHub la creará automáticamente).
4. Para el .zip: arrastra el archivo y nómbralo `files/FractionCitadelDemo.zip`.
5. Escribe un mensaje de commit y pulsa "Commit changes".

Activar GitHub Pages:

1. En el repo, ve a Settings → Pages.
2. En "Source" selecciona la rama `main` y carpeta `/ (root)`.
3. Pulsa "Save". La URL típica será:

   `https://mp-1235.github.io/fraction-citadel-demo/`

Nota sobre visibilidad y permanencia:
- El repositorio ya es público para que puedas usar la URL en un QR sin necesidad de iniciar sesión.
- GitHub Pages puede tardar unos segundos en desplegar la página y tus archivos.

Si prefieres, puedes subir los archivos usando Git desde tu máquina:

```bash
git clone https://github.com/MP-1235/fraction-citadel-demo.git
cd fraction-citadel-demo
mkdir -p assets files
# copiar tus archivos a assets/logo.png y files/FractionCitadelDemo.zip
git add assets/logo.png files/FractionCitadelDemo.zip
git commit -m "Añadir logo y zip del demo"
git push origin main
```
