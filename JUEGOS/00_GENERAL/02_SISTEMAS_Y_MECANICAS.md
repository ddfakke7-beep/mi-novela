# 02 — SISTEMAS Y MECÁNICAS

Registro de los sistemas que tendrá que definir el proyecto. Por ahora es un mapa de trabajo, no una especificación técnica cerrada.

> **Estado general:** este documento reúne la base ya acordada y las propuestas iniciales de los sistemas que faltan. Cada apartado indica qué está confirmado y qué sigue pendiente; ninguna propuesta nueva se considera aprobada por aparecer aquí.

## Criterio de aprobación de sistemas

- **APROBADO:** decisión revisada y aceptada por el usuario. Se conserva como parte de la base del proyecto.
- **PENDIENTE:** propuesta inicial todavía no aceptada. Puede modificarse, simplificarse o descartarse durante la revisión.
- Los sistemas ya acordados mantienen su estado aprobado en cuanto a sus decisiones confirmadas. Que una cifra, fórmula, contenido concreto o detalle aparezca como pendiente no invalida las decisiones generales ya aprobadas.
- Cada sistema nuevo se incorpora primero como propuesta **PENDIENTE**. Se revisa punto por punto; solo después de la aceptación del usuario se cambia su estado a **APROBADO** y se pasa al siguiente sistema.
- Las referencias a AION 2 y Diablo IV sirven para estudiar soluciones existentes. Se reutilizarán las ideas que encajen con el proyecto, no se copiarán automáticamente sistemas completos ni dependencias propias de un MMO o de un ARPG concreto.


## Progresión del personaje

- **Confirmado como dirección:** desarrollo mediante habilidades activas, habilidades pasivas y equipamiento.
- **Referencia conceptual:** L.A.G., por su concepto de habilidades pasivas ilimitadas.
- **Pendiente:** qué significa exactamente «ilimitadas» en nuestro juego, cómo se obtienen, acumulan, equipan, combinan, mejoran y equilibran.
- **Pendiente:** atributos, niveles, especializaciones, límites y posibles sinergias.

## Progresión del personaje: nivel, esencias, pasivas y equipo

**Estado: base acordada; detalles pendientes.** La intención es permitir que el jugador consiga y pruebe distintas configuraciones sin repetir farmeo cada vez que quiera cambiar de estilo. Se conservan las decisiones generales ya aceptadas; los nombres, efectos, cantidades y valores concretos que no se hayan confirmado siguen abiertos.

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

Podrán ser modificadores sencillos de estadísticas (daño, defensa, regeneración, velocidad, críticos, enfriamientos, etc.) o efectos que alteren condiciones y resultados de combate (por ejemplo, acumular más rápido, modificar una condición de activación o cambiar el resultado de un efecto). No todas necesitan una sinergia especial con otras pasivas. Se buscará que algunas aporten cambios funcionales interesantes y no sean únicamente aumentos numéricos, pero sin crear interacciones complejas por defecto.

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
- La dirección actual es que ofrezca mejoras sencillas pero significativas, por ejemplo reducir el intervalo de activación de un efecto, aumentar su área o daño, o mejorar la regeneración.
- Debe tener una función diferenciada de las pasivas: no queremos que sea otra capa de bonificaciones que multiplique indiscriminadamente todos los efectos.
- Deberá poder utilizarse con distintas combinaciones de esencias; no se pretende obligar al jugador a conseguir una pieza diferente por cada build.
- Su funcionamiento exacto, obtención, niveles de mejora, variedad de opciones y relación con las esencias quedan pendientes.
- Esta pieza no está definida todavía como un sistema cerrado: se conserva como una posibilidad de diseño que se evaluará al desarrollar la progresión.

### Principios de equilibrio y simplicidad

