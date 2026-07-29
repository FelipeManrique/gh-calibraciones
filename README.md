# gh-calibraciones

Dashboard de calibraciones de equipos de GH Consultora, publicado con GitHub Pages.

**Estado:** en construcción. El shell público no contiene datos de calibración — esos
solo se sirven a cuentas de Google autorizadas a través de un backend en Google Apps
Script (ver `/docs` cuando esté listo).

## Estructura

- `index.html` — shell público (sin datos sensibles).
- Próximamente: integración de "Iniciar sesión con Google" + fetch a un Web App de
  Apps Script que valida el email contra una lista autorizada antes de devolver datos.
