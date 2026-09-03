Eres un experto en desarrollo de aplicaciones web con dominio en HTML, CSS y JavaScript.

Crea una aplicación PWA (Progressive Web App) con los siguientes requisitos:

### Nombre de la Aplicación

Tras las Pistas del Proceso Gráfico

### Propósito / Función Principal

## 2. Propósito / Función Principal

Transformar la actividad de aprendizaje en una **"Investigación al estilo Sherlock Holmes"**, utilizando los acertijos del libro *El gran libro de acertijos de Sherlock Holmes* como recurso narrativo y metodológico para desarrollar en el estudiante la **observación, formulación de preguntas, identificación de pistas, razonamiento lógico, deducción y toma de decisiones** aplicadas al proceso de diseño, impresión y publicación.

La actividad se organiza como una investigación progresiva en la que el estudiante debe resolver diferentes "casos" para reconstruir un proceso de producción gráfica. Cada acertijo representa una habilidad cognitiva necesaria para avanzar hacia la siguiente fase del proceso.

### Caso 1. La primera deducción → Identificación y relación de pistas

**Acertijo utilizado:** *La primera deducción*.

El acertijo plantea la necesidad de relacionar nombres, características y casos para descubrir correspondencias.

**Adaptación a la actividad:**

El estudiante recibe tres pistas relacionadas con un proyecto gráfico:

* características del recurso;
* formato del archivo;
* medio o canal donde será utilizado.

Debe relacionar las pistas y determinar a qué fase del proceso corresponde cada una:

**DISEÑO → IMPRESIÓN → PUBLICACIÓN**

**Interacción HTML:**

* Mostrar las pistas como tarjetas.
* El estudiante arrastra cada pista hacia la fase correspondiente.
* Puede modificar sus respuestas antes de confirmar.
* Debe incluir además pistas falsas (distractoras) que el estudiante deba descartar, y un botón de apoyo "Pedir una pista al docente" que abra una pregunta guía sin revelar la respuesta.

**Feedback:**

**Respuesta correcta:**

> "¡Excelente, detective! Has relacionado correctamente las pistas. Esta evidencia permite identificar la fase correspondiente del proceso."

**Respuesta incorrecta:**

> "La deducción todavía no es correcta. Observa nuevamente la pista y pregúntate: ¿qué ocurre con este recurso durante el proceso?"

---

### Caso 2. Un problema iluminador → Deducción del formato

**Acertijo utilizado:** *Un problema iluminador*.

En el acertijo, Holmes debe identificar qué interruptor corresponde a una habitación que no puede observar directamente y plantea un método que permite resolver el problema mediante una sola visita.

**Adaptación a la actividad:**

El estudiante recibe diferentes características técnicas sin que se le indique directamente el formato.

Por ejemplo:

> "Este recurso debe conservar sus formas cuando cambia de tamaño y será utilizado para producir una pieza impresa."

**Pregunta del caso:**

> ¿Qué formato se deduce a partir de las pistas?

Opciones:

* Vectorial
* Ráster
* Video

**Interacción HTML:**

El estudiante selecciona el formato y posteriormente debe justificar su elección. Debe contar también con un botón de apoyo "Pedir una pista al docente".

**Feedback:**

> "¡Caso resuelto! La pista principal era la posibilidad de modificar el tamaño sin perder la definición. Has utilizado la evidencia para deducir la respuesta."

Si responde incorrectamente:

> "Observa nuevamente la evidencia. ¿Qué característica diferencia a un gráfico vectorial de una imagen ráster?"

---

### Caso 3. El engaño del dominó → Reconstrucción del proceso

**Acertijo utilizado:** *El engaño del dominó*.

Holmes deduce los números que aparecen en los extremos de una cadena de dominós sin observar directamente la disposición realizada por los niños. El desafío se basa en analizar las relaciones entre los elementos disponibles.

**Adaptación a la actividad:**

Los estudiantes reciben elementos desordenados:

**Diseño / archivo vectorial / imagen ráster / impresión / video / publicación digital**

Deben reconstruir la secuencia lógica del proceso.

**Interacción HTML:**

Arrastrar y ordenar los elementos:

**DISEÑO → IMPRESIÓN → PUBLICACIÓN**

