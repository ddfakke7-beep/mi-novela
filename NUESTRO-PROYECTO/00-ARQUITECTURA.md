# 00 — Arquitectura documental

**Estado: APROBADA — arquitectura documental y responsabilidades.**

## 1. Principio rector

Cada dato tiene un documento propietario. Los demás documentos pueden resumirlo para facilitar el trabajo, pero no crear una segunda versión independiente.

La arquitectura no funciona mediante una jerarquía lineal en la que un archivo siempre vence a todos los demás. Funciona mediante **autoridad por ámbito**: cada fuente es autoridad sobre el tipo de información que le corresponde.

Si dos fuentes que deberían ser compatibles discrepan, no elegir una en silencio: detener el trabajo afectado, identificar el conflicto y resolverlo antes de narrar.

La continuidad abarca tanto a Kevin y su círculo cercano como al resto de personajes, grupos y elementos del mundo que adquieran relevancia. El mundo no queda suspendido cuando Kevin no está presente.

## 2. Fuentes y responsabilidad exclusiva

| Fuente | Es autoridad sobre | No debe convertirse en |
|---|---|---|
| `01-REGLAS-DEL-MUNDO.md` | Reglas generales, límites y funcionamiento del mundo/Sistema | Manual de estilo, ficha de personaje o resumen de pisos |
| `PISOS/piso-XX/diseño.html` | Plan aprobado de ese piso: fases, orden, objetivos, participantes previstos, amenazas, condiciones y transiciones | Registro de acontecimientos ya ocurridos |
| `02-PERSONAJES/` | Estado vigente individual: capacidades, conocimientos, equipo, recursos, condición, objetivos, relaciones y situación/destino conocido | Historial completo de la novela |
| `02-PERSONAJES/GRUPOS/` | Identidad y estado vigente de grupos recurrentes: integrantes, composición, cohesión, objetivos, coordinación, recursos, relaciones y trayectoria colectiva | Sustituto de las fichas individuales o registro de cada cooperación pasajera |
| `03-CONTINUIDAD/HISTORIAL-APROBADO.md` | Hechos narrativos aprobados, orden, causas y consecuencias confirmadas; evolución del mundo y sucesos relevantes fuera de la perspectiva de Kevin | Copia completa de todas las fichas |
| `03-CONTINUIDAD/ESTADO-ACTUAL.md` | Resumen operativo del punto exacto en que continúa la historia | Segunda versión de las reglas o de las fichas |
| `04-PROTOCOLO-NARRATIVO.md` | Controles que obligan a consultar y aplicar las fuentes | Fuente de nuevas reglas del mundo |
| `05-METODO-DE-DISENO-Y-TRABAJO.md` | Procedimiento para diseñar, revisar, aprobar y mantener | Repetición de reglas narrativas |
| `06-ARCO-GLOBAL-PISOS-01-10.md` | Propósito y progresión planificada del arco global | Canon de sucesos todavía no narrados |
| `07-SISTEMA-DE-PROGRESION.md` | Método de evaluación y registro del crecimiento | Estado actual de Kevin o de otro personaje |

## 3. Cómo resolver información aparentemente contradictoria

Aplicar estas distinciones:

- **¿Qué debía pasar?** Consultar el diseño aprobado del piso.
- **¿Qué pasó realmente?** Consultar el historial narrativo aprobado.
- **¿Cómo está ahora un personaje?** Consultar su ficha vigente.
- **¿Cómo está ahora un grupo?** Consultar su registro vigente.
- **¿En qué punto exacto estamos?** Consultar el estado actual.
- **¿Qué está permitido o prohibido por el mundo?** Consultar las reglas maestras.
- **¿Cómo debemos trabajar?** Consultar el protocolo y el método.

El diseño no convierte una posibilidad planificada en un hecho. La continuidad no puede cambiar una regla general. Una ficha o registro actualizado no puede inventar un acontecimiento que no haya sido aprobado. El estado actual es un resumen de navegación: si contradice el historial o una ficha, debe corregirse, no tratarse como una fuente nueva de canon.

Una regla nueva no modifica retroactivamente hechos aprobados, salvo que el usuario decida expresamente revisar la continuidad.

## 4. Estructura del proyecto

