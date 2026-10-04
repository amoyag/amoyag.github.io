---
title: "Bioquímica e Ingeniería de Proteínas"
collection: teaching
type: "Asignatura de grado — Grado en Bioquímica"
permalink: /teaching/bip
venue: "Universidad de Málaga, Facultad de Ciencias"
date: 2026-09-01
location: "Málaga, España"
excerpt: "Curso 2026–27. Proyecto de equipo sobre PTP1B: encargo, entregas, evaluación, bitácora, informes y plantillas."
comments: false
share: false
---

Curso **2026–27**. Clases expositivas abiertas y trabajo práctico de diseño de proteínas. Esta página reúne el encargo del proyecto, las instrucciones de trabajo y las plantillas. Las entregas se realizan en el **Campus Virtual (CV)**.

Actualización: **261004**. Las fechas se expresan como año, mes y día (YYMMDD); por ejemplo, 261113 significa 13 de noviembre de 2026.

**Contenido de esta página**

* Índice
{:toc}

<!-- Contenido del proyecto procedente de campus/261004_proyecto_equipo.md del repositorio BIP. -->

## Proyecto de equipo de BIP

El proyecto consiste en **diseñar y evaluar variantes de PTP1B con una especificación concreta**. Se trabaja en tres equipos de cinco estudiantes. Todos parten de la misma proteína; cada equipo estudia un problema distinto y defiende sus decisiones con los datos que haya reunido.

«La máquina genera; el estudiante selecciona». El trabajo del equipo consiste en formular el objetivo, interpretar los resultados, seleccionar o descartar candidatos y explicar qué falta para sostener una conclusión sobre su función.

**Un candidato que supera un filtro computacional no es una proteína cuya función se haya demostrado.** El proyecto distingue tres niveles: qué comprueba el cálculo, qué hipótesis funcional permite plantear y qué experimento distinguiría esa hipótesis de una alternativa. Se propone ese experimento; el proyecto no exige demostrar experimentalmente la función de las variantes.

### El encargo de cada equipo

Las especificaciones se asignan por sorteo en S12. La ficha de cada equipo concreta los residuos y las restricciones.

| Equipo | Problema de diseño | Lo que debe poder justificar |
|---|---|---|
| A | Modificar el entorno del bucle WPD para estudiar la hipótesis de rigidificarlo, conservando la maquinaria catalítica | Por qué una geometría compatible con el objetivo no basta para demostrar un cambio de movilidad o de actividad |
| B | Modificar el bolsillo alostérico para intentar impedir la unión del ligando de referencia, conservando el plegamiento y la maquinaria catalítica | Qué evidencia apoyaría una pérdida de unión y cómo distinguirla de un defecto de plegamiento o de actividad |
| C | Modificar posiciones de superficie alejadas de ambos sitios, como control | Si los datos apoyan la hipótesis de una menor perturbación funcional; la distancia a los sitios no garantiza que todo siga funcionando |

Se evalúa la calidad de la investigación y del razonamiento. **Un equipo sin candidatos que superen el filtro puede obtener la máxima calificación** si caracteriza los fallos, justifica sus decisiones y reconoce los límites de la evidencia.

### Cómo se desarrolla el trabajo

**Se conservan los cuadernos de Colab de cada sesión como archivos separados.** Se trabaja sobre las plantillas preparadas por el profesor y se añaden los análisis, interpretaciones y decisiones. No hay que escribir un notebook desde cero ni reunir las sesiones en un segundo «cuaderno de evidencia». En S12 se localizan las regiones; en S14 se comprueba la especificación; en S16 se trabaja la selección y en S19 se revisan las decisiones tras las objeciones a la propuesta. La continuidad la dan una carpeta de evidencias y una bitácora breve que enlaza los cuadernos y resultados.

Fuera del aula, el trabajo se organiza en tres tramos. **TE1** documenta la selección inicial y los descartes con los datos anteriores al filtro. **TE2** incorpora el rediseño de secuencia y la comparación entre el esqueleto diseñado y el modelo obtenido al predecir de nuevo su estructura. **TE3** caracteriza los candidatos y prepara la selección que se defenderá. Los enunciados detallados, los criterios de terminado y las rúbricas de los informes se comunicarán en S19, el 261021.