- Las siete esencias deben ofrecer identidades y posibilidades útiles, sin que una sea obligatoria o claramente superior en todos los casos.
- Los efectos automáticos de las esencias deben aportar identidad y variedad al combate sin exigir botones adicionales ni alterar obligatoriamente cada ataque básico, habilidad o definitiva.
- Las sinergias entre esencias son opcionales; no se debe añadir complejidad solo por completar todas las combinaciones posibles.
- Las pasivas, el equipo y la pieza especial deben ampliar las opciones, no invalidar unas configuraciones para hacer obligatorias otras.
- Evitar acumular varias capas que potencien exactamente lo mismo y provoquen multiplicadores difíciles de equilibrar. Cada sistema debe tener una función reconocible: esencias definen efectos de combate, pasivas modifican o complementan esos efectos, equipo aporta estadísticas generales y la pieza especial ofrece una mejora concreta.
- No es necesario que todos los sistemas tengan sinergias entre sí. Las interacciones serán limitadas y se añadirán solo cuando aporten algo claro.
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
- **Dirección de simplificación en evaluación:** mantener un kit del personaje pequeño y relativamente fijo, en lugar de crear numerosas cadenas de ataques, habilidades y variantes. La variedad principal también vendrá de las configuraciones de esencias y de los enemigos.
- **Combo básico propuesto:** al ejecutar el ataque, el personaje realiza una secuencia de tres tajos hacia delante: los dos primeros son diagonales y se cruzan en forma de X; el tercero es horizontal. Se busca que la secuencia pueda ejecutarse sin exigir desplazamientos o animaciones de movimiento complejas para cada golpe.
- **Habilidad especial y definitiva:** cada una tendrá una función y efecto propios. No se pretende multiplicar sus versiones según cada combinación de esencias.
- **Protección durante habilidades:** la habilidad especial y la definitiva otorgarán invulnerabilidad durante su ejecución. Además de su función ofensiva, podrán utilizarse como herramientas defensivas para evitar ataques peligrosos.
- **Uso táctico de la invulnerabilidad:** estas acciones tendrán sus propios tiempos de reutilización, por lo que el jugador deberá decidir cuándo gastarlas para atacar o protegerse. No se fijan todavía duraciones ni tiempos de reutilización; deberán equilibrarse junto con la duración de las rotaciones y los patrones de los enemigos.
- **Límite frente a mecánicas de jefes:** la invulnerabilidad evitará el daño de ataques compatibles con ella, pero no resolverá automáticamente mecánicas especiales que exijan posicionarse, abandonar una zona, destruir un objetivo u otra respuesta concreta. Los jefes podrán plantear secuencias, áreas persistentes o varios impactos que obliguen a elegir bien cuándo utilizar estas herramientas.
- **Objetivo de diseño:** dar al jugador varias respuestas defensivas válidas (esquiva, guardia, habilidad y definitiva) sin quitar protagonismo a los jefes ni permitir que una sola acción ignore todos sus patrones.
- **Disponibilidad de habilidades:** la habilidad especial y la definitiva estarán disponibles desde el inicio del combate si sus respectivos tiempos de reutilización están completos. No dependerán de acumular energía golpeando enemigos, recibir daño, derrotar enemigos ni cambiar de personaje.
- **Recarga por tiempo:** al utilizar una habilidad, comenzará su propio tiempo de reutilización. Una vez terminado, volverá a estar disponible automáticamente. La intención es que el jugador pueda usar sus habilidades cuando las necesite y que la rotación dependa de administrar sus tiempos de reutilización, no de esperar a llenar una barra de energía.
- **Objetivo de diseño:** evitar que el jugador llegue a un encuentro o explore el mundo abierto sin poder utilizar una habilidad o definitiva importante por no haber cargado energía previamente. Se busca una experiencia fluida y consistente tanto en exploración como en combate.
- **Pendiente:** definir los tiempos de reutilización de la habilidad y la definitiva, y si existirán formas limitadas de reducirlos o acelerarlos.
- **Movimiento del personaje:** el personaje se desplaza libremente por el escenario también durante el combate. No será un sistema estático ni permanecerá clavado en un punto; la movilidad y el posicionamiento forman parte de la experiencia, manteniendo una base compatible con la futura adaptación a 3D.
- Los ataques se ejecutan desde la posición del personaje. La simplificación buscada está en el número y complejidad de acciones y animaciones, no en eliminar el movimiento libre.
- **Dirección de producción:** priorizar acciones y efectos reutilizables, con un alcance de animación y programación manejable tanto para la primera versión 2D como para una posible adaptación 3D. Evitar que cada esencia o combinación obligue a rehacer el combo, la habilidad o la definitiva.
- Las esencias aportarán efectos automáticos y modificaciones a la experiencia de combate; no deben convertir al personaje en un mero activador pasivo ni hacer que el kit base pierda toda importancia.
- La variedad y el desafío también se apoyarán en enemigos especiales y jefes con patrones o mecánicas particulares, de modo que el jugador tenga que responder a amenazas distintas y no solo aumentar el daño.
- **Esquiva:** será una de las respuestas defensivas principales, tomando como referencia juegos de acción como Wuthering Waves o Zenless Zone Zero. Al ejecutarla en el momento preciso, tendrá una ventana breve de invulnerabilidad que permitirá evitar prácticamente cualquier daño normal.
- **Sin barra de esquiva:** no consumirá una reserva de energía o resistencia ni dependerá de recuperar una barra durante el combate.
- **Límite contra el abuso:** la esquiva tendrá una animación de ejecución y recuperación durante la cual no se podrá encadenar otra inmediatamente. El límite vendrá de ese tiempo de recuperación, no de una barra que pueda agotarse. La duración exacta y la ventana de invulnerabilidad quedan pendientes.
- **Esquiva perfecta:** acertar el momento podrá ofrecer una pequeña recompensa u oportunidad ofensiva, pero no será necesario acertar siempre el timing perfecto para poder sobrevivir.
- **Guardia como alternativa:** el jugador también podrá adoptar una postura de bloqueo para reducir el daño recibido. Será una opción más permisiva que la esquiva, pensada para quien prefiera resistir y leer el ataque en lugar de depender tanto de los reflejos.
- **La guardia no será invulnerabilidad:** bloquear reducirá el daño, pero podrá provocar retroceso, interrupción o ruptura de guardia ante golpes fuertes o impactos consecutivos. No se busca añadir otra barra de recurso obligatoria; la presión de los golpes y sus consecuencias se resolverán mediante las reacciones del personaje y las reglas de los ataques.
- **Ataques especiales:** algunos ataques peligrosos podrán tener más de una respuesta válida. Según el diseño del ataque, el jugador podrá esquivarlos o resistirlos mediante una guardia adecuada, posiblemente con una consecuencia mayor; otros exigirán salir de un área, cambiar de posición o cumplir una mecánica concreta. No todos serán bloqueables ni esquivables por defecto.
- **Diferencia de mérito:** esquivar correctamente evitará el daño y podrá abrir una oportunidad para contraatacar; bloquear permitirá sobrevivir con mayor margen de reacción, pero normalmente implicará recibir daño reducido, perder posición o quedar expuesto. La guardia será una alternativa legítima, no una forma de anular gratis todos los ataques.
- **Diseño de dificultad:** los jefes no deberán volverse difíciles simplemente quitándole al jugador la posibilidad de esquivar o bloqueando artificialmente sus respuestas. La dificultad deberá venir de leer patrones, elegir la respuesta adecuada y gestionar las consecuencias. El jugador podrá superar encuentros usando principalmente esquiva, principalmente guardia o una combinación de ambas.
- Algunos ataques enemigos podrán ser extremadamente peligrosos e incluso letales si el jugador no responde correctamente.
- **Interrupciones al jugador:** no se plantea añadir un sistema general de interrupciones que cancele constantemente las acciones del personaje. La esquiva, la guardia y la invulnerabilidad de habilidad/definitiva ya ofrecen respuestas defensivas; evitar que recibir cualquier golpe corte continuamente las acciones es parte de la experiencia buscada.
- **Aturdimiento de enemigos:** habrá una barra de aturdimiento que se llena al golpear al enemigo. Cuando se completa, el enemigo queda quieto/aturdido durante un intervalo. El efecto consiste en detenerlo; no añade automáticamente daño aumentado, vulnerabilidad especial ni una ventana de castigo con bonificaciones.
- **Derribos:** no se considera necesario incorporar un sistema general de derribos.
- **Lanzamiento por el aire:** podrá aparecer como mecánica particular de determinados jefes o encuentros, no como una regla general para todos los enemigos.
- **Pendiente:** definir duración y recuperación de la esquiva, ventana de invulnerabilidad, comportamiento y límites de la guardia, y qué ataques especiales admiten bloqueo o exigen otra respuesta. No se añadirá por ahora un sistema separado de contraataques u otras respuestas defensivas. También quedan pendientes estados alterados, valores de aturdimiento, daño y diseño de enemigos y jefes. El desplazamiento libre del personaje ya queda establecido como dirección.

### Daño y estadísticas de combate

- **Dirección confirmada:** utilizar un sistema tradicional de ARPG, con atributos ofensivos y defensivos reconocibles.
- Se contemplan estadísticas como ataque, defensa, vida, probabilidad y daño crítico.
- **Simplicidad inicial:** no se introducirán por ahora múltiples tipos de daño ni resistencias particulares para cada enemigo. Los enemigos y jefes compartirán una base general de resistencia/defensa; las diferencias vendrán principalmente de sus patrones, mecánicas y comportamiento, no de exigir configuraciones de daño específicas.
- Las estadísticas deberán relacionarse de forma clara con el equipo, las pasivas y la progresión del personaje.
- **Pendiente:** definir la lista definitiva de atributos, fórmulas de daño, escalados, límites y reglas de cálculo. No se fijan cifras ni fórmulas todavía. Se podrán añadir tipos de daño o resistencias diferenciadas en el futuro si aportan una razón de diseño clara.

