# 01 — DISEÑO GENERAL

Este documento reúne las decisiones de diseño que afectan al juego completo, sin depender de si se representa en 2D o 3D.

## Género y ambientación

- **Confirmado:** ARPG.
- **Dirección acordada:** fantasía sobrenatural.
- **Referencias:** Diablo para la experiencia ARPG y L.A.G. para la estructura de avance por etapas y territorios desconocidos.
- **Pendiente:** tono exacto, estética, perspectiva y cámara, ritmo del combate y modelo de control.

## Estructura de progresión del mundo

- **Dirección acordada:** el avance principal se organiza mediante etapas que conducen a territorios nuevos.
- Cada etapa representa un territorio, piso, prueba, ciudad u otro destino que todavía debemos definir según el contexto del mundo.
- El jugador supera el contenido necesario de la etapa y puede continuar hacia la siguiente.
- La estructura de etapas no significa que cada territorio sea un pasillo o un recorrido estrictamente lineal.
- Dentro de los territorios buscamos exploración, caminos alternativos, secretos, mazmorras, jefes opcionales y otros puntos de interés.
- Los territorios pueden variar en tamaño y contenido; no todos necesitan ser enormes ni tener exactamente la misma estructura.
- El jugador puede encontrar amenazas que superen su capacidad actual. No se ha decidido que todos los enemigos escalen automáticamente con él.

## Transición entre etapas

- **Dirección acordada:** reutilizar una mecánica sencilla y consistente de salida entre etapas.
- Al completar la etapa, el portal de salida queda disponible o se activa.
- El jugador se acerca e interactúa para avanzar al siguiente destino.
- La apariencia puede ser la de un portal u otra representación visual, pero la interacción y función general se mantienen. No hace falta inventar un sistema de transición diferente para cada territorio.

## Exploración y contenido opcional

Los territorios deben ofrecer motivos para desviarse de la ruta principal: descubrir lugares, buscar recursos y equipo, encontrar secretos, explorar mazmorras o afrontar desafíos opcionales. La libertad de exploración debe convivir con el objetivo de avanzar por las etapas.

## Zonas especiales de desafío

- **Dirección acordada:** solo algunos territorios tendrán áreas especiales de desafío configurables, pensadas también para jugadores que buscan una exigencia mayor.
- Estas áreas serán opcionales y no deben convertir todas las etapas en el mismo menú de dificultad.
- **Propuesta provisional:** comenzar con tres niveles de exigencia, siempre que cada nivel aporte una diferencia perceptible y significativa.
- Superar cualquiera de los niveles debe tener mérito. Una dificultad menor no invalida el logro de completar la prueba.
- Las dificultades superiores podrán ofrecer recompensas adicionales o distintivas.
- **Pendiente:** qué parámetros cambian, cómo se configuran las pruebas, qué recompensas otorgan y si todos los desafíos comparten el mismo formato.

## Dificultad general

La primera referencia de diseño será el modo Extremo. Los modos menos exigentes se podrán construir mediante reglas configurables, pero no se ha cerrado todavía la tabla de penalizaciones.

La muerte y sus consecuencias son una mecánica importante por definir. La pérdida de pasivas, habilidades u otros elementos se mantiene como propuesta, no como regla final.

## Identidad propia

Las referencias a Diablo y L.A.G. pueden orientar directamente los aspectos que nos interesan, pero no obligan a reproducir todo su contenido. Debemos definir qué reglas, historia y características tendrá nuestro juego.
