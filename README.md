# Ficha APA

Curso de autogestión del aprendizaje sobre las normas APA 7.ª edición, construido con React + Vite.

Incluye 6 módulos, 31 lecciones (texto, video y cuestionarios), listas de chequeo, y progreso guardado automáticamente en el navegador del estudiante (usando `localStorage`).

## Requisitos

- [Node.js](https://nodejs.org) versión 18 o superior instalado en tu computadora.

## Cómo correrlo en tu computadora

1. Abre una terminal dentro de esta carpeta.
2. Instala las dependencias (solo la primera vez):
   ```
   npm install
   ```
3. Inicia el servidor de desarrollo:
   ```
   npm run dev
   ```
4. Abre en el navegador la dirección que aparezca en la terminal (normalmente `http://localhost:5173`).

## Cómo publicarlo en internet (gratis)

La forma más simple es con **Vercel** o **Netlify**, conectando este mismo repositorio de GitHub:

1. Sube esta carpeta a un repositorio de GitHub (ver instrucciones más abajo).
2. Entra a [vercel.com](https://vercel.com) (o [netlify.com](https://netlify.com)) e inicia sesión con tu cuenta de GitHub.
3. Elige "Add New Project" / "Import from GitHub" y selecciona el repositorio `ficha-apa`.
4. Deja la configuración automática (Vite se detecta solo) y haz clic en "Deploy".
5. En un par de minutos obtendrás un enlace público (por ejemplo, `ficha-apa.vercel.app`) que puedes compartir con tus estudiantes.

## Cómo subir esta carpeta a GitHub

Si nunca has usado Git, la forma más simple es:

1. Crea un repositorio nuevo en [github.com](https://github.com) (botón "New").
2. En tu computadora, dentro de esta carpeta, abre una terminal y ejecuta:
   ```
   git init
   git add .
   git commit -m "Primera versión de Ficha APA"
   git branch -M main
   git remote add origin https://github.com/TU-USUARIO/ficha-apa.git
   git push -u origin main
   ```
   (Reemplaza `TU-USUARIO` por tu usuario de GitHub y `ficha-apa` por el nombre real que le diste al repositorio.)

## Progreso de los estudiantes

El progreso (lecciones completadas, respuestas de las listas de chequeo, enlaces de video) se guarda en el navegador de cada estudiante mediante `localStorage`. Esto significa que:

- El progreso es individual por navegador y por dispositivo — no se sincroniza entre computadoras.
- Si el estudiante borra los datos de navegación de su navegador, perderá su progreso guardado.
- No requiere ninguna base de datos ni backend: el sitio funciona igual de bien en Vercel, Netlify, GitHub Pages, o cualquier hosting estático.

## Autora

Msc. Betty Meneses Ayllón — Universidad Privada Domingo Savio
