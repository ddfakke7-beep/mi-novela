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

**Estado: APROBADO — sistema general y decisiones revisadas.** Referencias principales: organización por categorías y almacenamiento de Diablo IV; separación entre bolsa del personaje y depósitos de AION 2. La propuesta se adapta a nuestro proyecto y no presupone que vayamos a reproducir la estructura de MMO de AION 2.

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
- **Espacios uniformes — APROBADO:** cada objeto ocupa una casilla, independientemente de su apariencia o tamaño.
- **Capacidad de la bolsa — APROBADO:** 100 espacios iniciales para equipo y consumibles; el equipo ocupa un espacio individual y los consumibles compatibles se acumulan por pilas. El límite inicial propuesto es de 99 unidades por pila.
- **Materiales — APROBADO:** registro independiente sin consumir espacios de la bolsa.
- **Objetos importantes de misión — APROBADO:** se almacenan aparte y no consumen espacios normales.
- **Almacenamiento — APROBADO:** depósito independiente para equipo y consumibles, accesible en lugares seguros o puntos de servicio. No tendrá ampliaciones inicialmente.
- **Organización — APROBADO:** orden automático por tipo, rareza y nivel; filtros por categoría y tipo. Búsqueda por nombre si el volumen de objetos lo justifica.
- **Acciones — APROBADO:** equipar, desequipar, usar, vender, descartar y consultar información, según el tipo de objeto.
- **Comparación de equipo — APROBADO:** mostrar las diferencias de estadísticas entre una pieza seleccionada y la equipada.
- **Protección — APROBADO:** favoritos/bloqueo para evitar vender o descartar objetos importantes; los objetos equipados no podrán descartarse accidentalmente.
- **Desmontaje — NO incluido inicialmente:** solo se reconsiderará si el sistema de mejoras demuestra que lo necesita.

### Decisiones cerradas

El inventario queda aprobado en su estructura y funcionamiento general. Los valores numéricos concretos podrán ajustarse durante el balance o si las pruebas de contenido demuestran que 100 espacios o pilas de 99 unidades no funcionan bien; no se consideran una nueva capa de progresión ni un motivo para detener la revisión de sistemas.

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

**Estado: APROBADO.** El equipamiento normal ofrece progresión mediante estadísticas generales, sin exigir conjuntos distintos para cada combinación de esencias. La pieza especial ocupa una ranura independiente y complementa la configuración.

### Ranuras de equipo

El personaje tendrá **siete ranuras de equipo normal**:

1. Arma.
2. Cabeza.
3. Pecho.
4. Manos.
5. Piernas y botas (una sola ranura).
6. Accesorio 1.
7. Accesorio 2.

Las piernas y las botas se agrupan para evitar dividir el equipo en demasiadas piezas. Los dos espacios de accesorios permiten cierta variedad sin multiplicar ranuras innecesariamente.

### Estadísticas

El equipo utilizará cinco estadísticas generales como base:

- Ataque.
- Defensa.
- Vida.
- Probabilidad de crítico.
- Daño crítico.

No se incorporan por ahora resistencias elementales, resistencias específicas contra enemigos ni otras capas de estadísticas. Se prioriza que las piezas sean fáciles de comparar y que funcionen con distintas configuraciones de esencias.

### Rarezas

Se establecen cuatro rarezas:

- **Común:** equipo básico, con valores sencillos.
- **Poco común:** mejores valores o alguna estadística adicional.
- **Raro:** combinaciones de estadísticas más interesantes.
- **Único:** pieza con una propiedad distintiva diseñada para ella.

La rareza orienta sobre el tipo de pieza, pero no garantiza que cualquier objeto de mayor rareza sea automáticamente mejor para todas las configuraciones. La utilidad depende de sus estadísticas y propiedades.

### Conjuntos y objetos únicos

- No habrá bonificaciones de conjunto en la primera versión del sistema.
- Sí podrán existir objetos únicos, obtenidos de jefes, desafíos u otras actividades relevantes.
- Cada objeto único podrá tener una propiedad especial reconocible, en lugar de limitarse a ofrecer números más altos.
- Los objetos únicos no estarán ligados obligatoriamente a una esencia concreta ni exigirán conseguir una pieza diferente para cada configuración.

### Comparación y protección de objetos

