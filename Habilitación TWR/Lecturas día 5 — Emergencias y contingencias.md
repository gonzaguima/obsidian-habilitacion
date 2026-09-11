---
tags:
  - habilitacion-twr
  - lecturas
  - ojt
---

# Lecturas para el día 5 — Emergencias y contingencias

El día 4 ya cubrió el **PEA, las alertas, la cadena de notificación, COA y meteorología aplicada**. El objetivo ahora es pasar de conocer el circuito a poder sostener la operación cuando se degrada un medio.

> Documento de lectura preparado el 10/09/2026. No acredita práctica, manejo de equipos ni decisión autónoma en el puesto. Ante una diferencia, prevalecen la publicación vigente, la cartilla del puesto y la instrucción del OJTI.

## 1. Prioridad y secuencia mental

1. **PEA y fases de alerta:** repasar Alerta 1, 2 y 3; distinguirlas de INCERFA, ALERFA y DETRESFA. Poder decir quién declara, a quién avisa TWR, quién cancela y qué datos se amplían después del aviso inicial.
2. **Emergencia de aeronave:** en MADE SULS, estudiar asistencia, prioridad, protección de la trayectoria, coordinación, fraseología y comunicaciones. Incluir interferencia ilícita, amenaza de bomba, falla de comunicaciones aire-tierra, descenso de emergencia y accidente/incidente.
3. **Degradación CNS y equipos:** para cada falla de SDC, SDD/vigilancia, radioayuda, suministro eléctrico o luces, identificar: señal de falla → verificación → registro → aviso técnico/supervisión → medio alternativo → restricción de capacidad o servicio → coordinación y difusión → condición de recuperación.

La secuencia que organiza todos los casos es:

```text
reconocer → verificar → proteger el tránsito → avisar/coordinar →
usar el respaldo autorizado → informar las limitaciones → registrar →
recuperar sólo cuando mantenimiento lo habilite
```

El respaldo no equivale automáticamente a operación normal. Antes de continuar, determinar qué servicio puede mantenerse, qué capacidad queda y qué tránsito no se debe aceptar.

## 2. Emergencia de aeronave: qué hace TWR SULS

El MADE SULS indica activar la alerta PEA apropiada conforme a la comunicación con la tripulación, el código 7700 o signos evidentes de desempeño inseguro. La primera prioridad operativa es proteger al tránsito en emergencia: despejar la trayectoria de descenso o el trayecto de rodaje.

| Situación | Punto de actuación que hay que retener |
|---|---|
| Emergencia declarada, 7700 o indicios observados | Recabar lo que sea útil sin demorar la protección; aplicar la alerta local y priorizar la aeronave. |
| Interferencia ilícita / 7500 | Activar Alerta 3, actuar con discreción y no negociar en la frecuencia de trabajo. Atender solicitudes, transmitir información sin esperar respuesta y coordinar la transferencia con Jefe de Turno/APP. |
| Amenaza de bomba de fuente confiable | Activar Alerta 2; avisar a la tripulación por el medio más rápido, sin asesorarla sobre manipulación de la posible bomba. Atender solicitudes, vigilar y coordinar. |
| Descenso de emergencia | Ejecutivo difunde inmediatamente tipo, posición, nivel que deja libre y rumbo aproximado; Planificador avisa a sectores/dependencias afectados. Después se protege al resto del tránsito empezando por el más crítico. |
| RA ACAS | No impartir instrucciones que contradigan la resolución. Dar información de tránsito pertinente y reasumir control cuando la tripulación informe que puede seguir instrucciones ATC. Corresponde reporte de incidente ATS. |

Para la alerta aeroportuaria y su cancelación, volver al resumen de día 4: **PEA 1/2/3** no es lo mismo que **INCERFA/ALERFA/DETRESFA**. Una operación que termina sin novedad no cancela por sí sola la alerta PEA.

### Información que conviene ordenar

No hay que esperar la respuesta a todas estas preguntas para iniciar la ayuda:

1. Identificación, tipo de aeronave y naturaleza de la emergencia.
2. Posición, altitud/nivel, pista o sector, intención y tiempo disponible.
3. Personas a bordo, combustible y mercancías peligrosas, si se conocen.
4. Tránsito afectado, medidas de protección ya tomadas y dependencias notificadas.
5. Novedades, aterrizaje/posición final y el circuito formal de cancelación.

