# 01 — DISEÑO GENERAL

Este documento reúne las decisiones de diseño que afectan al juego completo, sin depender de si se representa en 2D o 3D.

> **Estado:** las decisiones nuevas de este documento son provisionales. Sirven para conservar lo acordado durante el diseño y podrán ajustarse antes de cerrar la visión general.

## Género y ambientación

- **Confirmado:** ARPG.
- **Dirección acordada:** fantasía sobrenatural.
- **Referencias:** Diablo para la experiencia ARPG; L.A.G. para la estructura de avance por etapas y territorios; ZZZ y Wuthering Waves para distintas ideas de exploración.
- **Pendiente:** tono exacto, estética, perspectiva y cámara, ritmo del combate y modelo de control.

## Estructura de progresión del mundo

- El avance principal se organiza mediante etapas que conducen a territorios nuevos.
- Cada etapa puede representar un territorio, piso, prueba, ciudad u otro destino que todavía debemos definir según el contexto del mundo.
- La estructura de etapas no significa que cada territorio sea un pasillo o un recorrido estrictamente lineal.
- Dentro de los territorios buscamos exploración, caminos alternativos, secretos, mazmorras, jefes opcionales y otros puntos de interés.
- Los territorios pueden variar en tamaño y contenido; no todos necesitan ser enormes ni tener exactamente la misma estructura.
- El jugador puede encontrar amenazas que superen su capacidad actual. No se ha decidido que todos los enemigos escalen automáticamente con él.
- El jugador no necesita completar todo el contenido opcional para avanzar. La motivación para explorar y fortalecerse debe surgir de lo entretenido que resulta jugar, no de temporizadores u obligaciones artificiales.

## Transición entre etapas

- **Dirección acordada:** reutilizar una mecánica sencilla y consistente de salida entre etapas.
- Al completar el contenido necesario de la etapa, el portal o salida queda disponible.
- El jugador se acerca e interactúa para avanzar al siguiente destino.
- La apariencia puede ser la de un portal u otra representación visual, pero la interacción y función general se mantienen. No hace falta inventar un sistema de transición diferente para cada territorio.
- **Provisional:** el jugador podrá regresar a territorios anteriores mediante puntos de teletransporte, para completar contenido pendiente o volver a explorarlos. La organización y las reglas concretas del viaje rápido quedan por diseñar.

## Exploración y registro de contenido

**Propuesta provisional:** cada territorio tendrá un registro de exploración que muestre el porcentaje completado y el progreso de sus distintas categorías.

El registro debería contabilizar prácticamente todo el contenido normal disponible en el territorio, según las categorías que finalmente incorporemos. Entre los ejemplos posibles están:

- Cofres normales y recompensas de exploración.
- Mazmorras y áreas secundarias.
- Jefes y encuentros especiales que formen parte del contenido registrable.
- Lugares y zonas descubiertas.
- Recursos, materiales y puntos de interés.
- Actividades, eventos, interacciones y desafíos.
- Otros descubrimientos que se definan al crear cada territorio.

El objetivo es que el jugador pueda saber qué contenido normal le falta y completar el territorio por sus propios medios, sin depender de guías externas. La exploración debe ser entretenida y razonablemente accesible: completar el registro debería depender principalmente de recorrer y disfrutar el territorio, no de repetir tareas tediosas o buscar elementos con criterios arbitrarios.

El 100% del registro normal no será obligatorio para desbloquear la salida ni para avanzar.

## Cofres ocultos y secretos opcionales

**Propuesta provisional:** habrá una categoría independiente de cofres ocultos o secretos especiales. Estos no forman parte del porcentaje normal de exploración y no impiden conseguir el 100%.

- El mapa del territorio podrá indicar la zona aproximada donde queda un secreto pendiente, sin revelar automáticamente su ubicación exacta.
- El secreto debe estar realmente escondido o requerir descubrir cómo acceder a él.
- Al consultar el secreto desde el registro o guía del mapa, el jugador podrá leer una pista breve. La pista debe orientar sin resolverlo todo.
- Las pistas y mecanismos concretos se diseñarán al crear cada territorio. No se fijan ahora acertijos genéricos ni una lista cerrada de mecanismos.
- Los secretos deben ser ingeniosos y relativamente sencillos de deducir. La intención es provocar un «¡ah, era eso!», no frustración ni búsquedas absurdas.
- Son contenido opcional: encontrarlos no debe ser requisito para progresar ni para completar el 100% normal.

## Sistema de ayudas para secretos

**Propuesta provisional:**

- La pista inicial del secreto se podrá consultar desde el registro/guía del mapa, sin tener que navegar por varias ventanas.
- Se contempla un recurso general de ayudas directas con recarga diaria, compartido por todo el juego y no separado por territorio.
- La cantidad inicial a evaluar es de **2 o 3 ayudas directas al día**.
- Una ayuda directa podrá revelar una orientación mucho más explícita o la solución del secreto.
- El sistema debe ser una comodidad para jugadores que no quieran dedicar tiempo a pensar en un acertijo, no una barrera que obligue a esperar para continuar jugando.
- La cantidad, recarga y presentación definitivas se decidirán más adelante.

## Recompensas de exploración

**Propuesta provisional:**

- Los cofres normales entregan recompensas habituales.
- Los cofres ocultos pueden ofrecer una recompensa mayor que la de un cofre normal, pero moderada y no imprescindible para la progresión.
- Las cifras usadas durante la conversación (por ejemplo, 20 frente a 100 unidades) son solo ilustrativas; no representan valores definitivos ni una economía aprobada.
- Las habilidades especiales y desbloqueos importantes deberían estar ligados a logros significativos, como derrotar determinados jefes, superar encuentros especiales o cumplir hazañas concretas. También se mencionaron como ejemplos derrotar cierta cantidad de enemigos o sobrevivir a una zona de amenazas.
- No se ha definido todavía qué recompensas exactas corresponde a cada actividad.

## Zonas especiales de desafío

- **Dirección acordada:** solo algunos territorios tendrán áreas especiales de desafío configurables, pensadas también para jugadores que buscan una exigencia mayor.
- Estas áreas serán opcionales y no deben convertir todas las etapas en el mismo menú de dificultad.
- **Propuesta provisional:** comenzar con tres niveles de exigencia, siempre que cada nivel aporte una diferencia perceptible y significativa.
- Superar cualquiera de los niveles debe tener mérito. Una dificultad menor no invalida el logro de completar la prueba.
- Las dificultades superiores podrán ofrecer recompensas adicionales o distintivas.
- **Pendiente:** qué parámetros cambian, cómo se configuran las pruebas, qué recompensas otorgan y si todos los desafíos comparten el mismo formato.

## Dificultad general

La primera referencia de diseño será el modo Extremo. Las consecuencias de morir ya están definidas como dirección aprobada para los tres modos:

- **Normal:** la muerte devuelve al jugador a un punto seguro o al último control de guardado, conservando el progreso registrado.
- **Difícil:** la muerte devuelve al último guardado y se pierde todo lo obtenido desde entonces que todavía no se haya guardado.
- **Extremo:** la muerte elimina la partida/run completa y obliga a empezar de nuevo, incluso si se había guardado.

Las reglas completas de guardado, persistencia y alcance de la pérdida están desarrolladas en `02_SISTEMAS_Y_MECANICAS.md`, apartado «Dificultad, muerte y guardado».

## Identidad propia

Las referencias a Diablo, L.A.G., ZZZ y Wuthering Waves pueden orientar directamente los aspectos que nos interesan, pero no obligan a reproducir todo su contenido. Debemos definir qué reglas, historia y características tendrá nuestro juego.
