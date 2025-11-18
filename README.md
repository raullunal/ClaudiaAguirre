
# Sitio de landing para Claudia Aguirre

Esta carpeta contiene una landing page lista para publicar en **GitHub Pages**.

## Contenido
- `index.html` — archivo principal (HTML + CSS inline)
- `assets/images/` — imágenes extraídas del CV (logos, íconos y elementos gráficos). Total: 24 archivos.

## Formspree
El formulario está configurado con Formspree. Para activarlo:

1. Crear una cuenta en https://formspree.io y crear un formulario -> obtendrás un `form ID`.
2. Reemplazar en `index.html` la URL del `form` por: `https://formspree.io/f/TU_FORM_ID`

Ejemplo: `<form action="https://formspree.io/f/abcdxyz" method="POST">`

## Publicar en GitHub Pages
1. Inicializar un repo en la carpeta y hacer push a GitHub.
2. En GitHub, Activar Pages desde la rama `main` o `gh-pages` y seleccionar `/ (root)` como directorio.
3. Tu sitio estará disponible en `https://<tu-usuario>.github.io/<repo>`