### Estados alterados

- **En evaluación:** se considera interesante incorporar algunos estados alterados, pero no se establecerá todavía un catálogo amplio.
- Se priorizarán pocos efectos fáciles de entender y distinguir. Su inclusión deberá aportar decisiones o variedad real, no solo más iconos y estadísticas que administrar.
- **Pendiente:** decidir qué estados concretos merecen existir, cómo se aplican, cuánto duran y cómo interactúan con enemigos y jefes.

### Tipos de enemigos, dificultad y diseño de encuentros

**Dirección acordada:** mantener una estructura sencilla y escalable para la primera versión 2D, sin cerrar la posibilidad de ampliar comportamientos y mecánicas en una futura versión 3D.

- **Enemigos normales:** su dificultad individual será baja. Deben poder derrotarse con facilidad, independientemente de que el jugador tenga una configuración optimizada o no, y sin exigir una habilidad elevada. Su función principal será dar ritmo y diversión al combate mediante encuentros con grupos. La variedad vendrá de comportamientos sencillos (por ejemplo, cuerpo a cuerpo, a distancia, ágiles o pesados), no de mecánicas complejas.
- **Enemigos especiales:** serán una amenaza mayor que los normales. Podrán destacar por golpes más fuertes, algo más de resistencia o alguna característica/mecánica sencilla. No deben convertirse en enemigos con cantidades exageradas de vida ni en pequeños jefes.
- **Repertorio de ataques:** dos o tres patrones reconocibles sirven como referencia inicial, no como cuota. Algunos especiales podrán necesitar menos; solo se añadirán ataques si aportan una diferencia clara.
- **Características distintivas:** una o dos particularidades como máximo cuando realmente aporten algo, aunque un enemigo puede funcionar perfectamente con una sola característica bien ejecutada. No necesitan combos elaborados ni mecánicas complejas.
- **Aturdimiento:** utilizarán la misma barra general de aturdimiento que los enemigos normales. Al llenarse, quedarán quietos durante el intervalo establecido; no tendrán una barra o efecto de aturdimiento exclusivo.
- **Interrupción:** podrán interrumpirse al recibir un golpe mientras preparan un ataque, siguiendo la regla general de los enemigos normales. Algunos movimientos concretos podrán tener protección contra interrupciones si necesitan completar su ejecución; no se asumirá que todos sus ataques son inmunes.
- **Jefes:** tendrán un repertorio reducido y reconocible, evitando diseñar demasiados ataques y animaciones por jefe. Como referencia inicial de trabajo, podrían tener alrededor de 3 o 4 ataques habituales y 1 o 2 movimientos especiales/distintivos. No es una cuota obligatoria: algunos jefes podrán necesitar menos. Los movimientos distintivos pueden ser golpes muy dañinos, ataques que derriben al jugador, ataques de área u otras mecánicas concretas. Se prioriza que cada movimiento tenga una función clara, no acumular cantidad.

**Comportamiento básico e interrupciones:**
- Los enemigos normales cuerpo a cuerpo seguirán una lógica sencilla: detectan al jugador, se acercan, atacan cuando están a distancia y vuelven a intentarlo. Los enemigos a distancia mantendrán una lógica equivalente adaptada a su alcance.
- El jugador podrá tomar la iniciativa: atacar, usar la habilidad o la definitiva antes de que el enemigo consiga golpearlo.
- **Interrupción de enemigos normales:** si un enemigo normal recibe un golpe mientras prepara un ataque, ese impacto podrá interrumpirlo y cancelar el ataque. No se necesita una barra ni un sistema adicional para esta reacción.
- **Jefes:** no serán interrumpidos por los golpes normales del jugador durante sus ataques. Sus movimientos deben poder ejecutarse sin que el jugador los cancele simplemente manteniendo el ataque.
- **Enemigos especiales:** pueden interrumpirse al recibir un golpe durante la preparación de un ataque, igual que los normales. Si un movimiento concreto necesita protección para funcionar correctamente, podrá indicarse expresamente; no se les concede inmunidad general.
- Esta interrupción por impacto es distinta de la barra de aturdimiento ya definida: la primera es una reacción puntual al recibir un golpe; la segunda se llena progresivamente y, al completarse, deja al enemigo quieto durante un intervalo.

**Dificultad del mundo y las zonas:**
- La exploración y progresión normal no deben depender de que cada enemigo común sea difícil.
- Se podrán diseñar determinadas áreas o encuentros especialmente difíciles, incluso opcionales o destinados a jugadores que busquen un reto mayor.
- La dificultad elevada debe concentrarse donde tenga sentido, en vez de elevar artificialmente la dificultad de todos los enemigos normales.
- No se ha definido todavía cómo se organizarán ni qué recompensas tendrán esas áreas difíciles.

**Avisos visuales de ataques:**
- Los ataques deben comunicar de forma clara qué va a hacer el enemigo y permitir reconocer si se aproxima un golpe normal o uno especial.
- Se podrán utilizar señales visuales adicionales, como un brillo, aura o cambio de color, para distinguir los ataques y advertir de los más peligrosos.
- Se contempla una opción de ajustes para desactivar esos efectos de aviso adicionales y aumentar el desafío.
- Desactivar los avisos adicionales no eliminará las animaciones propias del enemigo ni sus movimientos anticipatorios: el jugador todavía podrá leer el ataque observando su animación. La presentación exacta de las señales queda pendiente.

**Diseño de mecánicas de jefes:** se tomarán como referencia mecánicas y patrones de otros juegos, adaptándolos al combate de este proyecto. No es necesario inventarlo todo desde cero. Se conservará lo que aporte diversión y encaje con nuestras defensas y movimiento; se descartará lo que genere pausas innecesarias, persecuciones constantes o complejidad sin beneficio.

**Criterios generales:**
- Evitar jefes que se alejen constantemente y obliguen al jugador a perseguirlos más de lo que combate.
- Evitar animaciones o periodos de inactividad excesivamente largos sin una razón clara.
- No basar la dificultad únicamente en aumentar la vida o el daño del enemigo.
- Mantener oportunidades razonables para que el jugador ataque y responda.
- Las mecánicas deben ser legibles y tener una respuesta comprensible; no deben anular arbitrariamente las opciones defensivas del jugador.
- La variedad de encuentros debe surgir de combinar ataques, comportamientos y unas pocas mecánicas concretas, sin convertir a cada enemigo en un sistema complejo.

