# 05 — COMBATE, ESENCIAS Y CONFIGURACIONES (PROPUESTA PENDIENTE)

> **Estado: PENDIENTE DE REVISIÓN.** Este documento recoge la dirección discutida en conversación para ordenar el combate de un solo personaje, las diez esencias, las pasivas y sus posibles combinaciones. No convierte estas propuestas en decisiones aprobadas. Los conceptos, ejemplos, agrupaciones y reglas podrán modificarse o descartarse.

> **Alcance:** este documento pertenece a `00_GENERAL` y describe la intención compartida del juego. No define cómo se implementará en 2D ni en una futura versión 3D. No modifica ni sustituye los documentos de esas carpetas.

## 1. Filosofía de las configuraciones

La intención no es que exista una configuración universalmente superior. El jugador debería elegir la forma de jugar que le resulte más divertida para el personaje, el enemigo, la zona o el momento.

- Una configuración basada en esencias puede ofrecer efectos y mecánicas particulares.
- Una configuración basada en pasivas puede priorizar estadísticas y números: crítico, ataque, velocidad, vida, defensa u otros atributos.
- El jugador puede preferir una mezcla de ambas.
- También debería ser viable renunciar a ciertas mecánicas y derrotar al enemigo usando el kit básico del personaje: ataques normales, habilidad, definitiva y ataque cargado, aunque una configuración más defensiva o menos ofensiva pueda tardar más.
- Ninguna esencia debería ser un requisito para derrotar a un jefe.
- Cambiar de configuración debería ser una opción de experimentación, no un castigo ni una obligación por cada enemigo.

**Principio de diseño propuesto:** las configuraciones deben competir en estilo, comodidad, ritmo y experiencia, no mediante una jerarquía fija en la que una siempre haga más daño o sea obligatoria.

## 2. Combate con un solo personaje en campo

### El problema que queremos resolver

En juegos de equipos como Wuthering Waves o Zenless Zone Zero, una parte importante del ritmo surge de alternar personajes y preparar una ventana de daño:

1. Un personaje de soporte aplica mejoras generales.
2. Un sub-DPS prepara el objetivo, aplica efectos o mejoras más específicas y de duración limitada.
3. El DPS principal aprovecha la preparación para concentrar el daño durante una ventana corta.
4. La rotación vuelve a empezar cuando las mejoras o habilidades se agotan.

En nuestro juego controlamos un solo personaje. No podemos copiar literalmente la rotación de tres personajes ni depender de cambiar de personaje para que el combate tenga profundidad.

### Dirección que se quiere explorar

Trasladar la preparación, ejecución y recompensa de una rotación al propio combate del personaje y al estado del enemigo:

- **Preparación:** acciones del jugador, habilidades, ataques cargados o efectos de configuración preparan una oportunidad. También puede consistir en leer el patrón del enemigo y posicionarse.
- **Ventana de oportunidad:** el enemigo queda marcado, aturdido, paralizado, expuesto o en otra condición temporal; o el jugador activa una mejora propia.
- **Ejecución:** el jugador decide cómo aprovechar la oportunidad: combo básico, ataque cargado, habilidad, definitiva o una combinación de ellos.
- **Recuperación y adaptación:** mientras ciertas habilidades están en enfriamiento o el enemigo recupera su estado, el jugador sigue combatiendo con el resto de su kit. No se pretende que todo el daño ocurra en una ventana fija de ocho segundos.

La profundidad debería nacer de decisiones continuas: qué preparar, cuándo gastar una habilidad, cómo responder al enemigo y qué recurso o ventana aprovechar. No se busca convertir el combate en una rotación rígida que siempre se repita en el mismo orden.

### Principios que deben comprobarse

- El personaje debe seguir siendo divertido incluso sin equipar esencias.
- Los ataques básicos, el ataque cargado, la habilidad y la definitiva deben conservar utilidad real.
- No todo enemigo necesita una fase de preparación ni una ventana de burst.
- Los jefes pueden ofrecer oportunidades de daño, pero no deben quedar reducidos a esperar una ventana y descargar todo.
- Las acciones de preparación no deben convertirse en tareas obligatorias antes de cada golpe.
- Las mejoras y estados deben ser legibles, con duración y condiciones comprensibles.
- La variedad no debe depender exclusivamente de aumentar la velocidad de los enemigos o de diseñar combos muy complejos para cada jefe.

