# Cuaderno de trabajo con IA — Diseña tu futuro

> Completa este registro con los prompts que realmente utilices en Codex/ChatGPT. La rúbrica valora seis o más prompts documentados, las mejoras realizadas y la detección razonada de un error. No afirmes que has ejecutado un prompt si no lo has hecho.

## Registro de prompts

### 1. Estructura inicial
**Prompt:** «Crea la estructura de un sitio de cuatro páginas sobre el Grado en Ingeniería en Diseño Industrial y Desarrollo de Productos de la UPV: index.html, estudios.html, centro.html y salidas.html. Usa HTML5 semántico y un menú común con enlaces relativos. No inventes datos; deja las fuentes indicadas».

**Qué revisaré:** que estén los cuatro archivos, que `header`, `nav`, `main` y `footer` estén bien usados y que todos los enlaces funcionen.

### 2. Identidad visual
**Prompt:** «Diseña un style.css profesional con estética de estudio de diseño industrial: fondo azul noche, acentos cian, tipografía legible, jerarquía clara, tarjetas y espacios amplios. Usa como máximo dos familias tipográficas y una paleta coherente».

**Qué revisaré:** contraste, legibilidad, consistencia y que todos los estilos estén en el CSS externo.

### 3. Diseño adaptable
**Prompt:** «Adapta las cuatro páginas a móvil y tablet con CSS responsive. El menú debe poder abrirse y cerrarse en móvil, los elementos no deben desbordarse y la tabla debe poder desplazarse horizontalmente si hace falta».

**Qué revisaré:** anchura a 360 px, navegación, tabla y tamaño de texto.

### 4. Plan de estudios
**Prompt:** «Usa el PDF oficial del plan de estudios 2026/2027 del campus de València. Resume solo los datos verificables. Distingue los créditos optativos de la intensificación y no mezcles el campus de Alcoy con el de València».

**Qué revisaré:** que los créditos y las asignaturas coincidan con el PDF y que las descripciones se identifiquen como resúmenes.

### 5. Nota de corte y acceso
**Prompt:** «Comprueba en la ficha oficial de la UPV la nota de corte y el número de plazas para el grado en el campus de València en 2026/2027. Explica que la nota de corte cambia cada curso y enlaza la página oficial de acceso».

**Qué revisaré:** curso académico, campus y enlace a la explicación de la nota de corte.

### 6. Accesibilidad y control final
**Prompt:** «Audita las cuatro páginas: textos alternativos, etiquetas semánticas, enlaces, viewport, contraste, navegación por teclado y rutas relativas. Devuelve una lista de problemas concretos y corrige solo los que se confirmen».

**Qué revisaré:** errores reales en navegador y no solo lo que diga la IA.

## Reflexión: error o riesgo detectado y corrección

**Riesgo detectado:** la ficha general de la titulación resume la optatividad como 48 ECTS, mientras que el plan específico del campus de València desglosa esa parte en 30 ECTS optativos y 18 ECTS de intensificación.

**Corrección aplicada en el proyecto:** se explica la diferencia en `estudios.html` y se enlaza el PDF del campus de València. Así se evita presentar ambas cifras como si fueran incompatibles o mezclar planes de campus distintos.

**Mi comprobación personal (rellenar después de probar):**
- Página o elemento que comprobé:
- Qué problema encontré:
- Cómo lo solucioné:
- Qué aprendí sobre el código:

## Qué he aprendido (rellenar con tus palabras)

Explica qué hacen `header`, `nav`, `main` y `footer`; cómo se enlaza el CSS; para qué sirve `alt`; qué hace una ruta relativa; y por qué hay que revisar un cambio de IA antes de publicarlo.