Antes de PR4 y PR5 se reservan al menos tres candidatos sin filtrar. Cada estudiante registra su decisión y su previsión antes de conocer el resultado. **La papeleta no se califica por acertar ni por fallar.** Lo que se evalúa posteriormente es la reconstrucción razonada de las decisiones.

La bitácora permite reconstruir qué se analizó, quién lo hizo, con qué datos y por qué se tomó cada decisión. La IA puede utilizarse, declarando su uso y comprobando sus resultados por otra vía. **Las preguntas individuales se harán en la presentación del proyecto.** Durante el desarrollo, el trabajo individual se documenta por escrito en los cuadernos, la bitácora y los anexos; no se añaden entrevistas de seguimiento.

### Entregas y evaluación

Los puntos de esta tabla son puntos sobre los 100 de la asignatura. Se mantienen los pesos publicados: **proyecto 70 y prácticas 30**.

| Entrega | Fecha | Puntos de equipo | Puntos individuales |
|---|---|---:|---:|
| Propuesta de diseño | 261019–261020 | 10 | — |
| Informe de progreso 1, INF1 | 261113 | 8 | 7 |
| Informe de progreso 2, INF2 | 261204 | 8 | 7 |
| Defensa oral | 261217–261218 | 10 | 20 |

La **propuesta** presenta el objetivo, los residuos y restricciones, la estrategia, el criterio de éxito y un modo de fallo que ese criterio podría pasar por alto. **INF1** documenta la selección inicial, el panel anterior al filtro y los descartes. **INF2** recoge el rediseño, los resultados del filtro, las decisiones posteriores y la justificación experimental. La **defensa** presenta la selección final y permite comprobar el razonamiento de cada integrante.

Los talleres individuales TI1 y TI2 aportan dos puntos cada uno dentro de los siete puntos individuales de INF1; no se suman otra vez. TI3 es formativo. La nota individual depende de las evidencias y respuestas de cada persona. El detalle se recoge en la guía de evaluación del Campus.

### Organización de archivos y herramientas

Se utilizan **Google Drive, Colab, Google Sheets y Google Docs**, con las plantillas enlazadas más abajo. Cada integrante trabaja desde su propia cuenta. La carpeta del equipo reúne los Colab y resultados compartidos, la bitácora y los informes colectivos. Los anexos individuales y los originales individuales se mantienen en el espacio personal y se comparten con el profesor; no hace falta mostrarlos al resto del equipo.

| Material | Herramienta | Quién lo completa | Para qué sirve |
|---|---|---|---|
| Cuaderno de cada sesión y sus resultados | Colab y Drive | Equipo o estudiante, según la actividad | Conservar cálculos, salidas e interpretación |
| Bitácora breve | Google Sheets | Equipo, identificando responsables | Enlazar evidencias y registrar decisiones |
| INF1 e INF2 colectivos | Google Docs | Equipo | Explicar y justificar el recorrido del proyecto |
| Anexo de INF1 y de INF2 | Google Docs | Cada estudiante | Mostrar una decisión propia y su razonamiento |

Se conservan las versiones entregadas de los cuadernos. Para continuar un análisis después de entregarlo, se crea una copia identificada como revisión, manteniendo el original. **No hay que duplicar en la bitácora el código, las tablas completas ni las respuestas de los Colab.**

### Cómo se utiliza la bitácora

Se hace una copia de la plantilla por equipo. La pestaña **Inicio** contiene las instrucciones y los enlaces generales; **Decisiones** contiene las entradas reales; **Ejemplo** muestra una entrada didáctica ficticia que no forma parte del trabajo entregado.

Cada fila recoge una decisión relevante, con identificador, fecha, candidato o región, responsable y aportación, decisión, evidencia localizable y alternativa o límite. Si intervienen varias personas, se indica brevemente qué aportó cada una. Una revisión añade otra fila que remite al identificador anterior.

Las columnas «Previsión del filtro» y «Resultado del filtro y fecha» se completan cuando corresponda. En S12, al localizar regiones, puede escribirse «No aplica». Antes de filtrar un candidato, el resultado es «No ejecutado». Una previsión ya registrada no se reescribe después de conocer el resultado. La bitácora del equipo no sustituye la papeleta individual.