**Estado:** dirección de diseño pendiente de revisión; no se ha definido todavía una rotación oficial, una duración de ventana ni una fórmula de daño.

## 3. Estructura propuesta de esencias y pasivas

### Desbloqueo y equipamiento

La estructura discutida más recientemente es:

- Diez esencias en total.
- Cada esencia se relaciona con tres nodos pasivos que funcionan como requisitos de desbloqueo.
- El jugador recorre un árbol o mapa de progresión y elige libremente qué rutas desbloquear.
- Al completar los tres nodos asociados, desbloquea la esencia correspondiente.
- Los desbloqueos son permanentes.
- Desbloquear una pasiva no significa que su efecto quede activo permanentemente: el efecto se obtiene al equiparla en la configuración.
- Se podría desbloquear todo el árbol y conseguir las diez esencias.
- La configuración tendría dos selecciones separadas: hasta tres esencias y hasta nueve pasivas.
- Se puede equipar menos del máximo de esencias o pasivas, si el jugador lo prefiere.

**Punto importante aún sin resolver:** si los tres espacios de esencia y los nueve espacios de pasiva son independientes, el jugador podría equipar tres esencias y nueve pasivas a la vez. En ese caso, no existe un coste real por renunciar a una esencia. Hay que decidir si esa libertad es intencional o si ambos sistemas deben compartir algún presupuesto de configuración. No se establece aquí un intercambio de espacios como regla aprobada.

### Diferencia que se busca entre ambos sistemas

- **Esencias:** ofrecen efectos característicos, reglas o mecánicas que cambian cómo se desarrolla el combate.
- **Pasivas:** permiten personalizar estadísticas y pequeños efectos, y construir especializaciones numéricas o combinaciones concretas.

Esta separación es una orientación, no una regla cerrada. Algunas esencias actuales también son bonificaciones numéricas, por lo que existe un posible solapamiento que debe resolverse durante la revisión.

## 4. Las diez esencias — conceptos de trabajo

Todos los conceptos de esta lista se consideran **PENDIENTES DE REVISIÓN** como conjunto. Los porcentajes y tiempos mencionados son referencias provisionales, no valores finales.

| Esencia | Concepto propuesto | Funcionamiento de trabajo |
|---|---|---|
| **Ruptura** | Aturdimiento y vulnerabilidad | Aumenta la acumulación de aturdimiento/postura, facilita llenar la barra antes de que empiece un ataque interrumpible y aumenta el daño recibido por el enemigo durante su ventana de vulnerabilidad. No cancela mecánicas ya iniciadas que sean ininterrumpibles. |
| **Flujo** | Usos adicionales de habilidad | Concede usos adicionales de la habilidad existente del personaje. No crea una habilidad nueva ni exige una cadena automática. Las secuencias con usos consecutivos tienen una ventana limitada para continuar; si no se pulsa a tiempo, la secuencia termina y los usos restantes no quedan almacenados. |
| **Vitalidad** | Vida y curación | Aumenta la vida máxima y cura un 25% de la vida máxima cada vez que se activa la habilidad. Cada activación cuenta, incluidos usos consecutivos o adicionales de Flujo. La curación puede desperdiciarse si el personaje ya está a vida completa. |
| **Ruina** | Marcas de deterioro | Los golpes aplican o acumulan marcas en el enemigo; cada marca aumenta el daño que recibe. Las marcas disminuyen gradualmente si se deja de atacar, en lugar de desaparecer todas de golpe. |
| **Umbral** | Daño de definitiva | Aumenta provisionalmente un 25% el daño de la definitiva. No reduce su enfriamiento ni exige condiciones adicionales. Su identidad numérica debe revisarse frente a las pasivas de daño de definitiva. |
| **Contraataque** | Respuesta automática | Una vez cada intervalo provisional de 15 segundos, evita automáticamente un ataque normal de jefe y responde con un contraataque de área. No debería activarse frente a mecánicas especiales que exijan una respuesta concreta. |
| **Reflejo** | Recompensa por esquiva perfecta | Tras realizar una esquiva perfecta, aumenta ligeramente la velocidad de ataque durante un tiempo breve. Cantidad y duración pendientes. |
| **Argonaut** | Acumulación y liberación de poder | Acumula poder mediante acciones de combate, con énfasis propuesto en habilidad y ataque cargado. Al completar la carga, el jugador puede liberar el poder para potenciar una acción posterior. Falta decidir cómo se activa, consume y combina con el combo o la definitiva. |
| **Parry** | Interrupción mediante ataques | Facilita que los ataques básicos o habilidades del personaje puedan realizar parries e interrumpir ataques enemigos que admitan interrupción. No permite cancelar mecánicas especiales o ininterrumpibles. |
| **Parálisis** | Acumulación de estado de control | Los golpes acumulan una barra de estado en el enemigo. Al llenarla, queda inmovilizado o paralizado durante un breve periodo; después obtiene resistencia temporal para evitar controlarlo continuamente. |

