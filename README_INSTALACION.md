# Agenda de Citas EPOANT — versión móvil y escritorio

Dominio previsto: https://citaorientacion.edupsic.com
Servidor Apps Script: https://script.google.com/macros/s/AKfycbxnL8P3abz8kJeKb-h9_uR4dwivoUNcTmuatvW_ubRVSUQOOVtO8PQH_LxZdCChw4A/exec

## Publicación
1. Sustituir en GitHub Pages los archivos `index.html`, `404.html`, `favicon.png` y `CNAME` en la raíz del repositorio.
2. Conservar el dominio personalizado y el DNS CNAME del subdominio apuntando al usuario GitHub Pages correcto.
3. En Apps Script sustituir `index.html` por el archivo de la carpeta `APPS_SCRIPT/` (no debe subirse este archivo al repositorio público de GitHub); guardar y crear una nueva versión de implementación web.
4. Probar en un celular y una computadora el formulario, las fechas, la selección de horario y el panel `?admin=1`.

## Compatibilidad
El sitio embebe Apps Script mediante iframe, que puede estar restringido por algunos navegadores o por las cookies de terceros. Para evitar bloqueos, aparece en ambas vistas el botón «Abrir en pantalla completa». La reserva real sigue ejecutándose dentro de Apps Script.

No se modifica `Code.gs`, la base de datos ni el PIN. No se ha probado una reserva real contra la implementación publicada.
