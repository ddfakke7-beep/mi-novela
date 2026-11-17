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
- **Enemigos especiales:** serán una amenaza mayor que los normales. Podrán destacar por golpes más fuertes, mayor resistencia o alguna característica/mecánica sencilla. Como referencia, se busca que tengan una o dos particularidades como máximo cuando realmente aporten algo; no necesitan combos elaborados ni un repertorio grande.
- **Repertorio de ataques:** como punto de partida, bastarán dos o tres patrones reconocibles. No es una cuota obligatoria: algunos especiales podrán necesitar menos, y solo se añadirán ataques si aportan una diferencia clara.
- **Aturdimiento:** utilizarán la misma barra general de aturdimiento que los enemigos normales. Al llenarse, quedarán quietos durante el intervalo establecido; no tendrán una barra o efecto de aturdimiento exclusivo.
- **Interrupción:** podrán interrumpirse al recibir un golpe mientras preparan un ataque, siguiendo la regla general de los enemigos normales. Si un ataque concreto necesita protección para poder ejecutarse, podrá indicarse mediante su propio diseño; no se asumirá que todos sus ataques son inmunes a interrupciones.
- **Jefes:** tendrán un repertorio reducido y reconocible, evitando diseñar demasiados ataques y animaciones por jefe. Como referencia inicial de trabajo, podrían tener alrededor de 3 o 4 ataques habituales y 1 o 2 movimientos especiales/distintivos. No es una cuota obligatoria: algunos jefes podrán necesitar menos. Los movimientos distintivos pueden ser golpes muy dañinos, ataques que derriben al jugador, ataques de área u otras mecánicas concretas. Se prioriza que cada movimiento tenga una función clara, no acumular cantidad.

**Comportamiento básico e interrupciones:**
- Los enemigos normales cuerpo a cuerpo seguirán una lógica sencilla: detectan al jugador, se acercan, atacan cuando están a distancia y vuelven a intentarlo. Los enemigos a distancia mantendrán una lógica equivalente adaptada a su alcance.
- El jugador podrá tomar la iniciativa: atacar, usar la habilidad o la definitiva antes de que el enemigo consiga golpearlo.
- **Interrupción de enemigos normales:** si un enemigo normal recibe un golpe mientras prepara un ataque, ese impacto podrá interrumpirlo y cancelar el ataque. No se necesita una barra ni un sistema adicional para esta reacción.
- **Jefes:** no serán interrumpidos por los golpes normales del jugador durante sus ataques. Sus movimientos deben poder ejecutarse sin que el jugador los cancele simplemente manteniendo el ataque.
- **Enemigos especiales:** queda pendiente decidir si algunos de sus ataques pueden interrumpirse o si tendrán resistencia a la interrupción. No se añadirá una regla compleja sin necesidad.
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