- **Pendiente:** definir el repertorio exacto de comportamientos normales, las características de los especiales, los ataques y movimientos distintivos de los jefes, las señales visuales concretas y el diseño de las zonas difíciles. Los enemigos y jefes individuales se diseñarán más adelante.

## Ciclo general de juego

**Estado: PENDIENTE — propuesta de conexión entre sistemas.**

El ciclo principal debería ser fácil de entender y repetible sin convertirse en una lista obligatoria de tareas:

1. **Explorar:** recorrer el territorio, descubrir lugares, personajes, recursos, secretos y actividades.
2. **Encontrar situaciones:** entrar en encuentros, misiones, desafíos, mazmorras o acontecimientos del mundo.
3. **Superar el contenido:** combatir, resolver una mecánica, interactuar o cumplir el objetivo correspondiente.
4. **Obtener resultados:** recibir experiencia, objetos, materiales, moneda, información o desbloqueos según la actividad.
5. **Desarrollar la configuración:** revisar equipo, esencias y pasivas; mejorar al personaje si hay una mejora útil.
6. **Continuar:** abrir nuevas zonas, afrontar contenidos más exigentes o avanzar a otra etapa del mundo.

Criterios:
- No todas las actividades deben pasar obligatoriamente por los seis pasos. Una exploración pequeña puede dar una recompensa inmediata; una misión puede enlazar varias actividades.
- No se debe obligar al jugador a volver a una base después de cada encuentro para poder seguir jugando.
- La gestión de inventario, equipo y configuración debe poder hacerse en momentos razonables y no interrumpir cada acción.
- La progresión debe combinar avance del personaje, descubrimiento del mundo y dominio del combate. Ninguno debería reducirse a repetir una única actividad.
- Este ciclo es una guía para conectar sistemas, no una estructura rígida que todas las zonas deban repetir de la misma manera.

## Interacción con el mundo

**Estado: PENDIENTE — propuesta inicial.**

Las interacciones del entorno deben ser directas y reconocibles. No todo objeto necesita un minijuego ni toda acción debe convertirse en una misión.

### Tipos de interacción
- **Acceso y mecanismos:** puertas, palancas, interruptores, mecanismos y rutas que se abren al cumplir una condición.
- **Recolección:** recursos visibles que el jugador puede recoger o activar.
- **Contenedores:** cofres, depósitos y recompensas del entorno.
- **Personajes y servicios:** hablar, aceptar o entregar misiones, comprar, vender y acceder a servicios cuando estén disponibles.
- **Elementos de descubrimiento:** lugares, señales, documentos u objetos que revelen información o registren un hallazgo.

### Criterios
- La interacción debe indicar claramente cuándo el jugador puede actuar y qué acción se espera.
- Priorizar una acción contextual sencilla antes que asignar un botón distinto a cada tipo de objeto.
- Si una interacción exige una condición —una llave, un desbloqueo, una misión o una mecánica—, comunicarla con claridad.
- No convertir cada puerta, recurso o elemento decorativo en una interacción obligatoria.
- Las interacciones importantes deben ser visibles o tener pistas razonables; evitar que el progreso dependa de probar cada objeto del escenario al azar.

**Pendiente:** alcance de las interacciones, controles, condiciones, animaciones y qué objetos pueden registrarse como descubrimientos.

## Inventario

**Estado: PENDIENTE — propuesta inicial para revisar.** Referencias principales: organización por categorías y almacenamiento de Diablo IV; separación entre bolsa del personaje y depósitos de AION 2. La propuesta se adapta a nuestro proyecto y no presupone que vayamos a reproducir la estructura de MMO de AION 2.

### Análisis y criterio de diseño

- El inventario debe permitir recoger botín y gestionar objetos sin interrumpir constantemente la exploración o el combate.
- Conviene separar visualmente los tipos de objetos mediante pestañas o categorías, en vez de mezclar equipo, consumibles, materiales y objetos de misión en una sola lista.
- Se recomienda que cada objeto ocupe un espacio uniforme, sin tamaños distintos según su forma. Esto simplifica la interfaz, la organización y la adaptación a 2D.
- Los materiales y consumibles apilables deben acumularse en una misma casilla hasta un límite por definir. El equipo y los objetos únicos ocupan espacios individuales.
- Debe existir almacenamiento aparte para guardar lo que el personaje no necesita llevar encima. No se copiarán por ahora los distintos almacenes de personaje/servidor de AION 2, porque dependen de una estructura de personajes y MMO que todavía no hemos definido.
- No se fijan todavía capacidad, cantidad de pestañas, límites de acumulación ni costes para ampliar espacios.

### Propuesta inicial

- **Bolsa del personaje:** contiene los objetos que lleva consigo y recibe el botín recogido.
- **Organización por categorías — APROBADO:**
  - **Equipo:** armas, armaduras, accesorios y demás piezas equipables.
  - **Consumibles:** pociones, alimentos y objetos de uso.
  - **Materiales:** recursos y componentes utilizados por otros sistemas.
  - **Misiones y varios:** objetos de misión y objetos que no encajen en las categorías anteriores.
- **Distribución de capacidad — APROBADO:**
  - **Equipo:** ocupa espacios individuales de la bolsa.
  - **Consumibles:** se acumulan en pilas y cada pila ocupa un espacio.
  - **Materiales:** se guardan en un registro propio y no consumen espacios de la bolsa.
  - **Objetos importantes de misión:** no consumen espacios normales de la bolsa.
  - Esta separación evita que la recolección de recursos o el avance de misiones bloqueen la capacidad para recoger equipo y consumibles.
- **Espacios uniformes:** cada objeto ocupa una casilla, independientemente de su apariencia o tamaño.
- **Acumulación:** materiales y consumibles compatibles pueden apilarse. El límite de cada pila queda pendiente.
- **Orden y búsqueda:** incluir ordenar automáticamente y filtrar por categoría o tipo. La búsqueda por nombre puede evaluarse según el tamaño final del inventario.
- **Acciones de objeto:** al seleccionar un objeto, mostrar las acciones que correspondan a su tipo, como equipar, usar o consultar información. Vender, desmontar, descartar, bloquear/favorito y otras acciones se definirán junto con los sistemas que las necesiten.
- **Almacenamiento:** depósito separado de la bolsa, accesible en lugares designados del mundo. Su capacidad, organización y posible ampliación quedan pendientes.
- **Comparación de equipo:** al seleccionar una pieza equipable, permitir compararla con la que lleva el personaje en la ranura correspondiente.
- **Protección contra errores:** evaluar una opción para marcar objetos importantes como favoritos/bloqueados, evitando venderlos o descartarlos por accidente.

### Decisiones pendientes de revisión