Después deberán relacionar cada formato con la fase en la que puede intervenir. Debe contar también con un botón de apoyo "Pedir una pista al docente".

**Feedback correcto:**

> "¡Muy bien! Has reconstruido la cadena del proceso. Al igual que Holmes, utilizaste las relaciones entre los elementos para descubrir el orden."

**Feedback incorrecto:**

> "La cadena presenta una inconsistencia. Analiza qué sucede primero: ¿se produce el diseño, se imprime el producto o se publica el contenido?"

---

### Caso 4. Una historia probable → Detectar el error

**Acertijo utilizado:** *Una historia probable*.

En este caso, Holmes detecta que una persona está mintiendo a partir de una contradicción relacionada con la ubicación de una nota dentro de un libro.

**Adaptación a la actividad:**

Presentar al estudiante una situación de producción gráfica con información aparentemente correcta, pero que contiene un error.

Ejemplo:

> "El diseñador prepara una fotografía ráster para imprimirla en gran formato. Para evitar pérdida de calidad, aumenta el tamaño de la imagen varias veces sin modificar su resolución."

**Pregunta:**

> ¿Qué evidencia permite detectar el problema?

El estudiante debe identificar la contradicción técnica. Se recomienda apoyar la pregunta con un simulador interactivo (por ejemplo, un control que amplíe una imagen de muestra y muestre en tiempo real la pérdida de definición) y con un botón de apoyo "Pedir una pista al docente".

**Feedback:**

> "¡Has encontrado la inconsistencia! El problema no está en la intención del diseñador, sino en la relación entre resolución, dimensiones y destino del archivo."

Este caso permite pasar de **identificar información** a **evaluar críticamente una decisión**.

---

### Caso 5. Un mensaje codificado → Interpretación para publicación digital

**Acertijo utilizado:** *Un mensaje codificado*.

El libro presenta un mensaje cuyos espacios, saltos de línea y orientación han sido alterados, obligando al lector a reorganizar la información para descubrir su significado.

**Adaptación a la actividad:**

Presentar información técnica de una publicación digital de manera desordenada.

El estudiante debe reorganizarla para identificar:

* formato;
* canal;
* características del recurso;
* especificaciones de publicación.

Por ejemplo:

**VIDEO — REDES SOCIALES — FORMATO DIGITAL — PUBLICACIÓN**

El estudiante debe reconstruir el mensaje y determinar la relación entre los elementos. Se recomienda añadir, como refuerzo léxico, un anagrama del término clave de la fase (por ejemplo, las letras de "PUBLICACIÓN" desordenadas), con su propio botón de apoyo "Pedir una pista al docente".

**Feedback:**

> "¡Mensaje descifrado! Has reorganizado correctamente las pistas y determinado que el recurso pertenece a la fase de publicación digital."

---

## Caso final. El expediente Sherlock Holmes → Integración

Después de resolver los cinco casos, el estudiante recibe el **expediente final del caso**.

Debe completar un esquema general:

**PISTAS → ANÁLISIS → DEDUCCIÓN → DECISIÓN → FASE DEL PROCESO**

y construir el proceso:

**DISEÑO → IMPRESIÓN → PUBLICACIÓN**

Relacionando:

* **Vectorial**
* **Ráster**
* **Video**

con el canal y la fase correspondiente.

Al cerrar el expediente, el estudiante debe poder **entregar el documento con sus respuestas** mediante dos vías:

* Un botón **"Imprimir / guardar como PDF"**, que abra el diálogo de impresión del navegador mostrando únicamente el expediente (sin navegación, botones ni controles de la actividad).
* Un botón **"Descargar expediente (.md)"**, que genere y descargue un archivo Markdown con todas las respuestas registradas por el equipo: datos del equipo, estado de cada caso, pistas clasificadas, formato elegido y su justificación, secuencia y matriz del proceso, evidencia seleccionada en el caso 4, mensaje descifrado y término del anagrama del caso 5, y las reflexiones y autoevaluación del cierre.

### Producto final del estudiante

El estudiante deberá:

1. Formular preguntas sobre el problema.
2. Identificar las pistas relevantes.
3. Comparar sus deducciones con las de un compañero.
4. Clasificar los formatos.
5. Relacionarlos con las fases del proceso.
6. Detectar posibles errores.
7. Reconstruir el flujo completo.
8. Justificar sus decisiones.

### Estructura de interacción del HTML

La experiencia deberá mantener una secuencia constante:

**INSTRUCCIÓN**
↓
**PISTA / ACERTIJO**
↓
**APOYO DISPONIBLE (pista del docente, a solicitud del estudiante)**
↓
**INTERACCIÓN DEL ESTUDIANTE**
↓
**RESPUESTA**
↓
**FEEDBACK INMEDIATO**
↓
**DEDUCCIÓN**
↓
**FASE DEL PROCESO**
↓
**SIGUIENTE CASO**

De esta manera, cada acertijo tiene una **función pedagógica concreta** y contribuye a completar progresivamente el expediente final. El libro no se utiliza para entretener al estudiante, sino como **metáfora de investigación y estrategia de razonamiento** para comprender y reconstruir el proceso de diseño, impresión y publicación.

### Público Objetivo

Estudiantes de segundo semestre

### Funcionalidades Deseadas

La actividad que vienes trabajando puede convertirse en una especie de **"Caso Sherlock Holmes: descubre el proceso de producción gráfica"**.

| Método de Holmes          | Adaptación a la actividad                                                                         |
| ------------------------- | ------------------------------------------------------------------------------------------------- |
| **Presentar un misterio** | Presentar un problema de diseño sin indicar directamente la solución.                             |
| **Observar pistas**       | Los estudiantes identifican información sobre formato, soporte, canal y características técnicas. |
| **Formular preguntas**    | Elaboran tres preguntas para descubrir qué está ocurriendo.                                       |
| **Relacionar evidencias** | Comparan sus preguntas con las de un compañero y relacionan las pistas.                           |
| **Deducir**               | Determinan si la evidencia corresponde a diseño, impresión o publicación.                         |
| **Comprobar**             | Verifican si el formato elegido es adecuado para el canal.                                        |
| **Recibir una pista**     | El docente proporciona preguntas guía cuando el estudiante queda bloqueado, mediante un botón de apoyo disponible en cada pregunta. |
| **Resolver el caso**      | Completan el flujo: **diseño → impresión → publicación**.                                         |
| **Explicar la solución**  | Justifican por qué asignaron cada formato a determinada fase.                                     |

### Ejemplo concreto

Podrías plantearlo así:

**Caso: El archivo desaparecido**

> Holmes recibe tres pistas relacionadas con un proyecto gráfico:
>
> **Pista 1:** El archivo debe conservar sus formas y líneas sin perder calidad al modificar su tamaño.
> **Pista 2:** El archivo será enviado a una imprenta para producir una pieza física.
> **Pista 3:** Otro recurso contiene movimiento y será publicado en redes sociales.
>
> **Pregunta del detective:** ¿Qué tipo de archivo corresponde a cada situación y en qué fase del proceso se utilizará?

El estudiante debe **deducir**, no simplemente memorizar:

* **Vectorial → diseño / impresión**
* **Ráster → imágenes utilizadas en diseño o publicación**
* **Video → publicación digital**

Aquí se aprovecha directamente la lógica del libro: el estudiante recibe información parcial y debe encontrar la relación entre las pistas. Por ejemplo, en *La primera deducción*, Holmes relaciona nombres, casos y características para reconstruir una correspondencia; en *Un problema iluminador*, debe determinar qué interruptor corresponde a una habitación utilizando un procedimiento lógico.

### Lo más importante: convertirlo en una secuencia didáctica

Yo estructuraría tu actividad así:

**1. MISTERIO**
↓
Se presenta un caso de producción gráfica con información incompleta.

**2. PISTAS**
↓
El estudiante identifica características del proyecto: soporte, canal, formato, resolución, movimiento, escalabilidad, etc.

**3. PREGUNTAS DEL DETECTIVE**
↓
Formula tres preguntas para resolver el caso.

**4. INVESTIGACIÓN EN PAREJA**
↓
Compara sus preguntas con las de un compañero.

**5. MATRIZ DE DEDUCCIÓN**
↓