La fraseología debe ser completa, concisa, clara y oportuna. Para el texto operacional, consultar Doc. 4444 capítulo 12, Doc. 9432 y MATS: este resumen no sustituye sus expresiones normalizadas.

## 3. Fallas CNS: ciclo obligatorio de notificación y recuperación

MADE SULS §5.6 dispone notificar de inmediato cualquier falla o irregularidad de comunicaciones, navegación, vigilancia u otro equipo que afecte la seguridad o eficiencia. La instrucción local indicada en el manual es informar a Dirección Electrónica por la vía telefónica primaria, interno **4520**, describiendo el tipo de falla para su encaminamiento técnico.

- Registrar **notificación y respuesta** en el Libro de Guardia: es información para el relevo, las limitaciones y el seguimiento.
- Aplicar el Plan de Contingencia que corresponda a la falla; no seleccionar una medida por analogía.
- El equipo sólo vuelve a utilizarse cuando mantenimiento comunique que está en condiciones de servicio.
- Electrónica/AIS comunica los términos, validez, distribución y publicación del estado CNS; la contingencia del servicio ATS se difunde a dependencias, usuarios y, cuando corresponda, por NOTAM.

### Matriz de decisión

| Falla | Verificar y proteger | Respaldo / coordinación | Recuperación |
|---|---|---|---|
| **SDC / telefonía** | Precisar qué línea o dependencia queda aislada y qué coordinación en curso puede quedar sin acuse. | Aplicar el procedimiento local/POI; usar sólo medios alternativos autorizados y avisar a las dependencias afectadas. El plan nacional contempla cambio de posición/UCS para una falla de línea SDC, pero confirmar la configuración vigente de SULS. | Registrar, informar el restablecimiento y reanudar el medio normal sólo con confirmación técnica. |
| **Radio tierra-aire** | Confirmar alcance de la falla y avisar a los tránsitos ya en vuelo, rodaje o en secuencia. | MADE SULS §7.1: si falla 118.3 MHz, usar 122.1 MHz como principal; si falla CWP o ambos equipos, usar el equipo de emergencia ROHDE & SCHWARZ para terminar operaciones en curso, coordinar y no aceptar más tránsito hacia SULS. | Mantenimiento CAISA determina condición normal o necesidad de NOTAM; registrar en Libro de Guardia. |
| **SDD / vigilancia / FDP** | Distinguir la falla local de visualización/datos de una falla de vigilancia ATS; no asumir que existe capacidad radar donde el manual dice que no aplica. | En SULS, la contingencia de vigilancia ATS figura como no aplicable; ante falla FDP, seguir POI APP–TWR SULS. Las medidas de vigilancia del CCM se rigen por los POI definidos. | Restablecer sólo luego del procedimiento y confirmación aplicables. |
| **Radioayuda** | Identificar la ayuda, procedimiento, aproximación o tránsito afectado; evitar expedir una autorización que dependa de una ayuda no disponible. | Avisar a Electrónica/radioayudas, a las dependencias y a los vuelos afectados; evaluar publicación, procedimiento alternativo y capacidad con el OJTI/supervisión. | La condición y publicación se confirman por los canales formales; no declarar operativa una ayuda desde una indicación aislada. |
| **Energía o luces** | Establecer qué equipo quedó afectado, si existe alimentación de respaldo y el impacto inmediato en seguridad/capacidad. | El plan nacional exige aviso técnico, evaluación de impacto, medios alternativos y aviso a unidades ATS afectadas. Para luces, aplicar la cartilla local y la restricción/NOTAM correspondiente; no deducir mínimos ni disponibilidad. | Informar fin de degradación a todos los afectados sólo tras habilitación técnica. |

## 4. Capacidad, degradación y coordinación

El Plan de Contingencia ATS Uruguay describe fases 0 a 5 según el impacto de la degradación: la fase 0 se absorbe con redundancias; las fases posteriores introducen ajustes y restricciones progresivas hasta una suspensión parcial o total del flujo en la fase 5. No es una escala que el controlador de TWR aplique por intuición: sirve para entender que toda degradación requiere evaluar **capacidad**, coordinación y comunicación de las restricciones.

En particular, el plan exige para una falla eléctrica secundaria: aviso técnico inmediato, evaluación del efecto ATS, empleo de medios alternativos, información a las unidades afectadas y aviso de finalización cuando corresponda. Una falla puede obligar a limitar o cancelar la operación según los sistemas realmente disponibles.