- Al seleccionar una pieza nueva, la interfaz la comparará con la pieza equipada en esa ranura y mostrará claramente los aumentos y reducciones de estadísticas.
- El jugador podrá marcar objetos como favoritos o bloquearlos para protegerlos.
- Los objetos equipados estarán protegidos contra el descarte accidental.
- Se podrá marcar equipo como basura para facilitar su gestión posterior en lote, si la operación correspondiente está disponible.

### Configuraciones guardadas

Se podrán guardar **tres configuraciones** inicialmente. Cada una recordará:

- Las tres esencias seleccionadas.
- La esencia principal visual.
- Las pasivas configuradas.
- El equipo normal de las siete ranuras.
- La pieza especial equipada.

Cambiar entre configuraciones estará permitido fuera del combate, pero no durante un combate. La cantidad inicial de tres espacios podrá revisarse durante pruebas si resulta insuficiente o excesiva.

### Pieza especial

Además de las siete ranuras normales, habrá **una ranura independiente para una pieza especial**.

- La pieza ofrecerá una mejora concreta y significativa, sin convertirse en otra capa de bonificaciones indiscriminadas.
- Podrá utilizarse con distintas configuraciones; no será necesario conseguir una pieza diferente para cada build.
- Podrá mejorarse mediante la progresión del personaje.
- Su función será distinta de las pasivas y del equipo normal: aportará un modificador particular, mientras el equipo normal proporciona estadísticas generales y las pasivas complementan los efectos de combate.

La variedad exacta de piezas, sus propiedades y los niveles de mejora se definirán al desarrollar el contenido y el sistema de mejoras.

### Criterios de equilibrio

- El equipo no debe invalidar las esencias ni las pasivas.
- No habrá afinidades obligatorias que hagan inservible una pieza al cambiar de configuración.
- No se incorporan conjuntos en la primera versión.
- Se priorizan estadísticas y propiedades fáciles de entender y comparar.
- Los valores numéricos y el balance se definirán más adelante.


## Botín y obtención de objetos

**Estado: APROBADO.** El botín procede de enemigos, jefes, cofres, misiones, actividades y exploración. Se combina una base de recompensas garantizadas con recompensas aleatorias complementarias. Los objetos importantes deben poder perseguirse mediante fuentes identificables, sin depender exclusivamente de probabilidades bajas.

### Fuentes de botín

- **Enemigos normales:** principalmente experiencia, moneda y materiales comunes. Ocasionalmente podrán entregar consumibles.
- **Enemigos especiales:** podrán entregar lo anterior y también equipo.
- **Jefes:** podrán entregar equipo, objetos únicos, materiales especiales y recompensas propias.
- **Cofres normales:** moneda, consumibles, materiales y, ocasionalmente, equipo.
- **Cofres ocultos:** recompensas mejores o adicionales respecto a los cofres normales.
- **Mazmorras y desafíos:** equipo, materiales y recompensas específicas de la actividad.
- **Misiones:** recompensas seleccionadas según la importancia de la misión.
- **Exploración y logros:** recompensas por descubrimientos y objetivos concretos.

No todos los enemigos necesitan soltar equipo. Se evita que cada combate llene el inventario de piezas sin valor.

### Recompensas garantizadas y aleatorias

El sistema combinará ambos métodos:

- Los contenidos importantes entregarán una recompensa útil y definida al completarlos por primera vez.
- Las recompensas aleatorias podrán aparecer como complemento y aportar variedad.
- Determinados jefes, desafíos o actividades tendrán objetos asociados que el jugador podrá perseguir.
- Ningún desbloqueo importante dependerá exclusivamente de una probabilidad baja.

Por ejemplo, derrotar a un jefe importante podrá garantizar una recompensa propia, mientras que conseguir piezas adicionales de su tabla de botín podrá depender de una probabilidad.

### Botín de jefes y objetos únicos

- Cada jefe importante tendrá una recompensa característica.
- Algunos jefes podrán entregar objetos únicos diseñados específicamente para ellos.
- Otros podrán entregar materiales necesarios para progresión o mejoras.
- La primera derrota garantizará una recompensa importante.
- Al repetir el combate se podrán conseguir recompensas adicionales, sin tener que volver a desbloquear lo que ya se consiguió.

Los objetos únicos tendrán fuentes identificables para que el jugador sepa qué contenido debe completar para intentar conseguirlos.

