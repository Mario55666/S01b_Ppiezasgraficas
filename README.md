# Tras las Pistas del Proceso Gráfico

PWA educativa de un solo archivo HTML (`tras-las-pistas-del-proceso-grafico.html`) para la unidad didáctica de Producción y publicación de piezas gráficas, dirigida a estudiantes de segundo semestre.

## Descripción

La actividad adapta cinco acertijos de *El gran libro de acertijos de Sherlock Holmes* a una investigación sobre el proceso de diseño, impresión y publicación de piezas gráficas. El estudiante resuelve cinco casos y un caso final de integración, relacionando pistas, deduciendo formatos (vectorial, ráster, video) y reconstruyendo la secuencia diseño → impresión → publicación.

## Requisitos para ejecutar

- Un navegador actualizado (Chrome, Edge, Firefox o Safari).
- Conexión a internet en el primer uso, para cargar Google Fonts y Bootstrap 5 desde CDN.
- No requiere instalación de dependencias ni servidor: el archivo se abre directamente.

## Uso

1. Abrir `tras-las-pistas-del-proceso-grafico.html` en el navegador (doble clic o arrastrar a una pestaña).
2. Completar el registro del equipo (2 integrantes).
3. Resolver los casos en orden; cada caso se desbloquea al completar el anterior.
4. Al cerrar el expediente final, quedan disponibles dos botones de entrega:
   - **Imprimir / guardar como PDF**: abre el diálogo de impresión del navegador con una vista del expediente sin elementos de navegación.
   - **Descargar expediente (.md)**: genera y descarga un archivo Markdown con las respuestas registradas por el equipo (pistas clasificadas, formato elegido, secuencia reconstruida, mensaje descifrado, reflexiones y autoevaluación).

## Estructura de los casos

| Caso | Acertijo base | Mecánica |
|---|---|---|
| 1 · La primera deducción | *La primera deducción* | Clasificación de pistas por arrastre (incluye dos pistas falsas para descartar) |
| 2 · Un problema iluminador | *Un problema iluminador* | Selección de formato + justificación escrita |
| 3 · El engaño del dominó | *El engaño del dominó* | Reordenar la secuencia del proceso + matriz formato-fase |
| 4 · Una historia probable | *Una historia probable* | Simulador de pixelación en `<canvas>` + pregunta de detección de error |
| 5 · Un mensaje codificado | *Un mensaje codificado* | Reconstrucción de mensaje + anagrama conceptual |
| Final · El expediente Sherlock Holmes | — | Integración, reflexión, autoevaluación y cierre del expediente |

## Notas técnicas

- Archivo único: HTML, CSS y JavaScript en el mismo documento.
- Bootstrap 5 y las fuentes Playfair Display / Lora se cargan por CDN.
- El manifest y el service worker se generan en tiempo de ejecución mediante `Blob` y se registran vía `URL.createObjectURL`, sin archivos externos.
- El estado de la actividad se mantiene en memoria (no usa `localStorage`); al recargar la página el progreso se reinicia.
- La instalación como aplicación (icono en escritorio o launcher) y el funcionamiento sin conexión dependen del navegador y de que los recursos se hayan cacheado en una visita previa con internet. Para instalabilidad garantizada, alojar el archivo en un servidor con HTTPS (por ejemplo GitHub Pages o Netlify).

## Créditos

Docente: Mg Mario Quiroz
Curso: Unidad didáctica de Producción y publicación de piezas gráficas · 2026 · Semana 1
Instituto de Educación Superior Pública "Diseño y Comunicación"