Si la falla compromete la separación aplicable durante una emergencia, MADE SULS §8 prevé una separación de emergencia de **500 ft**, informando a los tránsitos involucrados y suministrando información de tránsito esencial. Es una medida excepcional; no reemplaza las mínimas normales ni autoriza aplicarla fuera de su supuesto.

## 5. Escenarios de repaso activo

### A. Pérdida de 118.3 MHz con tránsito en final, salida en rodaje y otra llegada coordinada

1. ¿Cómo confirmás la falla y qué frecuencia de respaldo establece el MADE?
2. ¿Qué informás primero a las aeronaves y a qué dependencias?
3. Si además falla el segundo equipo/CWP, ¿qué operaciones deben terminarse y cuál tránsito deja de aceptarse?
4. ¿Qué queda anotado y quién determina el restablecimiento?

### B. Emergencia de tren y teléfono de coordinación degradado

1. Separá la protección de la trayectoria de la activación de alerta y de la notificación técnica.
2. Decí qué información transmitís inicialmente a Bomberos/Operaciones/CCR conforme al PEA.
3. Elegí el medio alternativo autorizado para la coordinación; si no está confirmado, no lo inventes: pedilo al OJTI.
4. Explicá por qué el aterrizaje sin novedad no basta para cancelar la alerta.

### C. Luces o radioayuda fuera de servicio con meteorología marginal

1. ¿Qué operación, aproximación o mínimo puede quedar afectado?
2. ¿A quién notificás y cómo evitás que se siga usando la información previa como si el sistema estuviera operativo?
3. ¿Qué restricciones/capacidad se deben coordinar antes de aceptar otro tránsito?
4. ¿Qué confirmación permite quitar la limitación?

## 6. Fuentes y lectura dirigida

- [Resumen día 4#1. Plan de emergencia del aeródromo — SULS](Resumen%20d%C3%ADa%204.md#1-plan-de-emergencia-del-aer%C3%B3dromo-suls) y su sección de fases ATS/SAR: repaso activo de alertas, notificación y cierre.
- **MADE SULS v2.0**, §§5.6, 6.4–6.6, 7.1–7.3 y 8: estado CNS, emergencia, interferencia ilícita, amenaza de bomba, RA ACAS, radio, vigilancia y separación de emergencia.
- **Plan de Contingencia ATS Uruguay v2.0**, §§3.1 y 4.1–4.8: fases de degradación, energía, frecuencias, SDC, AFTN y vigilancia. Leer siempre el procedimiento particular aplicable; no extrapolar una contingencia ACC/APP a TWR.
- Procedimiento local de degradación/contingencias de TWR SULS y cartillas vigentes del puesto, si están disponibles durante el briefing. Confirmar con el OJTI qué respaldo se usa realmente y cómo se registra la falla.

## 7. Matriz para completar con el OJTI

| Falla o situación | Cómo se detecta/verifica | Primer aviso | Medio alternativo | Protección operacional | Registro y recuperación |
|---|---|---|---|---|---|
| SDC / telefonía |  |  |  |  |  |
| SDD / vigilancia |  |  |  |  |  |
| Radioayuda |  |  |  |  |  |
| Energía |  |  |  |  |  |
| Luces |  |  |  |  |  |

## 8. Control de lectura

1. ¿Qué hechos pueden llevar a TWR a activar una alerta aunque el piloto no use MAYDAY?
2. ¿Qué diferencia hay entre la alerta PEA y una fase SAR?
3. Ante 7500, ¿qué no debe hacerse en la frecuencia operativa?
4. Ante una amenaza de bomba, ¿qué tipo de asesoramiento no debe dar TWR?
5. ¿Cuál es la secuencia de frecuencia y respaldo prevista localmente al fallar 118.3 MHz?
6. ¿Qué se hace con el tránsito en curso cuando sólo queda el equipo de emergencia?
7. ¿Dónde se registra una falla CNS y quién habilita el retorno a servicio?
8. ¿Por qué una falla de vigilancia del CCM no debe trasladarse mecánicamente a la operación SULS?
9. ¿Qué tenés que determinar antes de continuar una operación con luces, energía o radioayuda degradadas?
10. ¿Cuál es el orden de prioridades que usarías en un escenario integrado?

Si el procedimiento local no fija un dato, medio o límite, llevarlo como pregunta al OJTI en vez de inferirlo.