- **Aprobado:** cuatro categorías/pestañas: Equipo, Consumibles, Materiales y Misiones y varios.
- **Aprobado:** capacidad diferenciada: equipo ocupa espacios individuales; consumibles se apilan y ocupan espacios por pila; materiales y objetos importantes de misión quedan fuera del límite de la bolsa.
- Definir los límites de acumulación de materiales y consumibles.
- Definir el almacenamiento: capacidad, pestañas, acceso y ampliaciones.
- Decidir qué objetos de misión quedan fuera del espacio normal.
- Definir las acciones disponibles para cada tipo de objeto.
- Decidir si habrá filtros avanzados, búsqueda y marcado de favoritos/bloqueo.

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

La dirección general es diseñar el juego pensando primero en el modo Extremo. Las consecuencias concretas de morir, la recuperación y las diferencias entre modos se desarrollan en el apartado **Dificultad, muerte y guardado**, que es la referencia única para este sistema.

## Equipo, botín y personalización de objetos

**Estado: PENDIENTE — propuesta inicial completa para revisar.**

### Criterio general

El equipo debe dar progreso tangible y permitir ajustar estadísticas, pero no convertirse en una segunda progresión tan complicada que opaque las esencias y pasivas. La estructura ya acordada se conserva: las esencias definen efectos de combate, las pasivas los modifican o complementan y el equipo aporta principalmente estadísticas generales.

La referencia útil de Diablo IV es la lectura rápida de atributos, la comparación de piezas y la posibilidad de mejorar un objeto que ya interesa. De AION 2 interesa estudiar la claridad de sus ranuras, equipo y rutas de obtención, no copiar sus capas de mejora o sus exigencias de MMO.

### Ranuras propuestas

Como punto de partida sencillo, se propone:

- Arma.
- Cabeza.
- Pecho.
- Manos.
- Piernas o botas (se deberá decidir si conviene separarlas en dos ranuras).
- Dos ranuras de accesorios.

No se propone una ranura de objeto para cada parte imaginable del cuerpo. Tampoco se añade equipo secundario, talismanes, alas o piezas de apariencia con estadísticas hasta que exista una razón clara.

**Criterio:** cada ranura debe tener una función legible y aportar decisiones reales. Si separar dos piezas solo aumenta el inventario y el trabajo de balance sin ofrecer una elección interesante, se mantienen unidas.

### Estadísticas de las piezas

- Cada pieza tendrá una o varias estadísticas principales adecuadas a su tipo.
- Algunas piezas podrán incluir estadísticas secundarias para diferenciar objetos de la misma ranura.
- Se priorizarán atributos ya contemplados en el sistema general: ataque, defensa, vida, crítico, daño crítico, velocidad y recuperación, entre otros que se aprueben.
- Evitar que cada objeto tenga una lista enorme de atributos pequeños.
- No introducir resistencias elementales o defensas específicas por enemigo como requisito de equipamiento.
- El jugador deberá poder entender rápidamente si una pieza mejora daño, supervivencia o alguna característica concreta.

**Pendiente:** lista de atributos por ranura, cantidad de atributos principales/secundarios y reglas para generar sus valores.

### Rarezas y calidad

Se propone una escala corta de rarezas, inspirada en la lectura visual de los ARPG:

1. Común: pieza sencilla, útil al inicio o como material de referencia.
2. Poco común: mejores valores o una estadística secundaria.
3. Rara: combinación más interesante de atributos.
4. Especial: objeto con una propiedad distintiva o una combinación poco habitual.

Los nombres, colores y cantidad definitiva de rarezas quedan pendientes. No se recomienda crear muchas categorías que solo cambien el color y el número.

La rareza no debe ser el único criterio para elegir equipo. Una pieza de menor rareza podría seguir siendo útil si sus atributos encajan mejor con la configuración del jugador.

### Conjuntos y objetos únicos

- **Conjuntos:** no se proponen como requisito inicial. Si se incorporan, sus bonificaciones deberán ser pequeñas y no obligar a usar piezas inferiores solo para completar un conjunto.
- **Objetos únicos:** se podrán estudiar para recompensar jefes, desafíos o contenidos concretos. Deberán ofrecer una característica reconocible, no limitarse a tener números más altos.
- No se crearán bonificaciones de conjunto o efectos únicos para cada esencia o combinación. Eso multiplicaría innecesariamente el trabajo de diseño y balance.

### Comparación y gestión

- Al seleccionar una pieza, mostrar la comparación directa con el objeto equipado en esa ranura.
- La comparación debe presentar claramente qué estadísticas suben y cuáles bajan.
- Se propone permitir bloquear o marcar como favorito un objeto para evitar venderlo, desmontarlo o descartarlo por error.
- Se propone marcar como basura los objetos que el jugador ya decidió procesar, si posteriormente existe venta o desmontaje por lote.
- Los objetos equipados no deberían poder descartarse accidentalmente mediante una acción rápida.

### Conjuntos de equipo / configuraciones

Se propone permitir guardar varias configuraciones del personaje. Cada configuración podría recordar:

- Las tres esencias seleccionadas y cuál es la principal visual.
- Las pasivas equipadas.
- El equipo utilizado.
- La pieza especial, si se conserva ese sistema.

La intención es facilitar probar estilos distintos sin tener que reconstruir manualmente la configuración cada vez.

**Límite recomendado:** comenzar con una cantidad pequeña de espacios guardados y ampliarla solo si el juego realmente lo necesita. No copiar de entrada la cantidad de presets de un MMO.

**Pendiente:** número de configuraciones, si se puede cambiar en cualquier momento o solo fuera de combate, y qué elementos recuerda cada una.

## Botín y obtención de objetos

**Estado: PENDIENTE — propuesta inicial.**

### Fuentes de botín

Se propone que los objetos y recursos se obtengan principalmente mediante:

- Derrotar enemigos y jefes.
- Abrir cofres y descubrir secretos.
- Completar misiones y actividades.
- Superar mazmorras y desafíos.
- Recompensas de exploración y logros concretos.
- Comerciantes o fabricación, si esos sistemas se aprueban.

Cada fuente debe tener una razón de existir. No todos los enemigos necesitan soltar equipo; los enemigos normales pueden entregar principalmente experiencia, moneda y materiales comunes, mientras que los especiales, jefes y actividades importantes pueden tener mejores posibilidades de dar equipo.

### Recompensas dirigidas

Se recomienda que los contenidos importantes tengan recompensas reconocibles. Por ejemplo, un jefe o desafío podría entregar una pieza especial, un material concreto o una recompensa seleccionable.

La aleatoriedad puede aportar variedad, pero no debería obligar a repetir indefinidamente un encuentro para conseguir una pieza básica necesaria para progresar.

