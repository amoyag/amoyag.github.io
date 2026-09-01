---
title: "EMM — Análisis de caso estructural"
permalink: /teaching/emm-caso-estructural
---
Estructura de Macromoléculas · 2026-27 · **5 % de la nota final**

Rellenad los ocho campos y entregad por el campus virtual. **Extensión total: una
o dos páginas.** No es un trabajo largo; es una ficha densa.

La rúbrica con la que se corrige está publicada en la guía de evaluación desde el
primer día. Los campos **2, 5 y 7** son los que distinguen una ficha trabajada de
una copiada del primer resultado de búsqueda.

Recordad que en el examen de enero hay una pregunta sobre vuestra molécula que
vale el 15 % del examen. La ficha se rellena en una tarde; esa pregunta, no.

---

## Vuestros datos

- **Nombre:**
- **Macromolécula asignada:**

---

## 1. Identificación

*Nombre de la macromolécula, organismo del que procede, entrada del PDB y año de
depósito.*

>

## 2. Método y calidad del modelo

*Método experimental. Resolución, con unidades — o, si el método no la define de
la misma manera, explicad por qué. Y **una limitación concreta** de este modelo:
qué parte de la estructura está peor determinada, qué falta en el fichero, o qué
no se puede ver a esta resolución.*

>

## 3. Composición

*Cuántas cadenas polipeptídicas hay depositadas y cuál es el estado oligomérico.
Qué ligandos, cofactores, iones metálicos o moléculas de agua estructurales
aparecen y dónde.*

>

## 4. Arquitectura

*Elementos de estructura secundaria dominantes y organización en dominios. Si la
proteína tiene un plegamiento con nombre reconocible, decidlo.*

>

## 5. Sitio funcional

*Un sitio de unión, un centro activo o una interfaz, descrito **con residuos
concretos** (número y tipo). «El sitio activo está en una hendidura» no vale:
decid qué residuos la forman y qué papel hace cada uno.*

>

## 6. Estructura y función

*Dos frases: cómo la arquitectura que habéis descrito hace posible la función.
No repitáis el campo 5 — aquí se trata de la conexión, no de la descripción.*

>

## 7. Elección de técnica

*Formulad **una pregunta abierta** sobre vuestra molécula: algo que no se sepa por
esta estructura, o que esta estructura no pueda contestar. Decid qué técnica del
curso la respondería, por qué esa y no otra, **y qué no os diría**.*

*Este campo es el que prepara directamente la Parte C del examen.*

>

## 8. Referencia primaria

*Una referencia que hayáis leído — el artículo original de la estructura, u otro
sobre la molécula. Cita completa. Y una frase sobre qué aporta que no estuviera
en la ficha del PDB.*

>

---

# Ejemplo resuelto

**Se usa hemoglobina, que no está en la lista de reparto** precisamente para que
sirva de ejemplo sin ser el trabajo de nadie. Es además la molécula que más
trabajamos en clase, así que podéis juzgar la profundidad esperada.

**1. Identificación.** Hemoglobina humana en estado desoxi (estado T). *Homo
sapiens*. PDB **2HHB**, depositada en 1984 (Fermi, Perutz, Shaanan & Fourme).

**2. Método y calidad del modelo.** Difracción de rayos X, 1,74 Å. A esta
resolución se resuelven las cadenas laterales con confianza y se ven aguas
ordenadas, pero **el modelo es una única conformación promediada sobre todo el
cristal**: no informa de la población de estados intermedios entre T y R, que es
justamente lo que hace falta para describir la cooperatividad. Los extremos
terminales de las cadenas suelen tener densidad más pobre y factores B altos.

**3. Composición.** Cuatro cadenas polipeptídicas depositadas, dos entidades
distintas: dos cadenas α y dos cadenas β. Tetrámero α₂β₂, que funcionalmente es
un dímero de dímeros αβ. Cuatro grupos hemo, uno por cadena, cada uno con su
Fe(II).

**4. Arquitectura.** Todo hélice α: el plegamiento de globina, ocho hélices
denominadas A–H por cadena, sin lámina β. El hemo se aloja en un bolsillo
hidrofóbico entre las hélices E y F.

**5. Sitio funcional.** El sitio de unión de O₂ es el Fe(II) del hemo. La
**His F8** (His87 en α, His92 en β) es la histidina proximal y coordina el hierro
por el quinto sitio, anclando el hemo a la hélice F. La **His E7** (His58 α,
His63 β), distal, no coordina el hierro pero forma un enlace de hidrógeno con el
O₂ unido y estorba estéricamente la geometría lineal que preferiría el CO, lo que
reduce la afinidad relativa por CO en unos dos órdenes de magnitud respecto al
hemo libre.

**6. Estructura y función.** Al unirse el O₂, el Fe(II) entra en el plano del
hemo y arrastra a la His F8 y con ella a toda la hélice F; ese desplazamiento se
transmite a la interfaz α₁β₂, que es la que cambia entre los estados T y R. Como
el cambio de una subunidad reorganiza la interfaz que comparten todas, la
afinidad de las restantes aumenta: la cooperatividad no está en el sitio de
unión, está en el acoplamiento mecánico entre subunidades.

**7. Elección de técnica.** *Pregunta*: ¿cuánto tiempo tarda la transición T→R
tras la unión del primer O₂, y hay intermedios poblados? La estructura
cristalográfica no puede contestarlo: da los dos extremos, no el camino.
*Técnica*: espectroscopía de absorción resuelta en el tiempo tras fotólisis de
flash del complejo con CO, que aprovecha que el hemo cambia de espectro al ligar
y permite seguir la cinética en la escala de microsegundos. *Qué no me diría*: da
poblaciones y constantes de velocidad, no coordenadas — sabría *cuándo* pasa
algo, no *qué* se mueve. Para eso haría falta cristalografía resuelta en el tiempo
o RMN, y cada una con su propia limitación.

**8. Referencia primaria.** Fermi, G., Perutz, M.F., Shaanan, B. & Fourme, R.
(1984). The crystal structure of human deoxyhaemoglobin at 1.74 Å resolution.
*Journal of Molecular Biology* 175(2), 159–174. Aporta el modelo refinado del
estado T que sirve de referencia a toda la descripción posterior del cambio
alostérico: la ficha del PDB da las coordenadas, el artículo da qué contactos
concretos de la interfaz α₁β₂ se rompen al pasar a R.