**No hay cuota de entradas ni se puntúa el número de ediciones.** Una fila breve que enlaza un resultado y explica una decisión es suficiente; ejecutar una celda sin tomar una decisión no obliga a crear una fila nueva. El panel y el diagrama del procedimiento se enlazan cuando estén disponibles, sin copiarlos de nuevo.

### Qué muestran los informes y los anexos

Los informes se redactan sobre la evidencia conservada. Las plantillas mantienen un orden común y señalan los criterios de evaluación junto al apartado correspondiente. Se sustituyen los campos entre corchetes por respuestas concretas, conservando los títulos. La longitud de la plantilla no fija un máximo de páginas: se escribe lo necesario para justificar las decisiones y se enlazan los registros extensos.

**INF1 de equipo** documenta el recorrido hasta los diez candidatos, interpreta el panel prefiltro, justifica los descartes e identifica la reserva para PR4. **INF2 de equipo** explica el uso de los resultados de PR4, la autoconsistencia con su convención, las decisiones posteriores y las tres cuestiones experimentales. Cada informe incluye una tabla breve de contribuciones: nombre, aportación concreta y evidencia. No se asignan porcentajes de participación.

**El anexo individual se escribe y entrega por separado.** Puede tratar el mismo candidato que otro integrante, pero debe permitir reconocer la operación y el razonamiento propios. Una afirmación como «ayudé con los cálculos» se concreta indicando qué entrada se utilizó, qué se comprobó, dónde está el resultado y cómo se interpretó.

| Anexo | Evidencia individual que se solicita | Puntos |
|---|---|---:|
| INF1 | Originales de TI1 y TI2, enlazados sin repetirlos ni volver a puntuarlos | 2 + 2 |
| INF1 | Reconstrucción de una decisión propia aplicada al proyecto, transfiriendo lo aprendido en TI1/TI2 | 2 |
| INF1 | Comparación con la decisión del equipo, alternativa y razón del acuerdo o desacuerdo | 1 |
| INF2 | Papeletas y registros propios originales, identificables y concordantes | 2 |
| INF2 | Contraste entre previsión y resultado del filtro | 1,5 |
| INF2 | Síntesis experimental personal vinculada al candidato | 1 |
| INF2 | Comparación con el criterio del equipo y una alternativa | 1,5 |
| INF2 | Cambio de criterio o mantenimiento justificado | 1 |

Entre ambos anexos, cada estudiante documenta **una operación computacional propia**, con entrada, herramienta, parámetro relevante, salida e interpretación. Puede hacerse sobre datos pregenerados y se valora dentro de los criterios existentes. No añade otra entrega. En INF1 no se exigen resultados del filtro sobre los candidatos del proyecto; en INF2 no se exigen TI3 ni PR5, posteriores a su entrega. No hace falta inventar un desacuerdo o un error para justificar una decisión.

### Cómo enlazar un Colab en el informe

1. Guardad el cuaderno en Drive con sus interpretaciones y salidas. Conservad también los archivos de resultados: compartir el notebook no comparte los archivos temporales de la máquina de Colab.
2. En **Compartir**, añadid la cuenta del profesor con acceso al cuaderno; para leer el Colab basta el permiso de lector. Copiad el enlace a vuestra copia, no al original vacío del profesor.
3. En Google Docs, seleccionad un texto descriptivo, como «S12 del equipo B, bloque 2», y usad **Insertar → Enlace**. Pegad el enlace. En Sheets podéis pegar la URL en la celda de evidencia y añadir el apartado y el archivo relevante.
4. Indicad junto al enlace la versión o fecha, el apartado o celda identificable y el resultado que utilizáis. No basta un enlace general a toda la carpeta.
5. Comprobad el acceso desde otra cuenta autorizada. Un enlace correcto no concede permisos automáticamente. Revisad también que los enlaces sigan funcionando en el PDF entregado.