### Recompensas repetidas

- Evitar que el jugador reciba constantemente objetos inútiles que solo llenen el inventario.
- Las piezas que ya no sirven podrán venderse, desmontarse o convertirse en materiales, si se aprueban esas acciones.
- Los duplicados de objetos especiales deberán tener una utilidad definida; no se debe permitir que se acumulen sin propósito.
- No se propone por ahora un sistema complejo de intercambio entre jugadores.

### Nivel y escalado del botín

Se propone que las recompensas correspondan razonablemente al tramo de progresión del personaje y al desafío superado. No se recomienda que todos los objetos del mundo escalen automáticamente al nivel del jugador, porque eso puede hacer que la exploración y los territorios pierdan identidad.

**Pendiente:** reglas de nivel de objeto, probabilidades, tablas de botín, recompensas garantizadas, duplicados y relación entre nivel del personaje y equipo.

## Mejoras de equipo

**Estado: PENDIENTE — propuesta inicial.**

Se propone un sistema de mejora directo y comprensible:

- Mejorar una pieza aumenta sus estadísticas de forma controlada.
- La mejora consume moneda y/o materiales obtenidos jugando.
- La mejora no debería destruir el objeto ni reducir su nivel por fallar.
- Evitar probabilidades de éxito, degradación, protección contra fallos y múltiples tipos de piedras en la primera versión.
- Debe existir un límite razonable de mejora para que el equipo no se convierta en una progresión infinita difícil de equilibrar.
- El jugador debe poder reconocer cuánto mejorará una pieza antes de confirmar el gasto.

Se recomienda separar tres operaciones que no deben confundirse:

1. **Mejorar:** aumentar los valores de una pieza.
2. **Modificar:** cambiar una estadística o propiedad, si se incorpora esa opción.
3. **Fabricar:** crear un objeto a partir de recursos, si se incorpora la fabricación.

No se recomienda copiar de entrada el número de capas de templado, masterworking, rerolls, extracción y transferencia de Diablo IV. Primero debe funcionar bien la progresión básica.

**Pendiente:** límite de mejora, costes, materiales, posibilidad de reiniciar mejoras y si realmente hace falta modificar atributos.

## Materiales, recolección y fabricación

**Estado: PENDIENTE — propuesta inicial.**

### Recolección

Se propone que los recursos aparezcan de forma natural en los territorios y puedan obtenerse explorando, interactuando con puntos de recolección o derrotando determinados enemigos.

- Los recursos deben tener usos reconocibles.
- No llenar el mundo de docenas de materiales que solo cambian de nombre.
- Los puntos de recolección pueden registrarse en el mapa si forman parte del porcentaje normal de exploración.
- No se propone energía, resistencia ni límites diarios para recolectar.
- Evitar que el jugador tenga que recorrer repetidamente una ruta vacía esperando que reaparezcan recursos.

### Fabricación

Se propone empezar con una fabricación limitada a objetos útiles y comprensibles:

- Consumibles básicos.
- Materiales procesados necesarios para mejoras.
- Algunas piezas de equipo o recompensas especiales, solo si aportan una ruta alternativa de obtención.

No se propone inicialmente un sistema de profesiones múltiples con niveles independientes, recetas interminables y especializaciones. Eso sería mucho trabajo y podría convertir la fabricación en un juego separado.

### Recetas

- Las recetas importantes se desbloquean mediante exploración, misiones, jefes o progresión.
- Una receta desbloqueada debería permanecer disponible.
- Mostrar materiales requeridos y dónde se pueden conseguir, al menos mediante una referencia general.
- Evitar recetas que exijan una cadena larga de materiales raros sin una recompensa proporcional.

**Pendiente:** si habrá fabricación, qué objetos permite crear, cómo se consiguen recetas y cuántos materiales distintos necesita el juego.

## Monedas y economía

**Estado: PENDIENTE — propuesta inicial.**

Se recomienda una economía pequeña, evitando muchas monedas que solo sirven para una tienda concreta.

### Monedas propuestas

- **Moneda común:** se obtiene jugando y se utiliza para servicios habituales, como comprar consumibles, vender objetos o pagar mejoras sencillas.
- **Materiales de progresión:** recursos específicos para operaciones concretas, obtenidos de contenidos relacionados con su uso.
- No crear una moneda diferente para cada territorio, jefe o actividad salvo que exista una función realmente distinta.

### Comerciantes y servicios

Se propone que existan puntos o personajes de servicio en lugares seguros del mundo, con funciones claras:

- Comprar consumibles y objetos básicos.
- Vender objetos que el jugador ya no necesita.
- Mejorar equipo, si se aprueba ese sistema.
- Fabricar objetos, si se aprueba la fabricación.
- Acceder al almacenamiento.

No es necesario que cada servicio tenga un NPC distinto. Se pueden agrupar funciones en una misma ubicación o interfaz para evitar viajes innecesarios.

### Criterios económicos

- Los precios deben tener una escala coherente con las recompensas.
- No utilizar costes de reparación o mantenimiento como impuesto constante al jugador, salvo que se demuestre que aportan algo.
- No introducir comercio entre jugadores ni una casa de subastas por defecto. Son sistemas ligados a economías multijugador y no se ha decidido que el juego sea un MMO.
- Evitar que la moneda común pierda utilidad demasiado pronto o que se acumule sin ningún uso.

**Pendiente:** nombre de la moneda, fuentes, gastos, servicios, posibilidad de venta y si habrá más de una moneda.

## Misiones y objetivos

**Estado: PENDIENTE — propuesta inicial.**

Se propone una estructura de misiones sencilla, con objetivos claros y seguimiento desde un registro:

### Tipos de misión

- **Principal:** conduce la historia y el avance entre etapas, territorios o mundos.
- **Secundaria:** desarrolla personajes, lugares, conflictos y acontecimientos locales; puede ofrecer recompensas útiles.
- **Actividad o desafío:** propone una prueba concreta de combate, exploración o interacción.
- **Descubrimiento:** se activa al encontrar un lugar, objeto, personaje o situación relevante.

No todas las interacciones del mundo tienen que convertirse en una misión formal. Algunas pueden resolverse directamente mediante exploración.

### Diseño de objetivos

- Evitar objetivos de relleno como derrotar cantidades arbitrarias de enemigos sin contexto.
- Cuando una misión pide combatir, explorar o conseguir algo, debe existir una razón dentro de la situación.
- Los objetivos deben ser claros y el registro debe indicar qué falta.
- Las misiones secundarias no deberían bloquear el avance principal salvo que exista una justificación narrativa importante.
- No se propone un sistema de encargos diarios obligatorios.

### Seguimiento y recompensas