## 5. Pasivas: conjunto inicial de treinta propuestas

Se propone comenzar con tres pasivas asociadas a cada esencia, para un total inicial de treinta. No se considera un límite definitivo ni significa que cada pasiva solo pueda combinarse con las otras dos de su esencia.

Los efectos de esta lista son bloques iniciales para diseñar configuraciones. Sus valores, nombres y funcionamiento todavía no están aprobados.

### Ruptura — aturdimiento y vulnerabilidad

1. **Impacto contundente:** los ataques pesados acumulan más aturdimiento.
2. **Aprovechamiento:** aumenta el daño contra enemigos aturdidos.
3. **Quiebre oportuno:** el primer ataque después de que el enemigo entre en estado vulnerable causa daño adicional.

### Flujo — habilidad y ritmo

4. **Ejecución fluida:** aumenta ligeramente el daño de la habilidad.
5. **Ritmo constante:** después de usar la habilidad, el siguiente ataque normal causa daño adicional.
6. **Dominio técnico:** aumenta el daño del último golpe de una secuencia de habilidad.

### Vitalidad — supervivencia

7. **Constitución:** aumenta la vida máxima.
8. **Resistencia natural:** reduce el daño recibido cuando la vida está baja.
9. **Recuperación:** aumenta la curación recibida.

### Ruina — marcas

10. **Herida profunda:** ciertos ataques acumulan marcas más rápido.
11. **Explotación de debilidad:** aumenta el daño contra enemigos marcados.
12. **Presión constante:** los ataques retrasan la pérdida de marcas.

### Umbral — definitiva

13. **Poder absoluto:** aumenta el daño de la definitiva.
14. **Impacto definitivo:** el primer impacto de la definitiva causa daño adicional.
15. **Remate:** la definitiva causa más daño a enemigos con poca vida.

### Contraataque — respuesta defensiva

16. **Respuesta violenta:** aumenta el daño del contraataque.
17. **Onda de choque:** aumenta el área del contraataque.
18. **Apertura:** el siguiente ataque normal después del contraataque causa daño adicional.

### Reflejo — esquiva

19. **Instinto:** amplía ligeramente la ventana de esquiva perfecta.
20. **Reacción veloz:** el siguiente ataque normal después de una esquiva perfecta causa daño adicional.
21. **Movimiento ágil:** aumenta la velocidad de movimiento brevemente después de una esquiva perfecta.

### Argonaut — carga y liberación

22. **Acumulación:** los ataques pesados generan más carga.
23. **Carga técnica:** las habilidades generan carga adicional.
24. **Liberación:** aumenta el daño de la descarga de Argonaut.

### Parry — interrupción

25. **Instinto de combate:** facilita realizar parries mediante ataques.
26. **Defensa ofensiva:** después de un parry exitoso, reduce brevemente el daño recibido.
27. **Castigo preciso:** los ataques que interrumpen a un enemigo causan daño adicional.

### Parálisis — control

28. **Acumulación anómala:** los ataques llenan más rápido la barra de parálisis.
29. **Inmovilización:** aumenta ligeramente la duración de la parálisis.
30. **Objetivo expuesto:** aumenta el daño contra enemigos paralizados.

## 6. Agrupaciones de configuraciones y combinaciones a explorar

No se propone diseñar a mano una bonificación exclusiva para cada pareja o cada conjunto posible de pasivas. Con treinta pasivas y nueve espacios, la cantidad de conjuntos posibles es enorme. La alternativa de trabajo es agrupar por objetivos de juego y definir reglas reutilizables para que el sistema calcule las combinaciones.

Las agrupaciones siguientes son ejemplos de builds que el jugador podría intentar formar. No son clases, restricciones ni combinaciones obligatorias.

### A. Configuraciones centradas en estadísticas