| Pista                       | ¿Qué indica?               | Formato   | Fase               |
| --------------------------- | -------------------------- | --------- | ------------------ |
| Mantiene calidad al escalar | Gráfico basado en vectores | Vectorial | Diseño/impresión   |
| Imagen fotográfica          | Píxeles                    | Ráster    | Diseño/publicación |
| Contiene movimiento         | Recurso audiovisual        | Video     | Publicación        |

**6. PISTA DEL DOCENTE**
Si no pueden resolverlo, un botón de apoyo visible en cada caso debe ofrecer preguntas guía como:

> "¿Qué formato pediría la imprenta?"
> "¿Qué características necesita un recurso para redes sociales?"
> "¿Qué formato puede escalarse sin perder calidad?"

Esto coincide muy bien con la lógica del libro, donde algunos títulos funcionan como pistas y se recomienda reconsiderar el significado del título cuando el estudiante queda atascado.

**7. RESOLUCIÓN DEL CASO**
↓
El estudiante completa:

**DISEÑO → IMPRESIÓN → PUBLICACIÓN**

y vincula cada fase con los formatos correspondientes.

**8. FEEDBACK**
↓
Se muestra inmediatamente si la deducción es correcta y **por qué**. Esta retroalimentación debe estar presente de forma constante, después de cada interacción, y no solo al final de la actividad.

### Una adaptación todavía más potente

En lugar de decirle al estudiante:

> "Clasifica los formatos vectorial, ráster y video."

podríamos convertirlo en:

> **"Sherlock Holmes necesita identificar qué archivos debe utilizar para resolver un proyecto que pasa por tres etapas: diseño, impresión y publicación. Tiene varias pistas, pero algunas están mezcladas. ¿Puedes reconstruir el proceso?"**

Así, el acertijo **deja de ser una actividad aislada** y se convierte en el **recurso narrativo que conduce al estudiante por toda la fase del proceso**.

Esto además encaja con la estructura que veníamos definiendo:

**Instrucción → pistas → interacción → deducción → respuesta → feedback → fase del proceso.**

Y podemos incluso tomar **acertijos específicos del libro** —por ejemplo *La primera deducción*, *Un problema iluminador*, *El engaño del dominó*, *Una historia probable* o *Un mensaje codificado*— y transformarlos uno por uno en **actividades interactivas HTML relacionadas con diseño, impresión y publicación**, manteniendo la lógica original de cada acertijo. El libro contiene, por ejemplo, problemas de deducción, códigos, lógica y relaciones entre elementos.

Si quieres, puedo hacer el siguiente paso: **tomar la actividad de aprendizaje completa que estás desarrollando y convertirla en una "Investigación al estilo Sherlock Holmes", indicando exactamente qué acertijo del libro usar en cada momento, qué debe hacer el estudiante y qué feedback debe mostrar el HTML.**

### Diseño y Estilo Visual

Impresionismo & Romanticismo

La luz como protagonista: pinceladas de colores puros que el ojo mezcla a distancia, siguiendo la teoría del contraste simultáneo de Chevreul. El Romanticismo aporta lo sublime: la emoción desbordando a la razón. Entorno visual

Fondos degradados como cielos de Monet: lavandas, celestes y melocotón en transición suave, con acentos complementarios (naranja sobre azul) que vibran sin romper la armonía. Bordes difusos, sombras suaves, movimiento lento tipo bruma; nada de aristas duras. Tipografía

Playfair Display italic

Familias orgánicas y fluidas, con remates suaves y cursivas caligráficas: Playfair Display para titulares emotivos y Lora para lectura, cuya modulación a pincel acompaña la pincelada.

### Interacción y Comportamiento

La interacción debe reforzar la ambientación de misterio e investigación al estilo Sherlock Holmes, haciendo que cada acción del estudiante permita descubrir nuevas evidencias y avanzar en la resolución del caso.

Misterio y descubrimiento: presentar la información de manera progresiva, evitando mostrar todas las respuestas desde el inicio.

Respuestas emergentes: utilizar ventanas pop-up para mostrar pistas, explicaciones, deducciones y resultados después de cada interacción.