- Un diario o registro reúne misiones activas, completadas y descubrimientos relevantes.
- La recompensa debe mostrarse antes de aceptar o completar cuando sea posible.
- Las recompensas pueden incluir experiencia, moneda, equipo, materiales, desbloqueos o información del mundo.
- Las misiones no deben ser la única fuente de progresión para cada sistema.

**Pendiente:** estructura exacta del diario, límites de misiones activas, marcadores, seguimiento en pantalla, decisiones narrativas y recompensas.

## Actividades, mazmorras y contenido repetible

**Estado: PENDIENTE — propuesta inicial.**

Se propone organizar el contenido en actividades reconocibles, sin convertir todas las zonas en listas de tareas repetitivas.

### Tipos de contenido

- **Mazmorras:** espacios delimitados con encuentros y un objetivo final. Pueden incluir un jefe, una secuencia de combate o una prueba ambiental.
- **Jefes de territorio:** encuentros importantes ligados a la exploración, historia o progresión.
- **Desafíos opcionales:** pruebas de dificultad elegible, como las áreas de tres niveles que ya se están considerando.
- **Eventos locales:** situaciones que aparecen en el territorio y ofrecen una actividad breve.
- **Secretos y exploración:** contenido opcional que recompensa observar y descubrir.
- **Encuentros especiales:** combates o situaciones únicas que no necesitan convertirse en una mazmorra completa.

### Repetición

- El contenido repetible debe tener una recompensa útil o una razón de dominio personal.
- No se recomienda obligar a repetir una mazmorra decenas de veces para conseguir un desbloqueo básico.
- Se puede permitir repetir jefes y desafíos para conseguir recursos o mejorar resultados, pero el progreso principal no debe depender de una probabilidad extremadamente baja.
- Evitar energía, tickets diarios o límites artificiales de intentos.

### Dificultad

Los desafíos de mayor dificultad deben exigir aprender patrones y responder mejor, no únicamente soportar más vida enemiga. Esta regla coincide con la dirección de combate ya acordada.

**Pendiente:** qué actividades se repiten, cómo se reinician, sus recompensas, duración objetivo y si existen variantes de dificultad.

## Mapa, territorios y desplazamiento

**Estado: PENDIENTE — propuesta inicial, compatible con el registro de exploración ya planteado.**

### Mapa

Se propone que el mapa permita:

- Ver el territorio actual y sus zonas descubiertas.
- Consultar puntos de interés, actividades y lugares importantes.
- Revisar el registro de exploración y sus categorías.
- Consultar secretos mediante pistas aproximadas, sin revelar su ubicación exacta.
- Identificar lugares seguros, servicios y puntos de desplazamiento cuando se desbloqueen.

No se recomienda llenar el mapa con iconos de cada objeto menor. Los marcadores deben ayudar a orientarse, no sustituir la exploración.

### Desplazamiento rápido

Se propone desbloquear puntos de viaje rápido al descubrir o activar lugares importantes del territorio.

- El viaje rápido debería estar disponible desde el mapa cuando el jugador no esté en combate ni dentro de una situación que lo impida.
- No consumir moneda ni materiales por cada viaje.
- Los puntos deben ubicarse de forma que reduzcan recorridos tediosos sin eliminar la necesidad de explorar.
- El jugador debe poder volver a territorios anteriores cuando el contenido lo permita.

### Estructura del mundo

La dirección narrativa ya contempla avanzar por distintas etapas, mundos o territorios y pasar al siguiente cuando el actual deje de representar el desafío adecuado. El sistema de mapa debe permitir esa progresión sin convertir el regreso en una carga.

**Pendiente:** estructura de mapas, puntos de viaje, condiciones de regreso, selección de territorio y relación entre mapa y registro.

## Dificultad, muerte y guardado

**Estado: PENDIENTE — propuesta inicial que desarrolla la dirección de dificultad ya conversada.**

### Modos de dificultad

- Se mantiene como objetivo de diseño que el juego pueda funcionar en Extremo.
- Los modos de dificultad deberían cambiar principalmente las consecuencias y exigencia del juego, no obligar a duplicar todos los contenidos.
- La dificultad normal debe permitir aprender sistemas y patrones sin que cada enemigo común se convierta en una amenaza excesiva.
- Los retos opcionales pueden superar la dificultad habitual del territorio.

### Muerte

La posible pérdida de pasivas u otros avances al morir se ha mencionado como idea, pero no está aprobada. Se propone evaluar primero estas alternativas:

1. **Consecuencia ligera:** reaparecer en un punto seguro y conservar el progreso, con una penalización limitada.
2. **Consecuencia intermedia:** perder temporalmente algún recurso recuperable, sin perder desbloqueos permanentes.
3. **Consecuencia extrema:** aplicar una pérdida más importante solo en el modo Extremo, con reglas explicadas antes de comenzar.

No se recomienda que la muerte borre desbloqueos permanentes de esencias o pasivas que el jugador ya consiguió. Eso chocaría con la decisión previa de que los desbloqueos son permanentes y haría que probar configuraciones resultara frustrante.

Si el modo Extremo contempla pérdida de progreso, deberá especificarse qué se pierde, qué se conserva y cómo se recupera. No debe quedar a interpretación.

### Guardado

Se propone:

- Guardado automático en hitos razonables: cambios de zona, desbloqueos, recompensas importantes y puntos seguros.
- Guardado manual desde lugares seguros o desde el menú, si la estructura técnica lo permite.
- Registrar configuración, inventario, progreso de misiones, exploración, desbloqueos y estado de actividades.
- Evitar que el jugador pierda progreso importante por cerrar el juego después de una recompensa.

**Pendiente:** puntos de guardado, frecuencia, ranuras de partida, guardado manual, consecuencias por modo y reglas definitivas de muerte.

## Interfaz, información y accesibilidad

**Estado: PENDIENTE — propuesta inicial.**

La interfaz debe mostrar información útil sin llenar la pantalla de barras, números e iconos.

### Información durante el combate

Se propone mostrar solo lo necesario:

- Vida del personaje.
- Barra de aturdimiento del enemigo cuando sea relevante.
- Enfriamiento o disponibilidad de habilidad y definitiva.
- Señales visuales de ataques enemigos, respetando la opción ya planteada para desactivar avisos adicionales.
- Información de estado alterado solo si finalmente se aprueba un catálogo de estados.

No se propone mostrar permanentemente todas las estadísticas del personaje durante el combate.

### Menús

Se propone separar las pantallas principales por función:

- Personaje: estadísticas generales y equipo.
- Esencias: selección de tres y esencia principal visual.
- Pasivas: selección y desarrollo.
- Inventario: objetos y materiales.
- Mapa y exploración.
- Misiones y registro.
- Opciones.