### Duplicados y recuperación de objetos únicos

- El equipo repetido podrá venderse o descartarse.
- No se entregarán duplicados inútiles de objetos únicos que el jugador ya posea.
- **La posesión actual determina si el jugador puede volver a obtener un objeto único; el historial de adquisición no lo bloquea.**
- Si el jugador vende o descarta un objeto único, podrá volver a conseguirlo mediante su fuente original.
- Si el objeto está en el almacenamiento o equipado en otra configuración, cuenta como poseído y no se entregará otro duplicado.
- Si el juego permite perder un objeto por alguna mecánica, deberá existir una forma de recuperarlo.
- No se incorpora desmontaje de equipo inicialmente.

La compensación concreta por recompensas repetidas que deban sustituirse se definirá junto con la economía y los materiales.

### Nivel y progresión del botín

- El equipo estará relacionado con la progresión de los territorios, no con un escalado automático de todo el mundo al nivel del jugador.
- Cada territorio o etapa tendrá un rango de progresión esperado.
- Los territorios posteriores ofrecerán equipo generalmente más potente.
- Los enemigos y cofres de zonas anteriores conservarán sus recompensas originales.
- El jugador podrá regresar a zonas anteriores y seguir encontrando sus recompensas, aunque ya no sean las más poderosas.

### Aleatoriedad del equipo

Inicialmente, las piezas tendrán estadísticas y propiedades definidas, en lugar de generar estadísticas aleatorias en cada caída.

- Una pieza concreta conservará su identidad y sus estadísticas.
- No habrá tiradas aleatorias de atributos en cada copia como sistema base.
- La variedad vendrá de las distintas piezas, sus estadísticas, las rarezas aprobadas, las propiedades de los objetos únicos y las fuentes de cada actividad.

Esto reduce el trabajo de balance y evita convertir el juego en una búsqueda interminable de la misma pieza con mejores números.

### Repetición de contenido

- Se podrá repetir contenido para conseguir recompensas adicionales.
- No habrá energía ni intentos diarios obligatorios.
- No se utilizarán probabilidades absurdamente bajas para objetos importantes.
- No se obligará a repetir contenido fácil durante horas para conseguir materiales básicos.
- La primera finalización podrá ofrecer recompensas especiales que no se repitan.
- Las actividades repetibles deberán ofrecer recompensas útiles, no solamente experiencia cuando el personaje ya no la necesita.

### Información sobre las recompensas

En los contenidos importantes se podrá consultar:

- Recompensas garantizadas.
- Recompensas posibles.
- Objetos únicos asociados a ese jefe o actividad.
- Si una recompensa importante ya fue obtenida y si el jugador todavía posee el objeto correspondiente.

No es necesario revelar todos los secretos del juego. Las recompensas ocultas podrán seguir siendo descubrimientos.

### Criterios generales

- Jugar y explorar debe ofrecer recompensas útiles.
- El jugador debe poder perseguir objetivos concretos y conseguirlos mediante un esfuerzo razonable.
- La aleatoriedad complementa la progresión, pero no debe controlar el acceso a desbloqueos fundamentales.
- Las recompensas deben tener una utilidad clara y no llenar el inventario con objetos innecesarios.
- Los valores, probabilidades y tablas concretas se definirán durante el desarrollo y el balance.


## Mejoras de equipo

**Estado: APROBADO.** El equipo podrá mejorarse individualmente mediante un sistema directo, predecible y sin probabilidades de fallo. La mejora aumentará las estadísticas de la pieza y tendrá un límite para evitar una progresión infinita.

### Niveles de mejora

- Cada pieza de equipo podrá mejorarse individualmente.
- Cada mejora aumentará sus estadísticas principales de forma predecible.
- El jugador podrá consultar el resultado antes de confirmar.
- Se establece un límite inicial de **+10 por pieza**.
- Las mejoras no cambiarán las propiedades especiales ni la identidad de la pieza.

### Costes y materiales

- Mejorar equipo consumirá **moneda común** y **materiales de mejora**.
- Se utilizará un tipo general de material de mejora, sin crear materiales distintos para cada ranura o tipo de equipo.
- Los materiales podrán obtenerse principalmente de enemigos especiales, jefes, desafíos y actividades.
- Los territorios más avanzados podrán proporcionar mejores materiales o mayores cantidades.
- Los costes aumentarán progresivamente: bajos en los primeros niveles, medios en los intermedios y altos en los últimos, pero siempre razonables.
- Las cantidades concretas y la curva de costes se definirán durante el balance.