Transparencias fantasmales: incorporar siluetas, documentos, huellas, objetos o personajes semitransparentes que aparezcan progresivamente como elementos del misterio.

Falsas pistas: incluir algunas pistas distractoras que obliguen al estudiante a analizar la información y distinguir entre evidencia relevante e irrelevante.

Presentación de sospechosos: introducir personajes o elementos como "sospechosos", asociados a diferentes formatos, procesos o decisiones, para que el estudiante determine cuál corresponde a la evidencia encontrada.

Retroalimentación positiva constante: después de cada respuesta, proporcionar una retroalimentación inmediata que reconozca el avance del estudiante, incluso cuando la respuesta sea incorrecta. Esta retroalimentación debe estar presente en todas las preguntas de la actividad, sin excepción.

Apoyos y ayudas en cada pregunta: cada caso debe incluir un botón de ayuda ("Pedir una pista al docente") visible junto a su interacción principal. Al activarse, debe abrir una ventana emergente con una pregunta guía que oriente el razonamiento del estudiante sin revelar la respuesta correcta, disponible en todo momento y las veces que el estudiante lo necesite.

Panel de glosario: la actividad debe incluir un panel de glosario, accesible en todo momento desde cualquier caso (por ejemplo, mediante un botón flotante o un acceso fijo en la interfaz), con las definiciones breves de los términos técnicos utilizados en la investigación (diseño, impresión, publicación, vectorial, ráster, video, resolución, sangrado, y demás vocabulario propio del proceso gráfico).

Progresión del caso: cada respuesta correcta debe desbloquear una nueva pista o etapa del proceso: Pista → Análisis → Deducción → Decisión → Fase del proceso.

Cierre del misterio: al completar todas las deducciones, el estudiante debe reconstruir el proceso completo Diseño → Impresión → Publicación y resolver el caso final.

### Tecnologías y Estructura

1. Holographic card

Holographic card

Loading interactive CodePen...

Open on CodePen

As they say, you can't beat the classics. So, we're starting with a simple card effect where it scales up, gets a colorful border shadow, and shimmers with a holographic gradient on hover. This animation works with:

::before pseudo-element: Creates the holographic effect by placing a gradient background with varying opacity and rotation. It initially has 0 opacity, and on hover, it becomes visible while moving downwards

.holographic-card:hover: Applies a scale effect (transform: scale(1.05)) and a glowing box shadow (box-shadow: 0 0 20px rgba(0, 255, 255, 0.5))

2. Liquid morph

Liquid morph

Loading interactive CodePen...

Open on CodePen

This animation creates a liquid-like morphing effect on a button when hovered over. Initially, the button has a rounded rectangular shape with a dark blue background and a centered text label. When hovered, the button slightly rotates, its border-radius decreases, and a colorful, conic gradient appears. The CSS features powering this animation include:

::before pseudo-element: Creates a conic gradient background, which transitions from cyan to dark blue, giving the appearance of a liquid filling the button

.liquid-morph-element:hover: Reduces the border-radius to 10px and applies a rotation of 15deg, giving the button a more angular shape

3. Explosive text effect

Particle deconstruction

Loading interactive CodePen...

Open on CodePen

This animation creates an "explosive" effect when the element is hovered over. It works with the ::before and ::after pseudo-elements, which produces the radial gradient effect and scale up and rotate on hover.

4. Text underline

Text hover underline

Loading interactive CodePen...

Open on CodePen

This animation creates a unique hover effect where underlines appear above and below the text when the user hovers over it. Its powered by the ::before and ::after pseudo-elements, which create the underline effect. The pseudo-elements grow from 0 to 100% on hover while a gradient is applied to them.

5. Dropdown menu

Dropdown menu

Loading interactive CodePen...

Open on CodePen

This animation creates a dropdown menu that appears when hovering over a button. Initially, the dropdown menu is hidden, with its opacity set to 0, but becomes fully visible on hover. The key to this animation is the opacity, which is set to 1 on hover and transform: translateY(0), which moves the menu to its normal position.

6. Double-sided card

Double-sided card

Loading interactive CodePen...

Open on CodePen

This animation creates a 3D flipping card effect. When the user hovers over the card, it rotates 180 degrees along the Y-axis, revealing the back side. The front and back sides of the card are identical in size but have different backgrounds and the perspective property on the cards' container enhances the 3D effect.