Se podrán agrupar pantallas relacionadas si la interfaz final lo hace más cómoda. La lista no obliga a crear un menú independiente para cada sistema.

### Accesibilidad y ajustes

Se propone considerar:

- Ajuste de tamaño de texto e interfaz.
- Volumen independiente para música, efectos y ambiente.
- Reasignación de controles cuando la plataforma lo permita.
- Opciones para reducir destellos, sacudidas de cámara y efectos visuales intensos.
- Opción de desactivar señales visuales adicionales de ataques, ya contemplada en el diseño de combate.
- Indicadores visuales y sonoros que no dependan exclusivamente de distinguir colores.

**Pendiente:** diseño visual, distribución, controles, opciones de accesibilidad y cantidad de información en pantalla.

## Contenido cosmético y apariencia

**Estado: PENDIENTE — propuesta inicial.**

Se propone separar la apariencia del personaje de sus estadísticas:

- Si se incorporan piezas cosméticas, cambiarán la apariencia sin alterar el poder.
- La esencia principal visual ya tiene una función de presentación: determinar la manifestación visual de los ataques sin dar ventajas mecánicas.
- No se propone que conseguir una apariencia sea requisito para progresar.
- Se podrá evaluar un sistema de guardar apariencias o combinaciones visuales, pero no hace falta diseñarlo antes de que exista suficiente contenido cosmético.

**Pendiente:** personalización inicial, apariencias desbloqueables, transfiguración, tintes y relación entre cosméticos y equipo.

## Sistemas que no se incorporan por defecto

**Estado: PENDIENTE — criterio de alcance recomendado.**

Para evitar que el proyecto se convierta en un MMO por acumulación de sistemas, no se consideran parte de la base hasta que exista una razón clara:

- Comercio entre jugadores y casa de subastas.
- Clanes, gremios y jerarquías sociales.
- Mercado controlado por jugadores.
- Energía o resistencia diaria para limitar actividades.
- Pase de batalla, recompensas por asistencia diaria y tareas de inicio de sesión.
- Múltiples monedas para cada actividad.
- Profesiones complejas con progresión independiente.
- Sistemas de mejora con fallos, destrucción o degradación del equipo.
- Múltiples personajes jugables con progresión y almacenamiento compartidos.

Esto no significa que estén prohibidos para siempre. Significa que no se añadirán solo porque existan en AION 2 u otros juegos. Primero debe estar justificada su función dentro de nuestro proyecto.

## Auditoría de coherencia entre sistemas

**Estado: criterio de diseño propuesto; se utiliza para detectar contradicciones antes de aprobar cada sistema.**

Estas reglas sirven para que las decisiones de un apartado no rompan las de otro:

1. **Desbloqueos permanentes frente a muerte:** morir no debe borrar esencias o pasivas ya desbloqueadas. Cualquier penalización extrema debe afectar, si se aprueba, a recursos o progreso recuperable claramente delimitados.
2. **Inventario frente a botín y recolección:** los objetos obtenidos deben tener una categoría y un uso identificables. No se deben crear materiales sin una función prevista ni recompensas que llenen la bolsa sin aportar valor.
3. **Equipo frente a esencias y pasivas:** el equipo aporta principalmente estadísticas generales; no debe exigir una combinación concreta de esencias para funcionar ni duplicar todos sus efectos.
4. **Mejoras frente a economía:** cada coste debe tener una fuente y un uso comprensible. No se añadirán monedas o materiales exclusivos solo para justificar una operación.
5. **Exploración frente a misiones:** el registro puede ayudar a completar el territorio, pero no debe convertir cada descubrimiento en una misión ni exigir el 100% para avanzar.
6. **Actividades repetibles frente a progresión:** repetir contenido puede ofrecer recursos o recompensas adicionales, pero los desbloqueos fundamentales no deben depender de una probabilidad extremadamente baja o de intentos diarios obligatorios.
7. **Dificultad frente a combate:** aumentar la dificultad debe exigir mejores decisiones y lectura de patrones, no contradecir las defensas ya definidas ni convertir a los enemigos comunes en esponjas de vida.
8. **Interfaz frente a complejidad:** cada indicador, pestaña, atributo o menú debe resolver una necesidad real. Si dos elementos cumplen la misma función, se priorizará unificarlos.
9. **Guardado frente a recompensas:** los desbloqueos y recompensas importantes deben persistir en hitos razonables para evitar pérdidas accidentales.
10. **Alcance del proyecto:** ninguna referencia a AION 2 o Diablo IV justifica incorporar automáticamente funciones multijugador, economía de MMO o capas de progresión que no necesita nuestro juego.

Antes de aprobar un sistema se comprobará su compatibilidad con estas reglas y con las decisiones ya confirmadas. Si aparece un conflicto, se corregirá la propuesta nueva antes de alterar una decisión aprobada.

## Orden propuesto para revisar los pendientes

**Estado: PENDIENTE — planificación de revisión, no aprobación de los sistemas.**

Para que la revisión sea ordenada y las decisiones de un sistema no contradigan otro, se propone este orden:

1. Inventario y almacenamiento: categorías, capacidad y organización.
2. Equipo: ranuras, estadísticas, rarezas y objetos especiales.
3. Botín: fuentes, recompensas y duplicados.
4. Mejoras de equipo: costes, límites y operaciones.
5. Materiales y fabricación: recolección, recetas y utilidad.
6. Monedas y comerciantes: economía y servicios.
7. Misiones y registro: tipos, seguimiento y recompensas.
8. Actividades y mazmorras: contenido repetible y desafíos.
9. Mapa y desplazamiento: territorios, viaje rápido y regreso.
10. Dificultad, muerte y guardado.
11. Interfaz y accesibilidad.
12. Cosméticos y apariencia.
13. Revisión final de sistemas excluidos o que merezcan reconsiderarse.

Este orden es una guía de trabajo. Si una decisión depende de otra, se podrá ajustar el orden sin aprobar automáticamente ninguna propuesta.

## Elementos aplazados para una fase posterior

Los siguientes detalles no necesitan resolverse durante la revisión de los sistemas generales. Se abordarán cuando exista suficiente contexto de contenido o producción:

- Diseño individual de personajes, enemigos, jefes, misiones y territorios.
- Catálogo definitivo de objetos, recetas, consumibles, recompensas y apariencias.
- Valores numéricos, probabilidades, fórmulas, costes y balance.
- Diseño visual final de menús, HUD, iconos, efectos, animaciones y controles.
- Implementación técnica, arquitectura, rendimiento y adaptación de 2D a una posible versión 3D.

Aplazar estos detalles no significa olvidarlos ni aprobarlos por adelantado. Se definirán cuando los sistemas generales que los condicionan estén revisados.
