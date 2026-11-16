# 02 — SISTEMAS Y MECÁNICAS

Registro de los sistemas que tendrá que definir el proyecto. Por ahora es un mapa de trabajo, no una especificación técnica cerrada.

> **Estado:** las decisiones nuevas sobre exploración, secretos y recompensas son provisionales hasta terminar el diseño general.

## Progresión del personaje

- **Confirmado como dirección:** desarrollo mediante habilidades activas, habilidades pasivas y equipamiento.
- **Referencia conceptual:** L.A.G., por su concepto de habilidades pasivas ilimitadas.
- **Pendiente:** qué significa exactamente «ilimitadas» en nuestro juego, cómo se obtienen, acumulan, equipan, combinan, mejoran y equilibran.
- **Pendiente:** atributos, niveles, especializaciones, límites y posibles sinergias.

## Progresión del personaje: nivel, esencias, pasivas y equipo

**Estado: estructura provisional acordada.** La intención es permitir que el jugador consiga y pruebe distintas configuraciones sin repetir farmeo cada vez que quiera cambiar de estilo. Los nombres, efectos, cantidades y valores concretos podrán ajustarse durante el balance.

### Nivel y puntos de desarrollo

- La progresión general seguirá una estructura familiar de ARPG: derrotar enemigos, obtener experiencia, subir de nivel y fortalecer al personaje.
- Se utiliza el nivel 60 como referencia provisional para el nivel máximo.
- Al alcanzar ese nivel, los puntos de desarrollo deberían ser suficientes para maximizar una configuración completa.
- El jugador podrá reiniciar y redistribuir sus puntos para probar otras configuraciones, sin materiales adicionales ni farmeo obligatorio.
- La idea es que experimentar con una configuración distinta sea una decisión de diseño, no un castigo de recursos.

### Desbloqueo y desarrollo

Se mantienen tres conceptos separados:

1. **Desbloquear:** conseguir una esencia o pasiva mediante actividades, encuentros, jefes, desafíos u otros contenidos.
2. **Desarrollar:** invertir puntos para mejorar sus efectos, cuando corresponda.
3. **Configurar:** decidir qué esencias y pasivas utilizar.

- Los desbloqueos serán permanentes. Una vez conseguida una esencia o pasiva, no habrá que repetir su actividad para volver a utilizarla.
- Se buscará que el jugador pueda perseguir directamente el contenido que desbloquea lo que le interesa, sin cadenas de requisitos irrelevantes.
- La cantidad exacta de puntos, los costes y los límites de selección siguen pendientes.

### Las siete esencias principales

**Propuesta provisional:** el sistema parte de siete esencias base. No son clases tradicionales ni obligan a adoptar un rol fijo. Cada una representa una naturaleza de poder y una orientación de combate.

| Esencia | Concepto central | Expresión en combate |
|---|---|---|
| **Ruptura** | Impacto y presión | Quebrar defensas, provocar impactos contundentes y castigar la resistencia enemiga. |
| **Flujo** | Movimiento y continuidad | Favorecer la movilidad, la velocidad y la fluidez de las acciones. |
| **Vitalidad** | Vida y resistencia | Mejorar la supervivencia, la recuperación y la capacidad de mantenerse en combate. |
| **Ruina** | Deterioro y desgaste | Debilitar al enemigo y causarle daño progresivo o efectos de desgaste. |
| **Umbral** | Marca y precisión | Premiar la precisión, las oportunidades y los ataques contra objetivos señalados o vulnerables. |
| **Arcanum** | Energía y proyección | Potenciar la energía, la proyección y la manifestación de las habilidades. |
| **Dominio** | Espacio y control | Influir en la posición de los enemigos y controlar áreas del campo de batalla. |

Estos conceptos sirven como identidad y orientación inicial; no son todavía una lista cerrada de habilidades ni una limitación absoluta sobre los efectos que podrá tener cada esencia.

### Selección y combinación de esencias

- Una configuración utilizará **tres esencias distintas** elegidas entre las siete disponibles.
- Las tres esencias participarán en una combinación que otorgará un **bonus especial propio de esa combinación**.
- Con siete esencias y selecciones de tres distintas existen 35 combinaciones posibles. La intención es que cada combinación pueda definirse mediante efectos y parámetros reutilizables, sin exigir habilidades, animaciones o recursos visuales exclusivos para cada una.
- De las tres esencias elegidas, el jugador señalará una como **esencia principal visual**. Esta elección determinará la apariencia o manifestación visual de los ataques.
- La esencia principal visual no tendrá más poder, estadísticas ni peso mecánico que las otras dos. Cambiarla modificará la presentación visual, no el bonus de la combinación.
- No se crearán nuevas esencias como resultado de combinar otras: se mantienen las siete esencias base y la combinación concede un bonus.
- Los efectos exactos de las 35 combinaciones, sus condiciones y sus valores quedan pendientes de diseño y balance.