### Éxito y penalizaciones

- Todas las mejoras tendrán éxito garantizado.
- No habrá probabilidades de fallo.
- El equipo no podrá destruirse, degradarse ni perder niveles al mejorarlo.
- No habrá costes de reparación asociados a las mejoras.

### Reinicio de mejoras

- El jugador podrá reiniciar las mejoras de una pieza.
- El reinicio será gratuito.
- Se devolverá el **100 % de la moneda y los materiales invertidos** en sus mejoras.
- La pieza regresará a su nivel de mejora original, pero conservará sus estadísticas base y propiedades especiales.

Esto permite cambiar de equipo y experimentar sin castigar al jugador por los recursos invertidos anteriormente.

### Modificación de estadísticas

Inicialmente no se incorporará un sistema para modificar o volver a generar las estadísticas de las piezas.

- No habrá rerolls de atributos.
- No se podrán transferir propiedades entre piezas.
- No se extraerán estadísticas ni mejoras.
- Si una pieza no tiene las estadísticas deseadas, el jugador podrá buscar otra que se ajuste mejor.

Estas operaciones podrán reconsiderarse más adelante solo si aparece una necesidad clara.

### Objetos únicos y pieza especial

- Los objetos únicos que formen parte del equipo normal utilizarán el mismo sistema de mejora que las demás piezas.
- Conservarán su propiedad distintiva al mejorarse.
- No necesitarán materiales ni reglas de mejora exclusivas.
- La pieza especial tendrá una progresión independiente, que se definirá al desarrollar ese sistema.

### Interfaz de mejora

La interfaz permitirá:

- Seleccionar una pieza.
- Consultar su nivel de mejora actual.
- Comparar las estadísticas actuales con las que tendrá después de mejorarla.
- Consultar la moneda y los materiales necesarios.
- Confirmar la mejora.
- Reiniciar las mejoras y recuperar todos los recursos invertidos.

### Criterios generales

- Mejorar equipo debe potenciar una pieza que el jugador quiera conservar, no convertirse en una apuesta.
- Los costes y aumentos deben ser claros antes de confirmar cualquier operación.
- Se prioriza un sistema sencillo, reutilizable y fácil de equilibrar.
- El límite, las cantidades, los valores de aumento y la curva de costes podrán ajustarse durante el balance sin cambiar las reglas generales aprobadas.

## Materiales, recolección y fabricación

**Estado: APROBADO.** Sistema deliberadamente sencillo: los materiales sirven para mejorar equipo y fabricar algunos objetos útiles, sin convertir la recolección o la fabricación en una progresión paralela.

### Tipos de materiales

Se utilizarán tres categorías generales:

- **Comunes:** recursos habituales para consumibles y objetos básicos.
- **Especiales:** materiales menos frecuentes para mejoras y recetas de mayor importancia.
- **Únicos:** materiales concretos vinculados a recetas especiales o recompensas de jefes y actividades.

La cantidad total de materiales se mantendrá controlada. Cada material debe tener una utilidad reconocible; no se crearán recursos que solo cambien de nombre o no tengan un uso real.

Los materiales se guardan en el registro independiente de materiales, sin ocupar espacios del inventario normal ni requerir que el jugador los lleve encima.

### Fuentes de obtención

Los materiales podrán conseguirse mediante:

- **Recolección del mundo:** plantas, minerales y otros recursos presentes en los territorios.
- **Enemigos:** determinados enemigos dejarán materiales relacionados con su naturaleza. No hace falta que cada enemigo tenga un material exclusivo; se podrán compartir materiales entre enemigos similares.
- **Jefes:** podrán entregar materiales especiales o únicos.
- **Actividades y exploración:** mazmorras, desafíos, cofres, misiones y otras recompensas.

Los materiales importantes deberán tener fuentes identificables. No se dependerá de probabilidades extremadamente bajas para conseguir recursos necesarios.

### Recolección

- Recolectar será una interacción sencilla: acercarse al recurso, interactuar y recogerlo.
- No se exigirán herramientas específicas, minijuegos, energía, resistencia ni límites diarios.
- Los recursos estarán distribuidos de forma razonable por el mundo. Se evitarán rutas repetitivas cuyo único propósito sea esperar reapariciones.