This animation works with:

transform-style: preserve-3d: Allows the cards to maintain their 3D position during rotation

transform: rotateY(180deg): Rotates the cards along the Y-axis

7. 4-corner image

4-corner image

Loading interactive CodePen...

Open on CodePen

This animation creates an interactive image effect where the image is divided into four quadrants on hover. The quadrants represent a different section of an image, and they are positioned to create a complete picture when assembled. Upon hovering over the container, the quadrants shift outward, creating the split effect.

It works with:

background-image: url() applies the image to each quadrant

background-position crops specific quadrants of the image

transform: translate() moves quadrants outwards on hover

8. Cursor animations

Cursor animations 1

Loading interactive CodePen...

Open on CodePen

This animation has two effects. First, it demonstrates various CSS cursor styles on hover, and each box undergoes different visual effects, like scaling, rotating, clipping, and pulsing. Here's a breakdown of what powers the effects in this:

cursor: Defines unique cursor types for the different boxes

::before: Creates a linear gradient effect that moves diagonally from top-left to bottom-right on hover

@keyframes pulse: Creates a pulsating effect where the box grows and shrinks in size repeatedly

@keyframes shake: Simulates a shaking or jittery motion, like the kind used to signify "error" or "not allowed"

@keyframes moveAround: Causes the boxes to shift slightly in various directions

CSS transforms: transform: scale(), rotate(), translateY(), translateX(), and skew() are applied to various boxes

9. Rotating cube

Rotating cube

Loading interactive CodePen...

Open on CodePen

This 3D animation creates an interactive cube with six faces (front, back, right, left, top, and bottom), each styled with distinct colors and a subtle gradient. The cube rotates smoothly in 3D space when hovered over, and a glass-like gradient appears on the faces. It works with:

translateZ, rotateX, and rotateY: Position the faces to form a cube

perspective and transform-style: preserve-3d: Ensure proper 3D rendering

@keyframes rotate3d: Creates the continuous cube rotation

::before and ::after: Creates the glass-like reflections that occur on hover

10. Chameleon SVG

Chameleon SVG

Loading interactive CodePen...

Open on CodePen

When hovered over, the card cycles through different SVG-based background patterns and shifts the pattern's position smoothly across the surface. It works with:

background-image: Uses inline SVG data to display custom patterns

@keyframes move-and-color: Defines the stages of animation, specifying changes to background-image and background-position

That's it for the custom CSS hover effects. Now, let's move on to examples from other developers. We'll start with checking out card hover animations; view this Codepen collection to see other text animations I created.

Build a site with interactive 3D hover effects!

Take hover effects to the next level with 3D interactions. In this creative course, we build a customizer app and landing page with real-time animations using Next.js 15, GSAP, Prismic, Three.js, Tailwind, and TypeScript!

A GIF of Suburbia website

View Course

Card CSS hover animations

These card hover animations add a unique effect that will grab the attention of your visitors'.

11. Profile card hover

Profile card Hover

Loading interactive CodePen...

Open on CodePen

The profile card hover animation by Codev Land creates a two-layer sliding effect on a card component. When hovered, the top slide (with an icon) moves up to reveal the bottom slide containing text. This animation relies on:

transform: translateY() (docs): Moves each slide along the vertical axis during hover

transition (docs): Creates a smooth animation effect when both slides' positions change on hover

12. CSS hard hover effects

CSS Card Hover Effects

Loading interactive CodePen...

Open on CodePen

The CSS hard hover effects by Bruno Rocha creates a dynamic card hover effect, where top layer shrinks on hover to reveal the inner text-filled layer. The creator uses the transition property to add to the cards to animate changes in their height, border-radius, and font size during hover.

13. Glowing gradient glassmorphism card

Glowing Gradient Glassmorphism Card

Loading interactive CodePen...

Open on CodePen

The Glowing gradient glassmorphism card by Kodplay creates a visually appealing card layout with a hover animation effect. Each card has a distinct style, with unique gradient backgrounds, blur effects, and hover interactions. Here's a breakdown of how the code works:

