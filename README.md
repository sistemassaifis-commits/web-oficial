# Sitio web — SAIFIS SAS

Sitio de una sola página para SAIFIS SAS (medicina física y rehabilitación,
San Andrés, Providencia y Santa Catalina), listo para publicar en GitHub Pages.

## Estructura

```
index.html
css/styles.css
js/main.js
images/dra-sharlett.jpg
images/saifis-logo.png
```

## Cómo subirlo a GitHub Pages (paso a paso)

1. Entra a github.com y crea un repositorio nuevo (por ejemplo `saifis-web`).
   Puede ser público. No marques "Add a README" si vas a subir estos archivos.
2. En tu computador, entra a esta carpeta (`output`) y sube el contenido al
   repositorio. La forma más fácil sin usar la terminal:
   - En la página del repositorio en GitHub, haz clic en **"Add file" → "Upload files"**.
   - Arrastra **todo el contenido** de esta carpeta (el archivo `index.html`,
     y las carpetas `css`, `js`, `images`) — no la carpeta `output` en sí,
     sino lo que está adentro.
   - Haz clic en **"Commit changes"**.
3. Ve a **Settings → Pages** (en el menú lateral del repositorio).
4. En "Build and deployment", en **Source**, elige **"Deploy from a branch"**.
5. En **Branch**, elige `main` y la carpeta `/ (root)`. Guarda.
6. Espera 1–2 minutos. GitHub te mostrará la URL pública, algo como:
   `https://tu-usuario.github.io/saifis-web/`

Cada vez que subas un cambio a los archivos, el sitio se actualiza solo
(puede tardar uno o dos minutos).

## Antes de publicar, revisa esto con tu amigo

- El correo `saifis.sanandres@gmailcom` en el portafolio original parece
  tener un error de tipeo (le falta el punto). Lo corregí como
  `saifis.sanandres@gmail.com` en el sitio — confirma que ese sea el correo
  correcto antes de publicar.
- El segundo correo (`shary30@hotmail.com`) se tomó tal cual del portafolio.
- Los dos botones de WhatsApp usan los números `316 316 3834` y
  `314 543 7976`. Confirma que esos sean los números correctos de WhatsApp
  (no solo de llamada).
- El botón de contacto (header, hero y sección de contacto) ya apunta al
  formulario: `https://forms.gle/L1aUPAdturfcY8hf6`.
- La foto de la doctora se tomó del portafolio en PowerPoint; si tienes una
  foto de mejor resolución, reemplaza `images/dra-sharlett.jpg` (mismo
  nombre de archivo) para que se vea más nítida.
- El logo (`images/saifis-logo.png`) es el archivo que subiste directamente
  en el chat.

## Editar contenido

Todo el texto está directamente en `index.html`, organizado por secciones
con comentarios (`<!-- SERVICIOS -->`, etc.). Los colores y tipografía están
centralizados como variables al inicio de `css/styles.css`.
