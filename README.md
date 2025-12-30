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
MIT License

Copyright (c) 2025 VivendasSofia

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


