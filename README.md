# Mythos & Aitiologia: El Sistema Graves de Mitología Griega

Aplicación educativa en español, entregada como un único archivo HTML. Se puede abrir `index.html` directamente en el navegador; no requiere instalación ni servidor. Tailwind CSS y Google Fonts son mejoras opcionales desde CDN, con estilos y tipografías de respaldo integrados.

## Publicación en GitHub Pages

El flujo [`pages.yml`](.github/workflows/pages.yml) valida y prepara el sitio en cada pull request hacia `main`, y lo publica automáticamente al integrar cambios en `main`. También se puede iniciar desde **Actions → Deploy Mythos & Aitiologia to GitHub Pages → Run workflow**, seleccionando la rama `main`.

**Configuración inicial de Pages:** en el repositorio, abre **Settings → Pages → Build and deployment** y selecciona **GitHub Actions** como fuente. Tras integrar el PR y completar el flujo, GitHub mostrará la URL publicada en **Settings → Pages** y en el resumen del despliegue. La dirección esperada de este repositorio es:

<https://jaimediazchabur.github.io/Contraprestacion/>

El artefacto de Pages incluye solo `index.html` y `.nojekyll`; no se suben los PDF de referencia ni otros archivos del repositorio.
