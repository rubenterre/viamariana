🧠 Guías de UX/UI: Vía Mariana
Este documento define las reglas de interacción, estructura y usabilidad para el desarrollo de la web bajo el certificado IFCD0110.
1. Principios de Diseño

* Claridad Informativa: La Vía Mariana es una ruta cultural/espiritual; el diseño debe ser limpio, inspirador y facilitar la lectura de trayectos.
* Consistencia: Todos los componentes (botones, tarjetas, formularios) deben compartir el mismo radio de borde, sombras y espaciados.
* Accesibilidad (A11y): Cumplir con un contraste mínimo (WCAG AA) entre --color-primary y fondos, y asegurar que todas las imágenes tengan su etiqueta alt.

2. Componentes de Interfaz (UI Kit)🔘 Botones (Buttons)

* Primario: Fondo --color-primary, texto --light, fuente --font-secondary.
* Secundario (Accent): Fondo --color-secondary, texto --dark, fuente --font-secondary.
* Comportamiento: Todos los botones deben tener un estado :hover con una transición suave (0.3s) que oscurezca ligeramente el color de fondo.
* Bordes: Radio de curvatura estándar de 8px.

🗂️ Tarjetas (Cards) - Patrimonio y Rutas

* Fondo: --light o --color-tertiary.
* Sombra: box-shadow sutil para dar profundidad sobre el fondo.
* Contenido: Imagen superior, título en --color-primary y breve descripción en --dark.

🚩 Navegación

* Sticky Header: El menú debe permanecer visible al hacer scroll.
* Active State: El enlace de la página actual debe marcarse con un subrayado o cambio de color a --color-secondary.

3. Layout y Cuadrícula (Grids)

* Contenedor Máximo: 1200px para pantallas de escritorio.
* Sistema: Uso de CSS Grid para galerías de patrimonio y Flexbox para alineaciones simples.
* Responsive Design:
* Mobile: 1 columna.
   * Tablet: 2 columnas.
   * Desktop: 3 o 4 columnas según el contenido.

4. Tono y Contenido

* Idioma: Español (España).
* Iconografía: Uso de iconos lineales y consistentes (ej. Lucide-icons o FontAwesome) que evoquen naturaleza, caminos y espiritualidad.

5. Checklist para la IA (OpenCode)
Antes de entregar un componente, verifica:

   1. ¿Utiliza las variables CSS de design-guide.md?
   2. ¿Es totalmente responsive (se adapta a móviles)?
   3. ¿El contraste de color es legible?
   4. ¿La estructura HTML es semántica (<article>, <section>, <nav>, etc.)?

------------------------------
Instrucción para el flujo de trabajo:
Este archivo debe ser consultado por OpenCode junto con los wireframes de Sketch para asegurar que la lógica de interacción coincida con el diseño visual propuesto.