Son operaciones de las herramientas de Google: [insertar enlaces](https://support.google.com/docs/answer/45893?hl=es) y [compartir notebooks de Colab](https://research.google.com/colaboratory/faq.html?hl=es).

### Compartir documentos y conservar las entregas

Los integrantes del equipo y el profesor tendrán permiso de **editor** en la bitácora y en los informes colectivos. En los anexos individuales, ese acceso corresponde al autor y al profesor. No hace falta habilitar acceso público. El permiso de editor permite al profesor consultar el historial; el permiso de lector o comentarista no basta para esa consulta.

Al entregar, se conserva una **versión con nombre** en el documento de trabajo y en la bitácora, por ejemplo `INF1_261113`. El PDF entregado en CV fija el contenido evaluable y mantiene el enlace al original. No se reemplaza el original de trabajo por una copia nueva al final, porque se perdería la continuidad de su historial. Las revisiones posteriores se identifican aparte.

Google permite consultar cambios y editores desde el historial de versiones. **El historial muestra actividad de edición, no demuestra por sí solo la calidad de la aportación ni recoge todo el trabajo fuera del documento.** La evaluación utiliza las evidencias, los anexos y las respuestas individuales en la presentación. No se asigna nota por cantidad de texto, clics o ediciones. [Ayuda de Google sobre el historial](https://support.google.com/docs/answer/190843?hl=es).

En cada fecha de informe se entregan:

- **Por equipo:** el PDF colectivo y una exportación de la bitácora en XLSX, con enlace al original de Sheets. Los paneles, manifiestos y resultados exigidos se conservan en la carpeta de evidencias y se enlazan desde el informe.
- **Por estudiante:** el PDF de su anexo individual, con enlaces al documento de trabajo y a sus evidencias. Las referencias a papeletas identifican únicamente las propias; no se publican respuestas ajenas.

Las actividades de entrega se organizarán en el CV separando la parte colectiva de los anexos individuales. Se mantienen las fechas de INF1 e INF2 indicadas arriba.

### Plantillas del proyecto

Se trabaja sobre una copia de cada plantilla mediante **Archivo → Hacer una copia**. Una bitácora por equipo, un documento colectivo por informe y un anexo por estudiante y por informe.

| Plantilla | Enlace |
|---|---|
| Bitácora de decisiones | [Abrir en Google Sheets](https://docs.google.com/spreadsheets/d/1xhoxmIs3oKrEVB9JwFtxbeLNc5F5jZ0gWOSCAou50yY) |
| INF1 de equipo | [Abrir en Google Docs](https://docs.google.com/document/d/1fJHtg7avPTKs4i33fn0ZnPuho57146aBU_9d3tkWTI8) |
| INF1 individual | [Abrir en Google Docs](https://docs.google.com/document/d/1W1n82U7Yyrr1qFra5w1Er3STN_mQpseIPSjs93SN6uM) |
| INF2 de equipo | [Abrir en Google Docs](https://docs.google.com/document/d/1CsyZ1fmawKDnbtGu3aXiHV36N75fhlQAo1zrYKS7lmc) |
| INF2 individual | [Abrir en Google Docs](https://docs.google.com/document/d/1ANzRFLhW2HG8nfE9aj73ejY7Ti543ERRUL_OEREwn68) |

### Qué se hace en S12

**S12 es el primer taller de equipo de esta etapa del proyecto.** Su resultado es una lectura comprobada de la especificación sobre la estructura. En esta sesión todavía no se generan variantes ni se ejecuta el filtro de candidatos.

Después del reparto se selecciona la letra del equipo en Colab y se carga el ZIP correspondiente. El paquete contiene las estructuras y la ficha YAML que necesita el cuaderno. Se guarda la copia de esa sesión con un nombre que identifique sesión, equipo y autor cuando sea individual, por ejemplo `S12_equipoB_261005.ipynb` o `TI1_NombreApellidos_261006.ipynb`. Si el cuaderno aún indica `BIP_A_equipoX` y pide añadir sesiones en él, se aplica esta organización: conservar cada sesión por separado y enlazarla desde la bitácora.

Al terminar se conserva el notebook con las interpretaciones y el registro de trabajo, junto con el ZIP de resultados que contiene la tabla y la figura. Debe explicarse una limitación concreta de lo que permiten concluir los datos. Este trabajo se reutiliza en S14.

### Cómo leer la ficha YAML

**El YAML es la ficha técnica del encargo, escrita de forma que pueda leerla el cuaderno.** El texto del proyecto explica para qué se diseña; el YAML concreta sobre qué estructura, en qué posiciones y con qué restricciones. Leer el archivo no ejecuta un diseño ni demuestra que se hayan cumplido sus condiciones.

Cada línea relaciona un nombre con un valor mediante dos puntos. Los corchetes contienen listas; el texto que sigue a `#` es un comentario. La sangría agrupa campos: los límites que aparecen debajo de `tolerancias` pertenecen a ese apartado. Los nombres de los campos se conservan porque el programa los busca literalmente.

Este fragmento reproduce campos de la ficha del equipo B; no sustituye al archivo completo:

```yaml
equipo: B
esqueleto: 1SUG
cadena: A
mapa_numeracion: autor
rango_modelado: [2, 299]
mutable: [187, 188, 189, 192, 193, 196, 197, 200, 276, 277, 279, 280, 281, 282]
```

Se lee así: «Somos el equipo B. Partimos de la cadena A de la estructura 1SUG. Usamos los números de residuo del PDB. El tramo modelado va del residuo 2 al 299. Se permite rediseñar la identidad de los aminoácidos de la lista `mutable`».

**Los números identifican posiciones, no aminoácidos nuevos.** `187` no significa “poner el aminoácido 187” ni “hacer 187 cambios”. Tampoco es el índice de una lista de Python. En `mutable` se enumeran posiciones concretas: del 189 se salta al 192; el 190 y el 191 no están incluidos. En cambio, el esquema de esta ficha interpreta `rango_modelado: [2, 299]` como los extremos de un intervalo. Es el significado del campo lo que distingue una lista de posiciones de un intervalo.

#### Las restricciones principales

| Campo | Lectura en palabras |
|---|---|
| `fijo_esqueleto` | Coordenadas del esqueleto que se conservan durante la etapa de diseño de secuencia sobre cada candidato. En estas fichas, `[[2, 299]]` representa el tramo completo. El candidato puede proceder de una generación previa de variantes de esqueleto |
| `fijo_identidad` | Posiciones cuyo aminoácido debe conservarse. Si una posición contiene cisteína, debe seguir conteniendo cisteína; eso por sí solo no demuestra que mantenga su geometría o su función |
| `mutable` | Posiciones en las que se permite cambiar el aminoácido. Es un permiso, no la obligación de que cambien todas. La ausencia de una posición en `fijo_identidad` no basta para autorizar su cambio |
| `subconjunto_restringido` | Posiciones sobre las que se evaluará la desviación geométrica específica del encargo. No es una lista adicional de mutaciones |
| `conjunto_de_ajuste` | Posiciones usadas para superponer las estructuras antes de medir las desviaciones |
| `atomos_funcionales` | Átomos concretos que requieren comprobación; por ejemplo, `{res: 215, atomo: SG}` identifica el átomo de azufre SG de Cys215 |
| `referencia_geometrica` | Estructura y convención que dan sentido a la comparación |
| `tolerancias` | Límites del filtro geométrico declarado; no probabilidades de éxito biológico |
| `metricas_obligatorias` | Comprobaciones que deben documentarse en las etapas correspondientes del proyecto |

Por ejemplo, el equipo B puede modificar la identidad en la posición 187 porque aparece en `mutable`. Debe conservar la de Cys215 porque figura en `fijo_identidad`. Además, se comprueba el átomo SG de esa cisteína. **Conservar la letra de la secuencia y comprobar la disposición espacial son operaciones distintas.**

Los campos `scrmsd_global_max: 2.0` y `scrmsd_especificacion_max: 1.0` corresponden a límites de 2 y 1 Å. El filtro exige valores inferiores a esos límites, con la convención de superposición establecida. El punto decimal se conserva en el archivo para que el programa lea los números. El scRMSD compara el esqueleto diseñado con la estructura predicha a partir de su secuencia: informa de autoconsistencia geométrica, no demuestra actividad.

El equipo B tiene además `referencia_bolsillo`: identifica `1T49` y el ligando `892` como referencia para delimitar el bolsillo. **1SUG es el esqueleto de partida y 1T49 la referencia del bolsillo**; sus papeles no son intercambiables.

En S12 el cuaderno lee la ficha, construye la tabla y la figura de regiones y comprueba la presencia de residuos y los solapes entre conjuntos. No aplica todavía todas las métricas escritas en el YAML. La tarea es poder señalar sobre la estructura «esto podemos cambiarlo, esto debemos conservarlo y aquí comprobaremos las consecuencias», y justificar que la selección coincide con la ficha.