### Fabricación

La fabricación tendrá un alcance limitado a objetos con utilidad clara:

- Consumibles de curación.
- Consumibles de apoyo al combate, si se incorporan.
- Materiales procesados que se utilicen en mejoras.
- Algunos objetos de recetas especiales.

**El equipo no se fabricará como sistema general en la primera versión.** La obtención principal de equipo seguirá siendo el botín de enemigos, jefes, cofres y actividades.

No habrá profesiones con niveles propios, árboles de especialización, decenas de estaciones ni cadenas largas de procesamiento.

### Recetas y procesamiento

- Las recetas importantes se desbloquearán de forma permanente mediante exploración, misiones, jefes, desafíos, comerciantes o descubrimientos.
- Una vez desbloqueada una receta, podrá utilizarse siempre que se tengan los materiales necesarios.
- La interfaz mostrará los requisitos y una referencia general de dónde conseguir los materiales.
- Se permitirán transformaciones sencillas, como procesar minerales comunes o combinar recursos para fabricar consumibles.
- Como regla general, habrá como máximo una transformación intermedia entre el recurso original y el objeto final. Se evitarán cadenas de varios pasos.

### Lugares de fabricación

Los servicios de fabricación se agruparán en lugares seguros. Una interfaz o estación general permitirá consultar recetas y fabricar objetos directamente desde el registro de materiales, sin tener que trasladarlos al inventario normal.

### Relación con las mejoras de equipo

El sistema de mejoras de equipo ya aprobado utiliza moneda común y un material general de mejora.

- Ese material se obtendrá principalmente jugando: enemigos de élite, jefes, desafíos, actividades y algunas recompensas de exploración.
- La fabricación podrá servir como fuente complementaria si más adelante hace falta, pero no será obligatoria.
- No habrá un material distinto por ranura de equipo ni por cada nivel de mejora.

### Límites de diseño

- No habrá energía de recolección ni límites diarios.
- No se exigirán materiales obligatorios extremadamente raros.
- No se inflarán las recetas con cantidades excesivas de recursos.
- No habrá profesiones obligatorias ni materiales sin propósito.
- La fabricación no será un requisito para avanzar en la historia.
- Los materiales importantes tendrán fuentes claras y razonables.

Las cantidades concretas, recetas y valores se definirán durante el diseño de contenido y el balance, sin alterar estas reglas generales aprobadas.

## Monedas y economía

**Estado: APROBADO.** La economía utilizará una sola moneda general. Los materiales de progresión seguirán siendo materiales con usos concretos, no monedas alternativas.

### Moneda principal

- Habrá una única moneda común para las compras y servicios habituales.
- Se obtendrá jugando: derrotando enemigos, abriendo cofres, completando misiones y actividades, explorando y vendiendo objetos.
- No habrá monedas exclusivas de territorios, jefes o actividades.

### Gastos y usos

La moneda se utilizará principalmente para:

- Comprar consumibles y objetos básicos.
- Pagar mejoras de equipo, junto con el material general de mejora ya aprobado.
- Comprar determinados objetos a comerciantes.
- Pagar otros servicios concretos únicamente si aportan una utilidad real.

No se añadirán gastos artificiales cuyo único propósito sea retirar dinero al jugador.

### Comerciantes y servicios

- Los comerciantes y servicios estarán disponibles en lugares seguros.
- Los comerciantes ofrecerán objetos útiles, principalmente consumibles y recursos básicos.
- Las funciones de compra, venta, almacenamiento, fabricación y mejora podrán agruparse en una misma ubicación o interfaz. No hace falta crear un personaje distinto para cada servicio.
- Se evitarán desplazamientos innecesarios para realizar operaciones habituales.

### Venta de objetos

- El jugador podrá vender equipo y objetos que ya no necesite.
- El valor de venta tendrá en cuenta factores generales como el tipo y la calidad del objeto; los valores concretos se definirán durante el balance.
- Los objetos marcados como basura podrán venderse en grupo.
- Los objetos protegidos y equipados no podrán venderse accidentalmente.
- Los objetos únicos vendidos podrán recuperarse de su fuente original, de acuerdo con la regla de obtención de objetos únicos ya aprobada.

