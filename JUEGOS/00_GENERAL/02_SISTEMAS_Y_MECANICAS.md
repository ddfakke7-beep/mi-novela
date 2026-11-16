# 02 — SISTEMAS Y MECÁNICAS

Registro de los sistemas que tendrá que definir el proyecto. Por ahora es un mapa de trabajo, no una especificación técnica cerrada.

> **Estado:** las decisiones nuevas sobre exploración, secretos y recompensas son provisionales hasta terminar el diseño general.

## Progresión del personaje

- **Confirmado como dirección:** desarrollo mediante habilidades activas, habilidades pasivas y equipamiento.
- **Referencia conceptual:** L.A.G., por su concepto de habilidades pasivas ilimitadas.
- **Pendiente:** qué significa exactamente «ilimitadas» en nuestro juego, cómo se obtienen, acumulan, equipan, combinan, mejoran y equilibran.
- **Pendiente:** atributos, niveles, especializaciones, límites y posibles sinergias.

## Progresión del personaje: nivel, esencias, pasivas y equipo

**Dirección acordada hasta ahora; estructura todavía en definición.** El objetivo es permitir que el jugador consiga y pruebe distintas configuraciones sin tener que repetir farmeo cada vez que quiera cambiar de estilo.

### Nivel y puntos de desarrollo

- La progresión general seguirá una estructura familiar de ARPG: derrotar enemigos, obtener experiencia, subir de nivel y fortalecer al personaje.
- Se está usando el nivel 60 como referencia para el punto en el que el personaje alcanza el máximo nivel; el límite definitivo todavía debe confirmarse.
- Al alcanzar ese punto, los puntos de desarrollo deberán ser suficientes para llevar al máximo una configuración completa.
- Cambiar de configuración permitirá reiniciar y redistribuir los puntos, sin exigir materiales adicionales ni repetir actividades de farmeo.
- La intención es que el jugador pueda experimentar con otras configuraciones de inmediato, siempre que ya haya desbloqueado las esencias y pasivas que necesita.

### Desbloqueo y desarrollo

- Las esencias y pasivas que el jugador consiga quedarán desbloqueadas permanentemente.
- Los desbloqueos importantes podrán obtenerse mediante actividades, encuentros, jefes, desafíos u otros contenidos específicos del mundo. La intención es que el jugador pueda perseguir directamente aquello que le interesa, evitando cadenas de requisitos irrelevantes.
- **Desbloquear** una esencia o pasiva será distinto de **invertir puntos para desarrollarla** y de **seleccionarla para una configuración**.
- No se exigirá volver a conseguir una pasiva ya desbloqueada cuando el jugador cambie de configuración.
- No se ha decidido todavía si todas las pasivas estarán disponibles para equipar simultáneamente, cuántas pertenecen a cada esencia ni cómo se organiza exactamente su selección.

### Esencias

La esencia será una parte central de la identidad de la configuración, pero su significado todavía no está definido.

- No está decidido si las esencias representarán elementos, naturalezas de poder, conceptos u otra estructura.
- Tampoco está cerrado si una configuración utilizará una sola esencia principal o cómo podrá relacionarse con otras esencias.
- No se deben tratar como clases tradicionales (tanque, asesino, cazador, etc.) ni asumir que el jugador tendrá que elegir una clase permanente al comenzar.
- La cantidad de esencias, su organización y sus relaciones con las pasivas quedan pendientes de diseño.

### Pasivas

Las pasivas serán capacidades o efectos que el jugador podrá desbloquear y combinar para construir diferentes estilos de combate.

- Se contempla como referencia inicial que cada esencia tenga varias pasivas; se mencionó un rango aproximado de 5 a 8, pero no está decidido.
- Se busca permitir combinaciones entre capacidades y evitar que el sistema encierre al jugador en un único rol.
- Algunas pasivas podrían tener sinergias específicas con otras. No se pretende crear interacciones automáticas entre todas las combinaciones posibles.
- La cantidad, categorías, funcionamiento, mejoras y límites de equipamiento de las pasivas siguen pendientes.

### Equipamiento y afinidades

El equipamiento tendrá dos funciones que deben mantenerse diferenciadas:

1. **Estadísticas normales:** atributos propios de cada pieza, como ataque, defensa, vida u otros que se definan.
2. **Afinidades:** propiedades fijas de la pieza que contribuyen a potenciar determinadas naturalezas de poder, esencias o pasivas, una vez que esa relación esté definida.

Dirección provisional para las afinidades:

- Las afinidades de cada pieza serán fijas al conseguirla.
- Una pieza podrá tener una o varias afinidades; no todas tendrán necesariamente la misma cantidad.
- Las afinidades deberán relacionarse con el sistema de poderes del personaje, no ser una colección de elementos desconectada de las esencias y pasivas.
- Reunir suficiente afinidad de un tipo podría activar bonificaciones específicas. También se podrán estudiar sinergias entre afinidades concretas.
- Las combinaciones mixtas deberán ofrecer variedad sin ser automáticamente superiores a una configuración especializada.
- No se quiere exigir un set independiente completo para cada esencia o afinidad. Las piezas de distintas afinidades deberán poder combinarse.
- El equipo no debe determinar por sí solo la clase o el estilo del personaje: debe complementar y potenciar la configuración elegida.

### Principios para mantener el sistema manejable

- Priorizar reglas claras y reutilizables.
- Evitar materiales de mejora que obliguen a repetir farmeo solo para probar otra configuración.
- Evitar calcular o programar todas las combinaciones posibles entre esencias, pasivas y afinidades.
- Las sinergias especiales se definirán de forma explícita y limitada a combinaciones que aporten algo interesante.
- No fijar porcentajes, umbrales, cantidades definitivas ni fórmulas hasta que se haya definido qué representan las esencias y las pasivas.

### Decisiones pendientes

- Qué representa exactamente una esencia y cuántas habrá.
- Si existen elementos, naturalezas de poder u otra clasificación.
- Cómo se relacionan las esencias entre sí y con las pasivas.
- Cuántas pasivas tiene cada esencia y cómo se combinan/equipan.
- Qué bonificaciones concretas otorgan las afinidades del equipo y a qué capacidades afectan.
- Cómo funcionan los umbrales y las sinergias entre afinidades.
- Cómo se obtienen, mejoran y reemplazan las piezas de equipo.
- Límite definitivo de nivel y distribución exacta de puntos.

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
