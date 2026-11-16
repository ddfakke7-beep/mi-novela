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

### Selección y efectos de las esencias

- Una configuración utilizará **tres esencias distintas** elegidas entre las siete disponibles.
- Cada esencia tendrá un **efecto característico propio**, que se manifestará automáticamente durante el combate según las condiciones de la configuración. No será una habilidad adicional que el jugador tenga que activar con un botón.
- Los efectos de las esencias no tienen por qué modificar directamente los ataques básicos, las habilidades o la definitiva. La dirección actual es que funcionen como efectos de combate propios (por ejemplo, impactos, descargas, marcas o zonas), independientes de la estructura de habilidades del personaje.
- De las tres esencias elegidas, el jugador señalará una como **esencia principal visual**. Esta elección determinará la apariencia o manifestación visual de los ataques.
- La esencia principal visual no tendrá más poder, estadísticas ni peso mecánico que las otras dos. Cambiarla modificará la presentación visual, no el funcionamiento ni la potencia de la configuración.
- Las tres esencias elegidas estarán activas en la configuración. Sus efectos característicos podrán coexistir, sujetos a condiciones y equilibrio.
- **Sinergias entre esencias: opcionales y pendientes.** Se podrá estudiar si ciertas combinaciones generan efectos adicionales, pero no se considera un requisito del sistema. No se diseñarán ahora las 35 combinaciones ni se dará por hecho que todas necesitan una sinergia exclusiva. Si las sinergias complican demasiado el diseño o el desarrollo, el juego podrá funcionar sin ellas.
- Con siete esencias y selecciones de tres distintas existen 35 combinaciones posibles, pero ese número no implica tener que crear 35 mecánicas, animaciones o efectos visuales exclusivos.
- Los efectos concretos, sus condiciones, frecuencias, valores y presentación visual quedan pendientes de diseño y balance.

### Pasivas

Las pasivas serán opciones de personalización que complementen las esencias y permitan construir estilos de combate distintos. No habrá categorías obligatorias como «pasivas principales» y «secundarias»: todas serán pasivas y se diferenciarán por el efecto que producen.

Podrán ser modificadores sencillos de estadísticas (daño, defensa, regeneración, velocidad, críticos, enfriamientos, etc.) o efectos que alteren condiciones y resultados de combate (por ejemplo, acumular más rápido, potenciar una explosión o recuperar vida al activar un efecto). No todas necesitan una sinergia especial con otras pasivas.

**Base de trabajo provisional:** se proponen inicialmente tres pasivas por cada esencia, como primer conjunto de referencia. No es un límite definitivo: durante el diseño podremos añadir, sustituir o utilizar otras pasivas si aportan algo mejor y mantienen el equilibrio. Los ejemplos de la tabla son orientativos, no una lista cerrada ni necesariamente exclusiva de cada esencia.

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

### Equipamiento normal

**Dirección provisional:** el equipo normal será un sistema independiente de la selección de esencias. Su función principal será aportar estadísticas generales y potenciar al personaje sin obligar a conseguir un conjunto distinto para cada combinación.

- Las piezas podrán aportar estadísticas generales, por ejemplo ataque, defensa, vida, velocidad de movimiento, velocidad de ataque, crítico, regeneración o reducción de enfriamiento.
- No se establecerán afinidades fijas obligatorias que exijan reunir equipo específico para las tres esencias seleccionadas.
- Un conjunto de equipo bien desarrollado deberá seguir siendo útil al cambiar entre distintas combinaciones de esencias y pasivas.
- El equipo podrá complementar diferentes estilos, pero no deberá determinar por sí solo qué combinación es viable ni convertirse en un requisito para reparar una configuración.
- No están definidos todavía los tipos de piezas, conjuntos, rarezas, estadísticas secundarias, mejoras ni la forma de obtener el equipo.

### Pieza especial

**Dirección provisional:** se contempla una ranura exclusiva para una pieza especial, separada del equipo normal. La referencia conceptual es el espacio de objeto neutral de Dota 2: un objeto particular con su propio espacio, no una pieza más de un conjunto de armadura.

- La pieza especial podrá seleccionarse y desarrollarse/mejorarse durante la progresión.
- Sus mejoras podrían potenciar los efectos automáticos de las esencias, modificar algunas de sus propiedades o aportar beneficios adicionales a la configuración.
- Deberá poder utilizarse con distintas combinaciones de esencias; no se pretende obligar al jugador a conseguir una pieza diferente por cada build.
- Su funcionamiento exacto, obtención, niveles de mejora, variedad de opciones y relación con las esencias quedan pendientes.
- Esta pieza no está definida todavía como un sistema cerrado: se conserva como una posibilidad de diseño que se evaluará al desarrollar la progresión.

### Principios de equilibrio y simplicidad

- Las siete esencias deben ofrecer identidades y posibilidades útiles, sin que una sea obligatoria o claramente superior en todos los casos.
- Los efectos automáticos de las esencias deben aportar identidad y variedad al combate sin exigir botones adicionales ni alterar obligatoriamente cada ataque básico, habilidad o definitiva.
- Las sinergias entre esencias son opcionales; no se debe añadir complejidad solo por completar todas las combinaciones posibles.
- Las pasivas, el equipo y la pieza especial deben ampliar las opciones, no invalidar unas configuraciones para hacer obligatorias otras.
- Evitar que cambiar de configuración implique repetir farmeo o conseguir varios conjuntos completos de equipo.
- Priorizar efectos comprensibles, reutilizables y fáciles de ajustar.
- Los porcentajes, valores, fórmulas, límites y sinergias definitivos se establecerán durante el balance.

### Decisiones pendientes

- Confirmar los nombres y descripciones definitivos de las siete esencias.
- Diseñar los efectos automáticos característicos de cada una de las siete esencias.
- Decidir más adelante si se incorporan sinergias entre esencias; son opcionales y no forman parte de los requisitos actuales.
- Diseñar y equilibrar el catálogo de pasivas; las tres por esencia son solo una base inicial.
- Definir cuántas pasivas se equipan y cómo se desarrollan.
- Definir el funcionamiento, obtención y mejoras de la pieza especial.
- Definir piezas, rarezas, estadísticas, conjuntos y obtención del equipo normal.
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