### Límites de diseño

No se incorporarán por defecto:

- Monedas distintas para cada territorio o actividad.
- Costes de reparación del equipo.
- Impuestos por viajar o utilizar servicios básicos.
- Comercio entre jugadores ni casa de subastas.
- Límites diarios para conseguir moneda.
- Sistemas complejos de inversión o mercado.

### Balance

Los precios y recompensas deberán mantener una economía útil y razonable: el jugador debe poder comprar objetos que le sirvan, sin que la moneda pierda toda su utilidad demasiado pronto.

Las cantidades, precios y recompensas concretas se definirán durante el balance, sin alterar las reglas generales aprobadas.

## Misiones y objetivos

**Estado: APROBADO.** El sistema general de misiones tendrá únicamente dos categorías: principales y secundarias. Los descubrimientos, desafíos, mazmorras y otras actividades pertenecen a sus respectivos sistemas de exploración y contenido, aunque puedan activar objetivos o misiones durante su desarrollo.

### Tipos de misión

- **Principales:** hacen avanzar la historia y conducen al protagonista hacia la siguiente etapa, territorio o mundo.
- **Secundarias:** desarrollan personajes, lugares, conflictos y acontecimientos que complementan la historia principal.

No todo descubrimiento, desafío o actividad necesita convertirse en una misión. Por ejemplo, un desafío puede estar disponible directamente en una zona específica; una mazmorra puede activar objetivos o una misión al entrar, sin crear una categoría general de misiones de mazmorra.

### Diseño de objetivos

- Los objetivos deben tener una razón dentro de la situación.
- Evitar encargos de relleno, como derrotar una cantidad arbitraria de enemigos sin contexto.
- Las misiones pueden combinar combate, exploración, conversaciones, búsqueda e interacción con el entorno.
- Los objetivos deben ser claros: el jugador tiene que entender qué necesita hacer.
- Las misiones secundarias no bloquearán el avance de la historia principal, salvo que exista una razón narrativa importante.

### Seguimiento

Un registro sencillo permitirá consultar:

- Misiones activas.
- Misiones completadas.
- Objetivo actual y progreso.

El jugador podrá seleccionar una misión como objetivo principal para facilitar su seguimiento. No hace falta llenar la pantalla de indicadores permanentemente.

### Recompensas

Las misiones podrán entregar:

- Experiencia.
- Moneda.
- Equipo y consumibles.
- Materiales.
- Desbloqueos permanentes.
- Información o acceso a nuevos lugares y acontecimientos.

Las recompensas importantes deberán ser claras. Un desbloqueo fundamental no dependerá de una probabilidad aleatoria.

### Decisiones y consecuencias

No se establece un sistema complejo de decisiones ramificadas para todas las misiones.

Podrán incluirse decisiones narrativas cuando tengan sentido, pero no será obligatorio que cada misión tenga varias rutas, finales o consecuencias enormes.

### Límites de diseño

- No habrá encargos diarios obligatorios.
- No se utilizarán misiones repetitivas como requisito para subir de nivel.
- Se evitarán objetivos artificiales para alargar el contenido.
- No se crearán cadenas de requisitos innecesarias.
- La historia principal no estará bloqueada detrás del 100% de exploración.
- No todo pequeño descubrimiento se convertirá en una misión formal.

La estructura prioriza misiones principales y secundarias con objetivos y recompensas útiles. Los detalles concretos de cada misión se definirán al diseñar la historia y el contenido.

## Actividades, mazmorras y contenido repetible

**Estado: APROBADO.** El contenido se organizará en unas pocas categorías reconocibles. No se crearán actividades distintas que repitan la misma función.

### Mazmorras

- Serán zonas independientes o espacios delimitados dentro de un territorio.
- Podrán contener enemigos, encuentros especiales, exploración, mecanismos y un jefe final.
- Tendrán objetivos propios que podrán activarse al entrar o avanzar.
- Algunas estarán relacionadas con la historia y otras serán opcionales.
- Sus recompensas estarán definidas según su importancia.
- No todas tendrán que seguir la misma estructura ni terminar obligatoriamente con un jefe.

### Jefes

- Los jefes importantes estarán vinculados a la historia, territorios o progresión.
- También podrán existir jefes opcionales para conseguir recompensas adicionales.
- Los encuentros podrán repetirse cuando tenga sentido, especialmente para obtener materiales o recompensas adicionales.
- La primera victoria sobre un jefe importante garantizará su recompensa principal.