::before and ::after pseudo-elements: Creates gradient skewed backgrounds. On hover, the skew effect is removed, and the dimensions adjust

transition: Animates the hover effects

span::before and span::after: Adds blur and glow effects on hover

backdrop-filter (docs): Adds a glassmorphism effect to the card's content

@keyframes animate: Creatives a slight vertical motion to give a dynamic floating effect

14. Tourist cards

hovering cards

Loading interactive CodePen...

Open on CodePen

The tourist cards hover effect by karim jawhar features three interactive cards, each showcasing the image of a landmark. When hovered over, the cards transform by rotating along the X and Z axes, giving them a 3D effect. This animation works with:

transform: rotateX, rotateZ, translateY, and translateZ properties create the 3D rotation and positioning effect that occurs on hover

transition: Smoothens the change between states, especially on the transform and box-shadow, making the hover effect more fluid

15. Same height cards

FlexBox Exercise #4 - Same height cards

Loading interactive CodePen...

Open on CodePen

The same height cards animation by Veronica is another great example. When hovered over, the cards enlarge slightly and reveal more information about the items, such as a "like" icon and time information. At the same time, the image becomes partially opaque as its opacity reduces.

This animation relies on:

transform: scale: Enlarges the card on hover, making it appear to "pop" out

card__img--hover class: Handles the changes that occur on the background image when hovered. The image properties that change include opacity (docs), background-size (docs), and background-position (docs)

### Requisitos Adicionales

## 👥 Registro de Equipo

Formen un equipo de **2 integrantes** para enfrentar el reto juntos. Completen el siguiente registro:

---

### 📋 Datos del Equipo

| N° | Nombres | Apellidos | Correo Electrónico |
|----|---------|-----------|-------------------|
| 1  | [Campo] | [Campo]   | [Campo]            |
| 2  | [Campo] | [Campo]   | [Campo]            |

### Entrega y exportación de resultados

- Botón **"Imprimir / guardar como PDF"** en el expediente final, con una vista de impresión que muestre solo el contenido del expediente (sin navegación ni botones de la actividad).
- Botón **"Descargar expediente (.md)"** que genere y descargue un archivo Markdown con el registro completo de las respuestas del equipo: datos del equipo, estado de cada caso, pistas clasificadas, formato elegido y su justificación, secuencia y matriz del proceso, evidencia detectada, mensaje descifrado, término del anagrama, reflexiones finales y autoevaluación.
- Botón de apoyo ("Pedir una pista al docente") disponible en cada pregunta o interacción de los cinco casos, con ventanas emergentes que muestren preguntas guía sin revelar la respuesta.
- Panel de glosario accesible en cualquier momento de la actividad (por ejemplo, mediante un botón flotante visible en todas las secciones), con las definiciones de los términos técnicos clave del proceso gráfico.
- Retroalimentación inmediata y constante en cada pregunta de la actividad, tanto en respuestas correctas como incorrectas.

Entrega toda la aplicación en un único archivo HTML listo para ejecutarse.
Usa Bootstrap 5 para lograr un diseño moderno y responsivo.
Incluye service worker y manifest.json para funcionamiento offline e instalación como PWA.
Asegúrate de que el diseño sea completamente responsivo en dispositivos móviles.
Incluye un Footer al final del documento con exactamente este texto:
  "Docente: Mg Mario Quiroz | Curso: Unidad didáctica de Producción y publicación de piezas gráficas · 2026 · Semana 1"
 Instituto de Educacion Superior Pública "Diseño y Comunicación"

### Instrucciones Finales

Entrega toda la aplicación en un único archivo HTML listo para ejecutarse.
Usa Bootstrap 5 para lograr un diseño moderno y responsivo.
Incluye service worker y manifest.json para funcionamiento offline e instalación como PWA.
Asegúrate de que el diseño sea completamente responsivo en dispositivos móviles.
Incluye en el expediente final los botones de impresión/PDF y de descarga del expediente en Markdown (.md) con las respuestas del estudiante.
Incluye un botón de ayuda ("Pedir una pista al docente") en cada pregunta o interacción, y un panel de glosario accesible desde cualquier punto de la actividad.
Mantén la retroalimentación inmediata y constante en cada pregunta, sin excepción.
