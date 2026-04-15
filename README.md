# servicios
Sitio web de presentación para AGNEXUS Networks.

## Deploy en GitHub Pages

- El contenido está en la raíz del repositorio.
- El archivo `CNAME` define el dominio personalizado `www.agnexusuio.com`.
- Se usa GitHub Actions en `.github/workflows/pages.yml`.
- El archivo `.nojekyll` evita procesamiento por Jekyll.

## Cómo publicar

1. Empuja los cambios a la rama `main`.
2. En `Settings > Pages`, selecciona `GitHub Actions` como fuente de publicación si no está configurado automáticamente.
3. Verifica que el dominio personalizado tenga certificado HTTPS activo.