### Desafíos

Los desafíos estarán disponibles en zonas o secciones específicas, separadas de las misiones normales.

- Se mantienen tres niveles de dificultad como estructura inicial.
- Cada nivel deberá exigir más habilidad y conocimiento de los patrones.
- La dificultad no consistirá simplemente en multiplicar la vida y el daño de los enemigos.
- Las recompensas aumentarán según la dificultad.
- Serán opcionales y no requisitos para completar la historia.

### Otros encuentros y actividades

Podrán existir eventos locales, encuentros especiales y situaciones que aparezcan durante la exploración.

No necesitan convertirse en sistemas independientes enormes. Se incorporarán cuando aporten algo interesante; si solo repiten contenido existente, no será necesario añadirlos.

### Repetición y recompensas

- Las mazmorras, los jefes y los desafíos podrán repetirse cuando corresponda.
- No habrá energía, tickets ni límites diarios de intentos.
- Las recompensas importantes no dependerán de repetir una actividad decenas de veces.
- Los desbloqueos fundamentales tendrán recompensas garantizadas.
- Repetir contenido servirá principalmente para conseguir recursos, equipo adicional o mejorar resultados.

### Límites de diseño

- Evitar mazmorras que solo cambien el aspecto de los enemigos.
- No crear actividades repetitivas para alargar artificialmente el juego.
- No esconder recompensas fundamentales detrás de probabilidades extremadamente bajas.
- No imponer obligaciones diarias.
- No crear variantes de dificultad que solo aumenten estadísticas.
- Evitar demasiados modos que compitan por cumplir la misma función.

La estructura prioriza mazmorras, jefes, desafíos opcionales y actividades adicionales solo cuando aporten variedad real. Los diseños concretos y recompensas se definirán al crear el contenido.

## Mapa, territorios y desplazamiento

**Estado: APROBADO.** El mapa estará organizado por territorios y conectado con el registro de exploración. Su función será orientar y facilitar el desplazamiento, sin sustituir la exploración.

### Mapa y exploración

El mapa permitirá:

- Consultar el territorio actual y sus zonas descubiertas.
- Ver lugares importantes, mazmorras, jefes, actividades y puntos de interés.
- Consultar el porcentaje y registro de exploración.
- Identificar lugares seguros y puntos de viaje rápido.
- Consultar pistas aproximadas de secretos, sin revelar su ubicación exacta.

No se llenará el mapa con iconos de cada objeto o recurso pequeño. Los marcadores deben ayudar a orientarse, no sustituir el descubrimiento.

### Territorios

- Cada territorio tendrá su propio mapa y registro de exploración.
- El jugador podrá regresar a territorios anteriores cuando la historia y el contenido lo permitan.
- Los territorios anteriores conservarán sus recompensas y contenido.
- No habrá escalado automático de todos los enemigos para igualar el nivel del jugador.

### Viaje rápido

- Se desbloqueará al descubrir o activar puntos importantes.
- Se podrá utilizar desde el mapa.
- No consumirá monedas ni materiales.
- No estará disponible durante combates ni situaciones que lo impidan.
- Su propósito será evitar recorridos innecesarios, no eliminar la exploración.

### Lugares seguros

Los lugares seguros podrán reunir servicios ya definidos, como almacenamiento, comerciantes, fabricación y mejoras. No hace falta que cada territorio tenga una ciudad enorme ni un NPC distinto para cada función; bastan lugares seguros bien distribuidos.

### Avance entre territorios

- El paso al siguiente territorio estará relacionado con la progresión de la historia.
- No será obligatorio completar el 100% de exploración para avanzar.
- Se podrá regresar a zonas anteriores si hay contenido pendiente o motivos para hacerlo.
- El regreso no deberá convertirse en una carga.

### Límites de diseño

- Evitar mapas saturados de marcadores.
- El viaje rápido no consumirá recursos.
- No habrá escalado automático de todos los enemigos.
- No se obligará a completar todo un territorio antes de continuar.
- Los territorios anteriores no perderán completamente su utilidad.

La estructura prioriza un mapa claro por territorio, registro de exploración, viaje rápido gratuito y libertad para regresar sin obligar a completar todo.

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
