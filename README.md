# Sitio web — SAIFIS SAS

Sitio de una sola página para SAIFIS SAS (medicina física y rehabilitación,
San Andrés, Providencia y Santa Catalina), ya publicado en:
https://sistemassaifis-commits.github.io/web-oficial/

## Estructura

```
index.html
css/styles.css
js/main.js
images/dra-sharlett.jpg
images/saifis-logo.png
images/favicon.ico
```

## Cómo subir cambios (recordatorio)

1. En tu repositorio en GitHub, entra a **"Add file" → "Upload files"**.
2. Arrastra los archivos que cambiaron (o todos, si prefieres reemplazar
   completo) manteniendo la misma estructura de carpetas (`css/`, `js/`,
   `images/`).
3. Haz commit. El sitio se actualiza solo en 1–2 minutos, en la misma URL.

## Datos de contacto usados en el sitio

- WhatsApp (único, en la sección de contacto): **+57 312 225 5858**
- Correos: `saifis.sanandres@gmail.com` y `shary30@hotmail.com`
  (el primero se corrigió de un error de tipeo en el portafolio original,
  que decía `gmailcom` sin el punto — confírmalo si no es el correcto)
- Botón de agendar cita / contacto (header, hero y sección de contacto):
  `https://forms.gle/L1aUPAdturfcY8hf6`
- Ubicación: Edificio Aniro, tercer piso, consultorio 301, San Andrés Islas
  — con agenda en Providencia y Santa Catalina

## Imágenes

- `images/saifis-logo.png` — el logo que subiste directamente en el chat.
- `images/dra-sharlett.jpg` — foto de la Dra. Sharlett Marie Moreno Stephens,
  tomada del portafolio en PowerPoint (resolución algo baja; si consiguen
  una mejor, reemplaza el archivo manteniendo el mismo nombre).
- `images/favicon.ico` — ícono que se muestra en la pestaña del navegador.

## Editar contenido más adelante

Todo el texto está directamente en `index.html`, organizado por secciones
con comentarios (`<!-- SERVICIOS -->`, `<!-- CONTACTO -->`, etc.). Los
colores y la tipografía están centralizados como variables al inicio de
`css/styles.css` (busca `:root`). Las animaciones y el menú móvil están en
`js/main.js`.