### Pasivas

Las pasivas serán modificadores y efectos que complementen las esencias y permitan construir estilos de combate distintos. La intención es que su funcionamiento sea claro y que no requieran crear una gran cantidad de animaciones o efectos visuales únicos.

**Base de trabajo provisional:** se proponen inicialmente tres pasivas por cada esencia, como primer conjunto de referencia. No es un límite definitivo: durante el diseño podremos añadir, sustituir o utilizar otras pasivas si aportan algo mejor y mantienen el equilibrio.

Ejemplos iniciales para orientar el diseño:

| Esencia | Tres pasivas iniciales propuestas |
|---|---|
| **Ruptura** | Penetración de defensa; daño de impacto; daño adicional contra enemigos con defensas debilitadas. |
| **Flujo** | Velocidad de movimiento; velocidad de ataque; recuperación de enfriamientos. |
| **Vitalidad** | Regeneración de vida; robo de vida; resistencia al daño. |
| **Ruina** | Daño progresivo; mayor duración de efectos de deterioro; daño adicional contra enemigos debilitados. |
| **Umbral** | Probabilidad de crítico; daño crítico; daño adicional contra objetivos marcados o vulnerables. |
| **Arcanum** | Generación de energía; daño de habilidades; reducción del coste de energía. |
| **Dominio** | Alcance o área de efecto; daño contra enemigos agrupados; mayor eficacia de efectos de control. |

Estas pasivas son ejemplos de dirección, no efectos aprobados ni exclusivos de cada esencia. Se podrán explorar otras opciones y distribuirlas donde tengan más sentido. No todas las pasivas tienen que ser únicas de una sola esencia.

- Las pasivas podrán complementarse y, cuando aporte valor, tener sinergias específicas con otras pasivas o con combinaciones de esencias.
- No se pretende programar una interacción especial para cada pareja o conjunto posible. Las sinergias se definirán de forma explícita y limitada.
- Quedan por decidir la cantidad de pasivas que se podrán equipar, sus niveles de mejora, sus requisitos y la organización de la selección.

### Equipamiento

**Dirección provisional:** el equipo será un sistema independiente de la selección de esencias. Debe potenciar al personaje sin obligar a conseguir un conjunto distinto para cada combinación.

- Las piezas podrán aportar estadísticas generales, por ejemplo ataque, defensa, vida, velocidad de movimiento, velocidad de ataque, crítico o reducción de enfriamiento.
- No se establecerán afinidades fijas obligatorias que exijan reunir equipo específico para las tres esencias seleccionadas.
- Un conjunto de equipo bien desarrollado deberá seguir siendo útil al cambiar entre distintas combinaciones de esencias y pasivas.
- El equipo podrá complementar diferentes estilos, pero no deberá determinar por sí solo qué combinación es viable ni convertirse en un requisito para reparar una configuración.
- Se contempla estudiar una ranura o pieza de especialización con una bonificación intercambiable, pero todavía no está decidido si existirá ni qué forma tendrá.
- No están definidos todavía los tipos de piezas, conjuntos, rarezas, estadísticas secundarias, mejoras, bonificaciones especiales ni la forma de obtener el equipo.

### Principios de equilibrio y simplicidad

- Las siete esencias deben ofrecer identidades y posibilidades útiles, sin que una sea obligatoria o claramente superior en todos los casos.
- Las combinaciones deben aportar variedad sin crear 35 sistemas independientes difíciles de mantener.
- Las pasivas y el equipo deben ampliar las opciones, no invalidar unas configuraciones para hacer obligatorias otras.
- Evitar que cambiar de configuración implique repetir farmeo o conseguir varios conjuntos completos de equipo.
- Priorizar efectos comprensibles, reutilizables y fáciles de ajustar.
- Los porcentajes, valores, fórmulas, límites y sinergias definitivos se establecerán durante el balance.

### Decisiones pendientes

- Confirmar los nombres y descripciones definitivos de las siete esencias.
- Definir el bonus concreto de cada combinación de tres esencias.
- Diseñar y equilibrar el catálogo de pasivas; las tres por esencia son solo una base inicial.
- Definir cuántas pasivas se equipan y cómo se desarrollan.
- Determinar si habrá una ranura o pieza de especialización en el equipo y cómo funcionará.
- Definir piezas, rarezas, estadísticas, conjuntos, mejoras y obtención del equipo.
- Confirmar el nivel máximo y la distribución exacta de puntos.

## Combate

