# Del archivo al pliego

Actividad 3 de la sesión 1 de la unidad didáctica Producción y publicación de piezas gráficas, programa de estudios de Diseño Publicitario, IESTP «Diseño y Comunicación» (IDC). Periodo 2026.

Archivo: `Del_archivo_al_pliego_S01.html` (un solo archivo HTML, 107 KB aprox.).

## Datos de la actividad

| Campo | Dato |
|---|---|
| Programa de estudios | Diseño Publicitario |
| Sesión / actividad | Sesión 1 / Actividad 3 |
| Capacidad | Elaborar piezas gráficas de comunicación publicitaria, considerando los fundamentos y principios del diseño, técnicas creativas, herramientas analógicas y digitales, y atendiendo los requerimientos específicos del cliente |
| Indicador de logro | Elige formatos según canal de difusión |
| Fases del ciclo de Kolb | OR → CA → EA |
| Duración | 35 a 40 min |
| Agrupamiento | Individual o en pareja |
| Uso de IA | Nivel 1 de la escala AIAS (sin IA) |
| Evidencia | Reporte PDF o Markdown subido a Google Classroom |
| Material base | Guía de preimpresión emelar.es (S01.s1) |

Consigna de la actividad: contrastar las hipótesis del estudiante con la nomenclatura formal (plancha, entintado, cuatricromía CMYK, pliego, tiraje, imposición, acabados: barniz, laminado, troquelado) y resolver un mini-caso de 4 preguntas cerradas sobre el proceso.

## Uso

1. Abrir `Del_archivo_al_pliego_S01.html` con doble clic en Chrome, Edge, Firefox o Safari. No requiere instalación ni servidor.
2. Completar el registro: nombres, apellidos y correo electrónico. Las estaciones se activan cuando los tres campos son válidos.
3. Recorrer las 5 estaciones en orden.
4. En la estación 5, pulsar «Generar reporte» y descargar el PDF o el Markdown.
5. Subir el archivo descargado a la tarea de Google Classroom.

Los datos se guardan solo en la memoria de la pestaña. Al cerrar o recargar la página se pierden; el reporte debe descargarse antes.

## Estaciones

| N.º | Estación | Fase | Mecánica | Registro en el reporte |
|---|---|---|---|---|
| 1 | Tu hipótesis del proceso | OR | Ordenar 5 pasos descritos en lenguaje cotidiano a partir de la orden de trabajo 0412 (2 000 volantes A5, 4/4, offset) | Orden propuesto, coincidencias con el proceso formal, hipótesis escrita |
| 2 | Contrasta con la nomenclatura formal | CA | Comparación del orden propio con el proceso formal; 7 situaciones con 3 opciones de término técnico | Términos logrados e intentos por término |
| 3 | Mini-caso: la orden 0412 en producción | EA | 4 preguntas cerradas con vista 3D manipulable | Respuesta e intentos por pregunta |
| 4 | Anagrama de taller | CA | PLANCHA, TIRAJE, IMPOSICIÓN; pistas en 3 niveles; tiempo opcional de 60 s | Palabras reconstruidas y pistas usadas |
| 5 | Transferencia | EA | Elección de sistema para 50 menús; reflexión escrita; autoevaluación en 3 niveles | Elección, reflexiones y autoevaluación |

### Respuestas del mini-caso (estación 3)

| N.º | Tema | Respuesta | Cálculo o criterio |
|---|---|---|---|
| 1 | Imposición | 4 volantes por cara | Volante con sangrado 152 × 214 mm, girado: 450 ÷ 214 = 2,1 y 320 ÷ 152 = 2,1 |
| 2 | Planchas | 8 planchas | 4 tintas (CMYK) × 2 formas (cara y dorso) |
| 3 | Pliegos del tiraje | 500 pliegos | 2 000 ÷ 4, sin merma de arranque |
| 4 | Acabados | Laminado mate → barniz UV selectivo → troquelado | El barniz queda sobre la película; el troquel separa las piezas al final |

Respuesta de la estación 5: impresión digital, porque un tiraje de 50 ejemplares no justifica grabar planchas.

### Vista 3D de la estación 3

Se manipula arrastrando (girar), con la rueda o dos dedos (acercar) y con los botones Pliego, Planchas, Pila, Acabados y Girar solo. Cada respuesta correcta modifica la escena:

| Pregunta | Cambio en la escena |
|---|---|
| 1 | Aparecen 4 volantes A5 girados sobre el pliego de 450 × 320 mm |
| 2 | Aparecen 8 planchas con franja C, M, Y, K en dos filas (cara y dorso) |
| 3 | Crece la pila de 500 pliegos |
| 4 | Se aplican la película de laminado y el barniz sobre el logo; los volantes se separan |

## Retroalimentación

Cada error abre un panel con cinco componentes: pausa, pista, dato, contexto y reintento. Ningún error resta puntos ni bloquea el avance. Los aciertos se marcan con símbolo y texto además de color. La tira de control CMYK de la parte superior indica las estaciones completas.

## Reporte

