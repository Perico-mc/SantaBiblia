# Guía: Cómo subir tu Landing Page a GitHub Pages

Sigue estos pasos para publicar tu página de "Santa Biblia" y que sea accesible desde internet de forma gratuita.

## Paso 1: Crear un Repositorio en GitHub

1. Inicia sesión en tu cuenta de [GitHub](https://github.com/).
2. Haz clic en el botón **"+"** en la esquina superior derecha y selecciona **"New repository"**.
3. Ponle un nombre (ejemplo: `santa-biblia-landing`).
4. Asegúrate de que sea **Public**.
5. No es necesario marcar "Add a README file" ni "Add .gitignore" por ahora.
6. Haz clic en **"Create repository"**.

## Paso 2: Subir los Archivos (Método Directo)

Si no usas Git en tu computadora, la forma más fácil es esta:

1. En la página de tu nuevo repositorio, verás un enlace que dice **"uploading an existing file"**. Haz clic ahí.
2. Arrastra y suelta los dos archivos que creamos:
   - `index.html`
   - `icon.png`
3. Espera a que se carguen.
4. En el cuadro de "Commit changes", escribe un mensaje corto como "Versión inicial de la landing page".
5. Haz clic en el botón verde **"Commit changes"**.

## Paso 3: Habilitar GitHub Pages

1. Ve a la pestaña **"Settings"** (Preferencias) de tu repositorio.
2. En el menú de la izquierda, busca la sección "Code and automation" y haz clic en **"Pages"**.
3. En la sección "Build and deployment" > "Branch", asegúrate de que esté seleccionada la rama **`main`** (o `master`) y la carpeta **`/(root)`**.
4. Haz clic en **"Save"**.

## Paso 4: ¡Listo para compartir!

1. Espera uno o dos minutos.
2. Actualiza la página de "Pages" en Settings. Verás un mensaje que dice: **"Your site is live at ..."**.
3. Haz clic en ese enlace para ver tu Landing Page publicada.

> [!TIP]
> Si alguna vez quieres actualizar la página, simplemente vuelve a subir el archivo `index.html` siguiendo el mismo proceso de "Add file" > "Upload files".