- **Confirmado como dirección:** combate de acción en tiempo real.
- Queremos que la variedad y dificultad surjan principalmente de los enemigos, sus patrones, ataques, combinaciones y encuentros; no de inventar reglas fundamentales diferentes para cada territorio.
- **Dirección inicial:** el jugador debe poder responder a amenazas mediante acciones como esquivar, bloquear o interrumpir, según el ataque y las capacidades disponibles.
- Algunos ataques enemigos podrán ser extremadamente peligrosos e incluso letales si el jugador no los evita o bloquea correctamente. Los ejemplos concretos y sus reglas todavía están por diseñar.
- **Pendiente:** ataques, defensa, esquivas, bloqueos, contraataques, recursos, estados, control de masas, daño, resistencias, enemigos y jefes.

## Registro de exploración

**Propuesta provisional:** cada territorio tendrá un registro accesible desde el mapa (la tecla o control definitivo todavía no está cerrado; se ha usado M como ejemplo).

El registro mostrará el porcentaje de exploración y el progreso de las categorías de contenido. La intención es contabilizar prácticamente todo el contenido normal del territorio: cofres normales, mazmorras, jefes o encuentros registrables, lugares descubiertos, recursos, actividades, desafíos, interacciones y otros descubrimientos que se definan.

- El jugador debe poder identificar qué contenido normal le falta sin necesitar una guía externa.
- Completar el 100% debería ser cuestión de explorar y disfrutar, no de realizar tareas repetitivas o búsquedas arbitrariamente difíciles.
- No será obligatorio completar el 100% para desbloquear la salida ni avanzar.
- Los cofres ocultos y secretos especiales se contabilizarán aparte y no afectarán al porcentaje normal.
- Las categorías exactas y el cálculo del porcentaje quedan pendientes.

## Cofres ocultos y pistas

**Propuesta provisional:** los cofres ocultos son secretos opcionales independientes del registro normal.

- El mapa/registro podrá indicar una zona aproximada donde existe un secreto pendiente, sin mostrar su posición exacta.
- El jugador consultará una pista desde el propio registro o guía del mapa, idealmente mediante una indicación de información que permita verla rápidamente al pasar el cursor, si la interfaz final lo permite.
- Las pistas deben ser claras en su intención, ingeniosas y relativamente sencillas de deducir. Evitar acertijos arbitrarios, combinaciones sin lógica o secretos que dependan de revisar cada rincón sin ninguna señal.
- Los tipos de acertijo, mecanismos y soluciones se diseñarán cuando se creen los territorios y su contenido; no se fijan de antemano.
- Encontrar estos cofres no debe ser obligatorio para progresar ni para completar el 100% normal.

## Ayudas para secretos

**Propuesta provisional:** habrá una reserva de ayudas directas con recarga diaria, compartida globalmente entre los territorios.

- Se está considerando una cantidad de 2 o 3 ayudas directas por día.
- La ayuda directa podrá revelar una pista muy explícita o la solución del secreto.
- La recarga no debe bloquear el progreso general ni convertir los secretos en tareas con espera obligatoria.
- La cantidad exacta, el funcionamiento de la recarga y la interfaz quedan pendientes.

## Recompensas y desbloqueos

**Propuesta provisional:**

- Los cofres normales entregan recompensas habituales.
- Los cofres ocultos pueden entregar una cantidad mayor o una recompensa adicional, pero no tan significativa como para volverlos imprescindibles.
- Las cifras de ejemplo mencionadas durante el diseño no son valores definitivos.
- Las habilidades especiales y los desbloqueos importantes se reservarían para logros relevantes: jefes, encuentros especiales, hazañas o acciones concretas. Como ejemplos por explorar se mencionaron derrotar cierta cantidad de enemigos o sobrevivir a una zona llena de amenazas.
- La relación exacta entre actividades, recompensas, habilidades y progresión todavía no está definida.

## Desafíos opcionales

- Algunos territorios podrán incluir áreas especiales donde el jugador elige entre varios niveles de exigencia.
- **Propuesta provisional:** tres niveles, con diferencias reales en los encuentros y desafíos; evitar escalones que solo aumenten ligeramente las estadísticas.
- Los niveles más exigentes podrán ofrecer recompensas adicionales, pero completar cualquier nivel debe conservar su mérito.
- **Pendiente:** funcionamiento exacto, modificadores, recompensas y variedad de pruebas.

## Muerte y dificultad

- **Confirmado como dirección:** diseñar primero pensando en Extremo.
- **Provisional:** los modos podrían diferenciarse por las consecuencias de morir, incluida la posible pérdida de pasivas u otros avances.
- **Pendiente:** reglas exactas de muerte, recuperación, persistencia y guardado.
- Los demás modos deberán poder configurarse sin duplicar todos los sistemas.

## Otros sistemas por diseñar

- Inventario y almacenamiento.
- Equipo, rarezas, atributos y botín.
- Recursos, fabricación y comercio, si encajan con el diseño.
- Misiones, eventos y actividades.
- Progresión de enemigos y jefes.
- Viaje rápido y regreso a territorios anteriores.
- Guardado, carga y gestión de partidas.

No implementar ni dar por aprobadas reglas concretas hasta que se definan en el proceso de diseño.