| Grupo | Pasivas que podrían encajar | Objetivo |
|---|---|---|
| **Crítico** | Poder absoluto, Impacto definitivo, Remate y futuras pasivas de probabilidad/daño crítico | Buscar golpes críticos y picos de daño. |
| **Ataque directo** | Ejecución fluida, Ritmo constante, Dominio técnico y pasivas generales de ataque | Potenciar el daño habitual sin depender de estados especiales. |
| **Velocidad** | Movimiento ágil, Instinto y futuras pasivas de velocidad de ataque/movimiento | Jugar de forma más rápida y móvil. |
| **Vida y resistencia** | Constitución, Resistencia natural, Recuperación y futuras pasivas de defensa | Aguantar más, cometer errores con menor castigo y ganar seguridad. |
| **Daño de definitiva** | Poder absoluto, Impacto definitivo, Remate y futuras pasivas específicas de definitiva | Concentrar una parte importante del daño en la definitiva. |
| **Daño pesado/cargado** | Impacto contundente, Acumulación y pasivas futuras de ataques cargados | Priorizar golpes lentos o cargados de mayor impacto. |

### B. Configuraciones centradas en mecánicas

| Grupo | Pasivas que podrían encajar | Objetivo |
|---|---|---|
| **Aturdimiento** | Impacto contundente, Aprovechamiento, Quiebre oportuno | Llenar la barra de aturdimiento y castigar la vulnerabilidad. |
| **Marcas** | Herida profunda, Explotación de debilidad, Presión constante | Aplicar marcas rápido y mantenerlas sobre el enemigo. |
| **Esquiva y contraataque** | Instinto, Reacción veloz, Movimiento ágil, Respuesta violenta, Onda de choque, Apertura | Obtener ventajas al esquivar y responder. |
| **Interrupción** | Instinto de combate, Defensa ofensiva, Castigo preciso | Aprovechar ataques enemigos interrumpibles. |
| **Parálisis** | Acumulación anómala, Inmovilización, Objetivo expuesto | Generar ventanas de control y daño. |
| **Carga y descarga** | Acumulación, Carga técnica, Liberación | Preparar una descarga potente mediante acciones concretas. |
| **Habilidad** | Ejecución fluida, Ritmo constante, Dominio técnico | Dar mayor protagonismo a la habilidad del personaje. |

### C. Configuraciones mixtas

También se deberían permitir mezclas sin penalización artificial por no completar un grupo:

- **Crítico + velocidad:** buscar muchos impactos rápidos con posibilidad de crítico.
- **Crítico + definitiva:** concentrar la inversión en una definitiva explosiva.
- **Vida + daño:** sacrificar parte del potencial ofensivo para jugar con más seguridad.
- **Vida + curación + Flujo/Vitalidad:** insistir en una experiencia de supervivencia y recuperación.
- **Aturdimiento + daño a vulnerables:** preparar ventanas de castigo sin depender de un personaje de soporte.
- **Marcas + ataques rápidos:** acumular y mantener marcas mediante presión constante.
- **Esquiva + contraataque + velocidad:** premiar el juego reactivo y móvil.
- **Interrupción + aturdimiento:** controlar ataques interrumpibles y acelerar la entrada a vulnerabilidad.
- **Parálisis + daño de definitiva:** inmovilizar al objetivo y aprovechar el tiempo disponible.
- **Carga + ataque pesado:** preparar y liberar potencia mediante golpes cargados.
- **Habilidad + curación:** priorizar el uso frecuente de habilidad y la supervivencia.
- **Ataque básico + estadísticas generales:** ignorar mecánicas especiales y fortalecer el kit normal.

Estas mezclas son ejemplos de intención. No se han definido bonificaciones exclusivas para ellas.

## 7. Regla de combinaciones: método de trabajo pendiente

Se propone estudiar un sistema de cálculo por etiquetas o familias, en lugar de programar una regla distinta para cada combinación concreta.

Una pasiva podría tener una o más etiquetas, por ejemplo:

- **Ofensiva:** ataque, daño general o daño de habilidad.
- **Crítico:** probabilidad crítica y daño crítico.
- **Velocidad:** velocidad de ataque o movimiento.
- **Supervivencia:** vida, defensa, reducción de daño y curación.
- **Definitiva:** daño o efectos de definitiva.
- **Aturdimiento:** acumulación y daño durante vulnerabilidad.
- **Marcas:** aplicación, mantenimiento y daño contra marcados.
- **Esquiva/contraataque:** recompensas por evitar y responder.
- **Interrupción:** parry e interrupción.
- **Parálisis:** acumulación, duración y daño contra paralizados.
- **Carga:** generación y descarga de Argonaut.
- **Habilidad:** daño y efectos relacionados con la habilidad.