- `00-ARQUITECTURA.md`
- `01-REGLAS-DEL-MUNDO.md`
- `02-PERSONAJES/INDICE.md` y fichas individuales.
- `02-PERSONAJES/GRUPOS/INDICE.md` y registros individuales de grupos recurrentes.
- `03-CONTINUIDAD/ESTADO-ACTUAL.md`
- `03-CONTINUIDAD/HISTORIAL-APROBADO.md`
- `03-CONTINUIDAD/PLANTILLA-TRANSFERENCIA.md`
- `04-PROTOCOLO-NARRATIVO.md`
- `05-METODO-DE-DISENO-Y-TRABAJO.md`
- `06-ARCO-GLOBAL-PISOS-01-10.md`
- `07-SISTEMA-DE-PROGRESION.md`
- `PISOS/piso-XX/diseño.html`

## 5. Elenco, grupos y profundidad de seguimiento

### Personajes

- **Centrales y recurrentes:** ficha individual con estado, capacidades, conocimientos, objetivos, relaciones, equipo, recursos, progresión y situación/destino conocido.
- **Secundarios con posibilidad de regresar:** registro breve, ampliable cuando adquieran relevancia.
- **Pasajeros:** no requieren ficha persistente salvo que sus acciones produzcan consecuencias relevantes.
- Si un personaje pasajero o secundario adquiere importancia recurrente, se amplía su seguimiento desde ese momento sin inventar retrospectivamente una biografía.

### Grupos

- Los grupos recurrentes pueden tener un registro propio, separado de las fichas de sus integrantes.
- Se registra su composición en cada etapa relevante, altas y bajas, cohesión, objetivos, coordinación, estrategias, recursos, relaciones y estado conocido.
- La cooperación ocasional no crea automáticamente un grupo formal ni exige un registro permanente.
- Los cambios de integrantes, separaciones, disoluciones, pérdidas y reencuentros solo se consideran hechos cuando están establecidos y aprobados.
- La evolución colectiva no sustituye ni determina automáticamente la progresión individual: cada integrante puede desarrollarse a un ritmo distinto.

### Continuidad fuera de la perspectiva de Kevin

Los personajes y grupos pueden progresar, entrenar, cambiar de objetivo, separarse, sufrir pérdidas o morir aunque Kevin no esté presente. También pueden evolucionar organizaciones, alianzas, comunidades, conocimientos colectivos y otros elementos del mundo cuando existan y tengan relevancia.

No se inventarán esos avances como hechos consumados. Deben estar narrados, aprobados o establecidos mediante una fuente válida dentro de la historia. Cuando una reaparición requiera explicar el intervalo, se puede proponer una trayectoria coherente, pero debe distinguirse de lo confirmado hasta que se establezca.

El seguimiento será proporcional a la relevancia: no se registrará exhaustivamente a todo participante pasajero.

## 6. Estado de personajes, grupos y certeza de la información

No confundir ausencia de aparición con un destino confirmado. Cuando sea relevante, la ficha o registro indicará si la entidad está activa, ausente con situación conocida, desaparecida/sin ubicación conocida, retirada, fallecida (solo con muerte confirmada), disuelta (para grupos) o en otra situación definida por los hechos.

Además, distinguir el grado de certeza de los datos narrativos:

- **Confirmado:** establecido por un acontecimiento aprobado o una fuente válida de la historia.
- **Inferido:** conclusión razonable derivada de hechos confirmados; no equivale a canon nuevo.
- **Desconocido:** no existe información suficiente.
- **Propuesto:** posibilidad de desarrollo todavía no aprobada.

Una inferencia o propuesta nunca se convierte silenciosamente en un hecho confirmado. Si una inferencia afecta decisiones importantes, explicitar su fundamento y sus límites.

## 7. Estados documentales

Todo contenido importante se identifica como **borrador**, **propuesta**, **aprobado**, **descartado** o **pendiente de confirmar**.

Solo el contenido aprobado puede tratarse como canon. Un documento puede contener secciones aprobadas y otras pendientes; el estado debe indicarse por sección cuando sea necesario.

## 8. Regla contra duplicaciones

Cuando cambie un dato, actualizar su documento propietario. El historial registra el acontecimiento que causó el cambio; la ficha registra el estado resultante; el estado actual señala dónde continuar. Ninguno debe copiar íntegramente el contenido de los otros.

El protocolo puede mencionar qué archivos consultar y qué comprobar, pero no reproducir sus reglas.