| Formato | Contenido | Nombre del archivo |
|---|---|---|
| PDF (A4) | Logo IDC, datos del estudiante y correo, fecha de inicio y de generación, resultados por estación, reflexiones y autoevaluación; pie con número de página | `Reporte_S01_A03_Del_archivo_al_pliego_<Apellidos>_<Nombres>.pdf` |
| Markdown | El mismo contenido en tablas y secciones | `Reporte_S01_A03_Del_archivo_al_pliego_<Apellidos>_<Nombres>.md` |

El botón «Copiar texto» copia el reporte en Markdown al portapapeles.

## Requisitos técnicos

| Componente | Versión | Origen | Sin conexión |
|---|---|---|---|
| Three.js | r128 | cdnjs.cloudflare.com | La estación 3 muestra el pliego en 2D |
| OrbitControls | 0.128.0 | cdn.jsdelivr.net | La vista 3D no se puede girar |
| Anime.js | 3.2.2 (UMD) | cdnjs.cloudflare.com | Los cambios de la escena ocurren sin transición |
| jsPDF | 2.5.1 | cdnjs.cloudflare.com | El botón de PDF avisa que no cargó; el Markdown funciona |
| Archivo, Source Serif 4, IBM Plex Mono | — | Google Fonts | Se usan tipografías del sistema |

El logo IDC está embebido en base64. El JavaScript está escrito en ES5 dentro de una única función autoejecutable, para que funcione abierto con doble clic (`file://`). No usa `localStorage` ni `sessionStorage`. Respeta la preferencia de movimiento reducido del sistema y el tema claro u oscuro.

En la versión publicada en Claude, la descarga del reporte pasa por una ventana de confirmación del visor. La página publicada es privada hasta que se comparte desde su menú Compartir.

## Criterios de diseño aplicados

DUA 3.0 (CAST, 2024):

| Principio | Aplicación |
|---|---|
| Compromiso | Hipótesis propia sin calificación en la estación 1; temporizador opcional en la estación 4 |
| Representación | Cada término como situación, definición con fuente, esquema 2D o 3D y glosario con buscador |
| Acción y expresión | Ordenar, elegir, deletrear, decidir en un caso y escribir una reflexión |

Criterios neuroeducativos:

| Código | Aplicación |
|---|---|
| N-01 | La estación 1 abre con una orden de trabajo, sin definiciones previas |
| N-02 | La retroalimentación aparece después de confirmar; sin animaciones en las zonas de decisión |
| N-04 y N-06 | Dificultad creciente; los sellos premian criterios cumplidos; el error no resta |
| N-05 | El texto visible usa «reto» y «estación», no «examen» |
| N-07 | Cada término en varias modalidades para todo el grupo |
| N-08 | Aciertos marcados con símbolo y texto además del color |
| N-09 | Reto de inicio sugerido para la sesión 2 (3 min): anagrama IMPOSICIÓN y pregunta 2 del mini-caso con un trabajo 4/1 (respuesta: 5 planchas) |

## Fuentes y precisiones

- Datos técnicos de la guía de preimpresión de emelar.es (material S01.s1):
  - sangrado mínimo de 2 mm;
  - carga de tinta máxima de 300 % en papel estucado;
  - barniz selectivo preparado con negro al 100 %, sin líneas menores de 0,5 pt ni textos menores de 7 pt;
  - marcas de troquel: corte continuo, hendido discontinuo, 0,25 pt;
  - descripción del offset.
- La guía no define «pliego» ni «tiraje»; sus definiciones son de la actividad.
- El glosario de la guía define «plancha» como «montaje de varias páginas juntas», acepción que corresponde a la imposición. La actividad usa la acepción de la entrada «offset» de la misma guía: lámina metálica, generalmente de aluminio, que toma la tinta.
- La guía denomina «plastificado» al laminado.
- Supuestos del caso:
  - pliego de 450 × 320 mm;
  - forma distinta para cara y dorso (con tiro y retiro de la misma forma serían 4 planchas);
  - la altura de la pila (500 pliegos ≈ 15 cm) es una estimación a 0,3 mm por hoja de 300 g y debe cotejarse con el calibre del papel real.
- El indicador de logro debe cotejarse con el sílabo vigente.

## Referencias

- CAST. (2024). *Universal Design for Learning Guidelines version 3.0*. https://udlguidelines.cast.org
- Emelar Artes Gráficas. (s. f.). *Guía de preimpresión*. emelar.es
- Forés, A., Gamo, J. R., Guillén, J. C., Hernández, T., Ligioiz, M., Pardo, F. y Trinidad, C. (2015). *Neuromitos en educación: el aprendizaje desde la neurociencia*. Plataforma Editorial.
- Furze, L., Perkins, M., Roe, J. y MacVaugh, J. (2024). *The AI Assessment Scale revisited: A framework for educational assessment* [Preprint]. arXiv. https://doi.org/10.48550/arXiv.2412.09029

---

Mg. Mario Quiroz Martinez — Unidad didáctica Producción y publicación de piezas gráficas · Instituto de Diseño y Comunicación