A partir de estas etiquetas se podrían estudiar reglas como:

1. Cada pasiva aporta su efecto base.
2. Equipar varias pasivas de una misma familia puede activar una bonificación de conjunto.
3. Mezclar familias puede permitir builds híbridas sin que una familia sea requisito de otra.
4. Las bonificaciones se calculan automáticamente según las pasivas equipadas.
5. Los efectos que se solapan deben compartir límites para evitar multiplicadores descontrolados.

**Ejemplo ilustrativo, no aprobado:** si el jugador equipa varias pasivas críticas, el sistema podría reconocer la concentración en crítico y otorgar una pequeña bonificación adicional de esa familia. No haría falta escribir manualmente una regla para cada combinación exacta de tres, cuatro, cinco o nueve pasivas.

### Valores y límites

Se ha mencionado como objetivo explorar bonificaciones acumuladas de alrededor de **30%**, con **40%** como posibilidad más extrema. No se ha aprobado ningún límite ni porcentaje.

Antes de fijarlos hay que comprobar:
- Si el porcentaje es ataque, daño final, probabilidad crítica, daño crítico u otro atributo.
- Si las bonificaciones se suman o multiplican.
- Cuánto aporta cada pasiva individual.
- Cuántas pasivas de una misma familia se necesitan para activar una sinergia.
- Qué ocurre cuando varias pasivas afectan al mismo efecto.
- Si el resultado sigue siendo razonable con equipo, nivel y esencias.

## 8. Solapamiento entre esencias y pasivas

Este es uno de los problemas centrales que todavía debemos resolver.

No basta con decir que las esencias son mecánicas y las pasivas son estadísticas, porque algunas esencias actuales también ofrecen bonificaciones numéricas:

- **Ruina:** aumenta el daño que recibe el enemigo mediante marcas. Es una vulnerabilidad condicionada al objetivo y al mantenimiento de las marcas.
- **Umbral:** aumenta directamente el daño de la definitiva en un 25%.
- Una build de pasivas podría intentar acumular daño general o daño de definitiva y terminar ofreciendo una ventaja similar o superior.

El diseño debe evitar que una esencia sea una elección claramente inútil frente a una pasiva, pero tampoco debe impedir que un jugador especializado consiga números muy altos si esa es la experiencia que busca.

Posibles soluciones para probar:
- La esencia ofrece un efecto más completo o eficiente; las pasivas ofrecen aumentos menores y más fragmentados.
- La esencia afecta a una condición o mecánica que las pasivas no reproducen por completo.
- Una build de pasivas puede superar a una esencia en un atributo concreto, pero debe renunciar a otras oportunidades de configuración.
- Rediseñar las esencias cuyo efecto sea únicamente una bonificación numérica para darles una identidad más particular.

No se elige todavía ninguna solución. En particular, Umbral y las pasivas de daño de definitiva necesitan compararse directamente.

## 9. Preguntas pendientes para la revisión

1. ¿Los espacios de esencia y pasiva son independientes o comparten un presupuesto de configuración?
2. ¿Las esencias deben tener siempre un efecto mecánico propio, o aceptamos que algunas sean principalmente numéricas?
3. ¿Qué diferencia exacta debe existir entre la bonificación de una esencia y la que puede alcanzar una build de pasivas?
4. ¿Las combinaciones se calculan por familias/etiquetas o queremos un sistema de sinergias más específico?
5. ¿Qué atributos podrán alcanzar bonificaciones elevadas y cuáles necesitan límites estrictos?
6. ¿Cómo se genera y consume la carga de Argonaut?
7. ¿Cómo se integran las oportunidades de preparación y daño en el combate de un solo personaje sin crear una rotación rígida?
8. ¿Qué pasivas de las treinta propuestas son realmente interesantes y cuáles deben sustituirse?

## 10. Regla de revisión

Todo el contenido de este documento permanece **PENDIENTE** hasta revisarlo. Las listas y agrupaciones sirven para facilitar la discusión, no para dar por aprobados los efectos. Una vez revisado un punto, su estado podrá cambiarse individualmente a APROBADO, MODIFICADO o DESCARTADO.
