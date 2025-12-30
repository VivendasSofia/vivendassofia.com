# Nombre-del-proyecto

Descripción corta
- Sitio web “En construcción” para mostrar una página temporal mientras se desarrolla el sitio principal.
- Incluye contador regresivo, formulario de suscripción (Formspree), enlaces de contacto y diseño responsive.

Estado
- Página lista para usar como `index.html`. Personalízala (logo, colores, fecha objetivo, correos y endpoint de Formspree).

Contenido del repositorio
- `index.html` — Página "En construcción" (HTML + CSS + JS).
- `README.md` — Este archivo con instrucciones y configuración.
- (Opcional) Otros archivos estáticos como `assets/` si los añades.

Cómo usar
1. Reemplaza o sube `index.html` a la raíz del hosting (por ejemplo: GitHub Pages, Netlify, Vercel, o tu servidor).
2. Configura en el archivo `index.html`:
   - Fecha objetivo: en la variable `target` dentro de la sección de scripts.
   - Correos: actualiza los enlaces `mailto:` (info y soporte).
   - Endpoint del formulario: cambia el atributo `action` por tu endpoint de Formspree o tu backend.
3. Si usas Formspree:
   - Crea un formulario en https://formspree.io y copia el endpoint (`https://formspree.io/f/xxxxxx`) en el `action`.
   - Opcional: cambiar envío a AJAX si quieres evitar recarga (hay un bloque comentado con fetch).

Personalización recomendada
- Cambia el texto del bloque `.brand` para mostrar tu logo o nombre.
- Ajusta colores en la sección `:root` del CSS.
- Si quieres una versión más simple (solo imagen y texto) dime y la genero.

Licencia
- Añade aquí la licencia que prefieras (por ejemplo MIT). Si quieres que añada un `LICENSE` lo puedo generar también.

Contacto
- Para soporte o dudas: añade tu email en la sección de contacto de `index.html` y en este README.

¿Quieres que suba también `index.html` junto con este `README.md`?
