# 00 — Arquitectura documental

**Estado: PROPUESTA REVISADA — pendiente de aprobación del usuario.**

## 1. Principio rector

Cada dato tiene un documento propietario. Los demás documentos pueden resumirlo para facilitar el trabajo, pero no crear una segunda versión independiente.

La arquitectura no funciona mediante una jerarquía lineal en la que un archivo siempre vence a todos los demás. Funciona mediante **autoridad por ámbito**: cada fuente es autoridad sobre el tipo de información que le corresponde.

Si dos fuentes que deberían ser compatibles discrepan, no elegir una en silencio: detener el trabajo afectado, identificar el conflicto y resolverlo antes de narrar.

## 2. Fuentes y responsabilidad exclusiva

| Fuente | Es autoridad sobre | No debe convertirse en |
|---|---|---|
| `01-REGLAS-DEL-MUNDO.md` | Reglas generales, límites y funcionamiento del mundo/Sistema | Manual de estilo, ficha de personaje o resumen de pisos |
| `PISOS/piso-XX/diseño.html` | Plan aprobado de ese piso: fases, orden, objetivos, participantes previstos, amenazas, condiciones y transiciones | Registro de acontecimientos ya ocurridos |
| `02-PERSONAJES/` | Estado vigente individual: capacidades, conocimientos, equipo, recursos, condición, objetivos y relaciones | Historial completo de la novela |
| `03-CONTINUIDAD/HISTORIAL-APROBADO.md` | Hechos narrativos aprobados, orden, causas y consecuencias confirmadas | Copia completa de todas las fichas |
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
- **¿En qué punto exacto estamos?** Consultar el estado actual.
- **¿Qué está permitido o prohibido por el mundo?** Consultar las reglas maestras.
- **¿Cómo debemos trabajar?** Consultar el protocolo y el método.

El diseño no convierte una posibilidad planificada en un hecho. La continuidad no puede cambiar una regla general. Una ficha actualizada no puede inventar un acontecimiento que no haya sido aprobado. El estado actual es un resumen de navegación: si contradice el historial o una ficha, debe corregirse, no tratarse como una fuente nueva de canon.

Una regla nueva no modifica retroactivamente hechos aprobados, salvo que el usuario decida expresamente revisar la continuidad.

## 4. Estructura del proyecto

- `00-ARQUITECTURA.md`
- `01-REGLAS-DEL-MUNDO.md`
- `02-PERSONAJES/INDICE.md` y fichas individuales.
- `03-CONTINUIDAD/ESTADO-ACTUAL.md`
- `03-CONTINUIDAD/HISTORIAL-APROBADO.md`
- `03-CONTINUIDAD/PLANTILLA-TRANSFERENCIA.md`
- `04-PROTOCOLO-NARRATIVO.md`
- `05-METODO-DE-DISENO-Y-TRABAJO.md`
- `06-ARCO-GLOBAL-PISOS-01-10.md`
- `07-SISTEMA-DE-PROGRESION.md`
- `PISOS/piso-XX/diseño.html`

## 5. Elenco y profundidad de seguimiento

- Personajes centrales y recurrentes: ficha individual con estado, capacidades, conocimientos, objetivos, relaciones, equipo y progresión.
- Personajes secundarios con posibilidad de regresar: registro breve, ampliable cuando adquieran relevancia.
- Personajes pasajeros: no requieren ficha persistente salvo que sus acciones produzcan consecuencias relevantes.
- Los personajes y grupos pueden progresar, entrenar, cambiar de objetivo, separarse, sufrir pérdidas o morir aunque Kevin no esté presente. No se inventarán esos avances: deberán estar previstos por el diseño, narrados o establecidos mediante una fuente fiable dentro de la historia.

## 6. Estados documentales

Todo contenido importante se identifica como **borrador**, **propuesta**, **aprobado**, **descartado** o **pendiente de confirmar**.

Solo el contenido aprobado puede tratarse como canon. Un documento puede contener secciones aprobadas y otras pendientes; el estado debe indicarse por sección cuando sea necesario.

## 7. Regla contra duplicaciones

Cuando cambie un dato, actualizar su documento propietario. El historial registra el acontecimiento que causó el cambio; la ficha registra el estado resultante; el estado actual señala dónde continuar. Ninguno debe copiar íntegramente el contenido de los otros.

El protocolo puede mencionar qué archivos consultar y qué comprobar, pero no reproducir sus reglas.
