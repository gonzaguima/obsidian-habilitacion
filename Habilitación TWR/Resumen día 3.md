# Instrucción OJT TWR SULS — Día 3

> Jornada 3 completada según confirmación del entrenando del 08/09/2026: **4 h como Ejecutivo**, con varias aproximaciones VOR y RNP a distintas pistas. La lectura de CAO con COA se completó en el día 4 y está resumida allí.

> Resumen integrado del día 3: reúne las incorporaciones de `Notas dia 3.md`, la CAO meteorológica, la familiarización con aeródromos/modelos y la práctica de la jornada. Los contenidos APP–TWR, GRF/CAISA, METAR y cartas se consolidan en el día 1; COA, en el día 4.

## Para ubicarse rápido

- **Base APP–TWR, GRF/CAISA, METAR y cartas:** consolidada en [[Resumen día 1]].
- **CAO meteo:** funciones de EMA/OMA/OVM, cizalladura, discrepancias de nubes/visibilidad y contingencias.
- **CAO COA:** consolidada en [[Resumen día 4]].
- **Complemento de repaso:** aeródromos y modelos de aeronave, solicitado al terminar el día 2.

## Apuntes originales y alcance de la jornada

Las notas del día 3 dicen:

> aparte de lo ya establecido, carta de acuerdo meteo
>
> leer carta con COA

“Lo ya establecido” se relaciona con las tareas anotadas al terminar el día 2: lectura de APP–TWR, procedimiento GRF SULS, acuerdo con CAISA sobre GRF, repaso de METAR, cartas de aproximación y reconocimiento de aeródromos/modelos habituales. El bloque base se consolidó en el día 1; esta nota conserva los aportes propios del día 3.

### Confirmación posterior de lo trabajado

El 08/09/2026 el entrenando confirmó que **se dio todo lo programado para el día 3**, con la excepción inicial de la **lectura de la CAO con COA**. Esta lectura se completó en el día 4. Se consideran trabajados el bloque APP–TWR, GRF/CAISA, METAR y CAO meteorológica, cartas, contingencias previstas y familiarización con aeródromos/modelos de esa jornada.

La práctica fue de **4 horas como Ejecutivo**, controlando **varias aproximaciones VOR y RNP a distintas pistas**. No se especificaron cantidad exacta, designadores de pista, tránsitos ni correcciones, por lo que no se atribuyen operaciones concretas adicionales ni un nivel de autonomía.

Sumadas a las aproximadamente 2 h del día 2, quedan **unas 6 h de práctica acumulada**. Son 4 h de Ejecutivo en día 3 más la porción de Ejecutivo no desglosada del día 2; no son 6 h exclusivamente como Ejecutivo.

El **plan de emergencia** se mantiene como lectura expresamente asignada para el **día 4**.

## Relación con el plan OJT

El plan guía ubica en el día 3 cartas de acuerdo, procedimientos instrumentales, coordinaciones, transferencias, contingencias y práctica supervisada como Ejecutivo. Las lecturas permiten preparar una misma pregunta para cualquier situación: **quién actúa, qué información necesita, cuándo coordina y quién conserva la responsabilidad**.

---

## Contenidos retomados de la jornada 1

Los procedimientos APP–TWR, GRF/CAISA, METAR y cartas de aproximación quedaron consolidados en [[Resumen día 1]]. En esta jornada se aplicaron y profundizaron junto con los acuerdos meteorológico y COA, sin duplicar aquí su desarrollo de estudio.

## 1. CAO meteorológica — DCA / ATS / INUMET

Fuentes: **CAO general, revisión 01, julio de 2024**, §§2–6, y **Anexo II SULS**, efectivo desde el **01/11/2025**, especialmente §§2–9 (páginas 2–12 del PDF). El anexo local es el que desarrolla equipos, comunicaciones y circuitos específicos de SULS.

### Quién hace cada tarea

| Dependencia | Función que hay que recordar |
|---|---|
| **EMA-SULS** — Estación Meteorológica Aeronáutica | Realiza observaciones y emite METAR/SPECI; recibe reportes locales, incluida cizalladura. |
| **OMA-SULS** — Oficina Meteorológica de Aeródromo | Proporciona TAF, GAMET, información de ruta y documentación elaborados por OMA-SUMU; coordina exposiciones verbales. |
| **OMA-SUMU** | Elabora los pronósticos y documentación indicados; suple las funciones de OMA-SULS cuando esta no tiene personal. |
| **OVM-SUMU** — Oficina de Vigilancia Meteorológica | Vigila el área asignada y emite/difunde información y avisos correspondientes, incluidos SIGMET y avisos de cizalladura. |
| **TWR / ATS** | Recibe y retransmite información meteorológica a las aeronaves; hace llegar a MET las aeronotificaciones y observaciones pertinentes. |

La coordinación funciona en ambos sentidos: **MET → ATS → aeronaves** y **aeronaves/ATS → MET**. TWR es un enlace esencial, pero la confección del informe meteorológico corresponde a INUMET.

### Productos: observación, pronóstico y aviso

| Producto | Para qué sirve |
|---|---|
| **METAR** | Observación ordinaria; la CAO general establece emisión cada hora. |
| **SPECI** | Observación especial ante los cambios que lo justifican. |
| **TAF** | Pronóstico de aeródromo; la tabla general prevé emisión cada seis horas. |
| **TREND** | Pronóstico breve adjunto al informe; la CAO general lo contempla para SUMU. |
| **GAMET** | Pronóstico de área para vuelos a baja altura. |
| **SIGMET / AIRMET** | Información sobre fenómenos en ruta que pueden afectar la seguridad, según el ámbito y los criterios de cada producto. |
| **AD WRNG / WS WRNG** | Aviso de aeródromo / aviso de cizalladura. |

No confundir **frecuencia de emisión** con **período de validez**. Un TAF emitido cada seis horas puede cubrir un período mayor. Para SULS, la AIP consultada identifica a OMA-SUMU como responsable del TAF e indica `Nil` para tendencia. [AIP SULS, información meteorológica](https://www.dinacia.gub.uy/sites/default/files/aip/2026-05/Ad2-5%20%286%29.pdf).

### Instrumental y presentadores en SULS

- **AWOS:** sensores en la intersección de RWY 08/26 y 01/19.
- **EMA Vaisala:** en umbral 08, utilizada también como respaldo.
- **Nefobasímetro:** en umbral 08; referencia automática para la base de nubes más baja.
- El anexo también identifica instrumental en el parque meteorológico de la estación.
- Los presentadores de TWR integran viento, temperatura, punto de rocío, presión y último METAR/SPECI.

**Viento:** el METAR/SPECI usa el promedio de los últimos **10 minutos**. El anexo describe la visualización de viento de TWR **cada 2 minutos** y el respaldo Vaisala. Son referencias temporales diferentes; no esperar que todos los valores instantáneos coincidan. Las ráfagas se cifran cuando la diferencia alcanza **10 kt o más** durante el período de observación indicado.

### Aeronotificaciones que ATS debe hacer llegar a MET

Se transmiten cuanto antes los reportes pertinentes, especialmente durante ascenso inicial y aproximación. El anexo menciona temperatura, viento, turbulencia, engelamiento y humedad cuando se conoce; entre los reportes especiales, turbulencia/engelamiento moderados o fuertes, determinadas tormentas, polvo o arena fuertes, ceniza/actividad volcánica y frenado inferior a bueno.

La **cizalladura** tiene un circuito local explícito hacia **EMA-SULS**. El reporte de frenado también interesa a **CAISA** para evaluar la pista: transmitirlo a MET no sustituye el circuito GRF.

### Cizalladura: recepción, emisión y cancelación

1. **La aeronave reporta a TWR.**
2. **TWR avisa a EMA-SULS con la mayor celeridad posible**, por los medios previstos disponibles.
3. **EMA** incluye el fenómeno como información suplementaria en METAR/SPECI, según corresponda.
4. **EMA avisa a OVM-SUMU**, que emite el aviso de cizalladura.
5. **ATS difunde la información pertinente** a las aeronaves afectadas y coordina con APP.

El reporte debe incluir, cuando se disponga: **pista, identificación, posición GPS si es posible, nivel de vuelo, intensidad del fenómeno, viento y temperatura**. Conservar también el contexto temporal del reporte para que pueda relacionarse con la operación.

La cancelación prevista en §6 del anexo sigue dos casos:

- **Dos horas desde la última notificación de aeronave:** EMA y OVM proceden a la cancelación; EMA se comunica con TWR y OVM.
- **Una aeronave informa que no hay afectación:** TWR lo comunica inmediatamente a EMA; EMA coordina con OVM la cancelación.

**TWR no cancela por su cuenta el aviso meteorológico.** Que una aeronave no mencione cizalladura no equivale a un reporte explícito de no afectación; se aplica el circuito y el criterio temporal del anexo.

### Nubosidad: qué hacer si hay discrepancias

La referencia inicial es el nefobasímetro; para las capas siguientes se utiliza la estimación del observador. Si falla la medición automática, se recurre a la estimación meteorológica.

Cuando discrepan las estimaciones o reportes:

1. TWR solicita a la primera aeronave que opere un reporte de la base de nubes más baja.
2. Se comunica a MET para su inclusión en METAR/SPECI.
3. Si persiste la discrepancia, el anexo dispone informar la **menor altura estimada o reportada**.

No promediar valores incompatibles ni sustituir informalmente el informe en TWR: corresponde coordinar con quien lo emite.

### Visibilidad local

Si el observador lo considera oportuno o ATS lo solicita expresamente, se pide a **Operaciones CAISA** el traslado al umbral correspondiente para estimar la visibilidad mínima mediante conteo de balizas.

Cuando corresponde informar una visibilidad mínima distinta de la predominante, el anexo establece el criterio de **menos de 1.500 m o menos del 50 % de la predominante**, indicando su dirección general.

La estimación visual en el umbral no debe confundirse automáticamente con una medición instrumental de **RVR**. Al recibir información, identificar qué variable se está reportando y de dónde procede.

### Comunicaciones y ATIS

- El anexo establece **telefonía directa como medio primario de coordinación**, con teléfonos alternativos.
- **AMHS** distribuye METAR/SPECI y otros mensajes. La estación emisora local figura como `SULSYMYX`.
- Para **ATIS 132,1 MHz**, el anexo asigna al **observador** el ingreso manual del METAR/SPECI. TWR debe mantener coherente la información operacional que transmite con los cambios recibidos.
- La tabla de enlaces radioeléctricos TWR–EMA y EMA–OVM/OMA figura **Nil**, aunque la contingencia menciona una frecuencia secundaria a asignar por DINACIA. La copia no proporciona una frecuencia utilizable: ese medio queda por confirmar en la configuración local.

### Contingencias meteo

| Falla | Respuesta resumida del Anexo II |
|---|---|
| Presentadores AWOS y Vaisala en ATS | Utilizar los valores del METAR/SPECI e informar a EMA-SULS. |
| Sensores AWOS | EMA confecciona el informe con Vaisala. |
| AWOS y Vaisala | EMA recurre al instrumental convencional y solicita PRENOTAM. |
| Terminal PUMA / AMHS de EMA | Intentar transmisión por terminales INUMET → Centro de Comunicaciones (CXK) → ACC; escalar a DTA según el orden del anexo. INUMET conserva la responsabilidad del contenido. |
| Imposibilidad de transmitir la información | Gestionar PRENOTAM que comunique la indisponibilidad. |
| Falla eléctrica | EMA avisa a ATS, CAISA y AIS; si no logra contactar AIS, canaliza la solicitud por OVM/OMA. |
| OMA-SULS sin personal | OMA-SUMU suple pronósticos, documentación y exposiciones verbales. |
| Internet y telefonía totalmente fuera de servicio | El anexo prevé radio secundaria, pero su asignación no queda resuelta en la copia; comprobar el medio local establecido. |

La CAO general exige considerar las limitaciones de servicio que produce la falta de equipo y notificar las afectaciones. El respaldo de **OMA-SULS** no equivale por sí solo a reemplazar las observaciones de **EMA-SULS**.

### Observación documental

La CAO general de 2024 fija un plazo de dos años; la copia disponible no acredita renovación posterior. El Anexo II es de octubre de 2025, efectivo desde noviembre, y también fija dos años. Este resumen conserva ambas referencias y sus fechas, sin dar por acreditada la renovación del acuerdo general. Además, el anexo local describe un nefobasímetro en SULS, mientras el texto general anterior mencionaba ese equipo solo para SUMU: para estudiar la instalación local se utiliza el anexo específico más reciente.

---

## 2. Seguimiento de la CAO con COA

La lectura fue asignada durante el día 3 y se completó en el día 4. Su desarrollo íntegro está consolidado en [[Resumen día 4#3. CAO con COA — lectura pendiente que se integra al día 4]], para evitar duplicarlo entre jornadas.

## 3. Aeródromos y modelos de aeronave — repaso complementario

Este tema estaba anotado para preparar el día 3. No se proporcionó una lista de frecuencias estadísticas de movimientos; los siguientes son **referencias de familiarización**, no un ranking de los más habituales de SULS.

### Aeródromos del entorno y la red nacional

| Indicador OACI | Referencia para reconocerlo |
|---|---|
| **SULS** | Laguna del Sauce / C. Curbelo: dependencia en habilitación. |
| **SUMU** | Carrasco: coordinación APP y apoyo meteorológico OMA/OVM. |
| **SUAA** | Ángel Adami / Melilla. |
| **SUPE** | El Jagüel / Punta del Este: referencia de los encaminamientos VFR desde el este. |
| **SUCA** | Colonia / Laguna de los Patos. |
| **SUDU** | Durazno / Santa Bernardina. |
| **SUSO** | Salto / Nueva Hespérides. |
| **SUPU** | Paysandú / Tydeo Larre Borges. |
| **SURV** | Rivera / Oscar Gestido. |

Para cada origen/destino que aparezca en las fajas: poder ubicarlo, reconocer la ruta de entrada/salida, dependencia adyacente y tiempo aproximado que esa trayectoria deja para coordinar. Los nombres e indicadores sirven para orientarse; los servicios y horarios se comprueban en la publicación aplicable.

### Modelos para practicar reconocimiento

Correspondencias tomadas del Doc. 8643 aportado; no se asignan velocidades fijas ni categorías por apariencia.

| Designador | Modelo / familia | Grupo para comparar performance |
|---|---|---|
| **C172** | Cessna 172 / Skyhawk | Monomotor de pistón. |
| **B350** | Beech Super King Air 350 | Bimotor turbohélice. |
| **C56X** | Cessna Citation Excel / XLS | Jet ejecutivo bimotor. |
| **E55P** | Embraer Phenom 300 | Jet ejecutivo bimotor. |
| **A320** | Airbus A320 | Jet de transporte bimotor. |
| **B738** | Boeing 737-800 | Jet de transporte bimotor. |

El objetivo es anticipar **velocidad de aproximación, alcance al precedente, ascenso inicial, tiempo de ocupación de pista y estela**. Dos aeronaves a igual distancia no necesariamente dejan el mismo tiempo disponible. La categoría de estela, la categoría de aproximación y la performance efectiva son datos distintos y deben comprobarse para la aeronave concreta.

---

## 4. Integración de las lecturas

### Llegada IFR con meteorología cambiante

1. APP secuencia y encamina a la aproximación coordinada; TWR mantiene pista y situación local actualizadas.
2. TWR recibe la transferencia conforme al POI y conoce trayectoria final y frustrada.
3. Si cambian viento, visibilidad, nubes o fenómenos, transmite la información significativa y coordina con APP/MET.
4. Si la lluvia afecta la pista, obtiene de CAISA el RCR pertinente; no deduce RWYCC del METAR.
5. Si se reporta cizalladura, activa el circuito TWR → EMA → OVM y mantiene informados a los afectados.
6. Ante frustrada, avisa a APP y transfiere según el procedimiento; cualquier trayectoria distinta requiere coordinación.

### Pista mojada y reporte de frenado

**METAR** explica el tiempo; **RCR** informa la superficie; **reporte del piloto** aporta una observación de frenado. TWR transmite los datos y deriva el reporte para reevaluación. CAISA evalúa y asigna la clave, MET gestiona la información meteorológica y la tripulación evalúa su performance.

### Falla de equipo durante una secuencia

Identificar qué función se perdió: una pantalla radar de TWR, todo el radar, la pantalla meteo, los sensores o el enlace de mensajes. Cada falla tiene una respuesta diferente: **coordinación telefónica**, **suspensión temporal de despegues**, **uso de METAR/SPECI**, **instrumental de respaldo** o **gestión de transmisión alternativa/PRENOTAM**, según el caso. No tratar todas las fallas como si fueran equivalentes.

### Actividad COA que afecta el entorno de SULS

Recibir y confirmar condición del vuelo y espacio requerido; coordinar con las dependencias afectadas; identificar quién conduce la operación y qué restricciones afectan las llegadas, salidas o circuitos. Si además hay meteorología adversa o una frustrada probable, incorporarla a la coordinación antes de comprometer la secuencia.

## 5. Repaso activo del día 3

1. ¿Quién secuencia las llegadas IFR y quién establece la pista en uso?
2. ¿Qué condiciones permiten reducir de 10 a 7 NM el espaciamiento del POI?
3. ¿Cuándo se transfiere una llegada IFR, una visual IFR y una VFR?
4. ¿Qué debe verificarse antes de transferir una salida IFR o VFR?
5. ¿Qué hace TWR ante una frustrada publicada y ante una arremetida que no puede seguirla?
6. ¿Qué significan RCR, RWYCC y RVR? ¿Quién asigna la clave de pista?
7. ¿Qué representa `5/2/5` y cuál es el umbral entre mojada y agua estancada?
8. ¿Cómo se leen `BR`, `BKN008`, `22012G22KT` y `Q1012`?
9. ¿Por qué un METAR con BKN008 y 5 km no basta para afirmar que puede hacerse VFR ordinario o aterrizar IFR?
10. ¿Qué diferencia hay entre IAF, IF, FAF, MAPt y MAHF?
11. ¿En qué se distinguen OCA/H, DA/H y MDA/H?
12. ¿Qué hacen EMA, OMA y OVM? ¿SULS tiene TREND según las fuentes consultadas?
13. ¿Cuál es el circuito completo de un reporte de cizalladura y quién cancela el aviso?
14. ¿Qué se hace si persiste una discrepancia sobre la base de nubes?
15. ¿Qué respaldo se utiliza si fallan los presentadores meteo? ¿Y si fallan AWOS y Vaisala?
16. ¿Qué significa COA y en qué situaciones ATS debe avisarle?
17. ¿Qué diferencia hay entre VMO/EVMO y VPA/VPO?
18. ¿Qué VMO exceptúa la carta de presentar FPL? ¿La excepción elimina la coordinación?
19. ¿Quién otorga PSA/PSV y qué hace ATS si el permiso no figura en el FPL?
20. ¿Quién controla una interceptación y cómo se coordinan ZOM y fallas de comunicaciones?

<details><summary>Ver respuestas breves</summary>

1. APP determina la secuencia; TWR establece la pista y mantiene informada a APP.
2. RWY 08 o 19, aeronaves de misma performance, coordinación y aceptación de TWR; considerar estela y velocidades.
3. IFR establecida en final y autorizada a completar; visual IFR después de aceptación con posición y altitud; VFR antes del ingreso previsto al ATZ, cuyo ingreso decide TWR.
4. IFR libre de tránsito, FPL activado y correlacionado; VFR libre de tránsito, respondedor correlacionado y Modo C verificado.
5. Frustrada publicada: informar y transferir inmediatamente después de iniciada. Si no puede cumplirla: avisar y coordinar las instrucciones con APP.
6. Informe de estado de pista; clave por tercio; alcance visual en pista. CAISA evalúa y asigna RWYCC; TWR lo transmite.
7. Claves del primer, segundo y tercer tercio en el sentido de la pista informada. Hasta 3 mm de agua: mojada; más de 3 mm: agua estancada.
8. Neblina; muy nuboso a 800 ft sobre el aeródromo; viento desde 220° a 12 kt con ráfagas de 22; QNH 1012 hPa.
9. El techo está bajo el umbral ordinario del LAR 91.300(b) aportado; VFR especial necesita las condiciones y autorización aplicables. Para IFR hay que comprobar procedimiento, mínimos, equipo y referencias visuales.
10. Inicio de aproximación; punto intermedio; inicio del tramo final; punto de frustrada; punto de espera de la frustrada.
11. OCA/H es franqueamiento de obstáculos; DA/H es altitud/altura de decisión; MDA/H es altitud/altura mínima de descenso. No se intercambian automáticamente.
12. EMA observa y emite METAR/SPECI; OMA proporciona pronósticos/documentación; OVM vigila y gestiona avisos. Las fuentes consultadas asignan TREND a SUMU y señalan Nil para SULS.
13. Aeronave → TWR → EMA-SULS → OVM-SUMU; EMA incorpora el reporte y OVM emite aviso. EMA/OVM cancelan por los supuestos del anexo: dos horas desde el último reporte o reporte de no afectación canalizado por TWR.
14. TWR obtiene un reporte de aeronave y lo comunica a MET; si persiste la diferencia, el anexo dispone la menor altura estimada o reportada.
15. TWR utiliza METAR/SPECI y avisa a EMA. Si fallan ambas estaciones automáticas, EMA utiliza instrumental convencional y solicita PRENOTAM.
16. Centro de Operaciones Aéreas de la FAU. ATS informa incumplimientos injustificados, aeronaves no identificadas e información de vuelos requerida por COA.
17. VMO es operación militar y EVMO su entrenamiento; este conserva obligación de FPL. VPA sigue normas generales y VPO necesita apartamientos por su función policial.
18. MARTE, TIGRE, SANITARIO y RESCATE en los supuestos de la carta. Se mantiene coordinación; RESCATE también puede coordinarse por CCR Carrasco.
19. COA. ATS consulta a la dependencia transferidora y/o aeronave y, si no obtiene la información, notifica inmediatamente a COA; verifica el permiso contra los datos del COA.
20. COA conduce la interceptación y coordina con ATS cuanto antes. ZOM: ATS–COA salvo carta específica. Medios: HL, luego DL, luego telefonía convencional/celular.

</details>

### Ejercicio de reconstrucción

Sin mirar, explicar una llegada IFR a SULS con pista mojada, una aeronave que reporta cizalladura y una posible frustrada. Nombrar quién actúa en cada paso, qué dato transmite y qué información falta antes de autorizar. Después agregar una actividad coordinada por COA y explicar qué parte de la secuencia habría que reconsiderar.

## Fuentes y pendientes concretos

- `Notas dia 3.md` y `Notas día 2.md`, del vault **Habilitación TWR**: alcance de las lecturas. Las notas del día 3 incorporan la confirmación posterior del entrenando sobre contenidos y práctica.
- **ATS-PATS-007 APP-TWR SULS v2.0**, encabezado ATS-PATS-07, 20/11/2025: §§2–7, coordinación y transferencias.
- **ATS-PATS-02 Procedimiento GRF SULS v1.0** y **CAO TWR SULS–CAISA, Anexo 10**: superficie de pista.
- **OACI Anexo 3, edición 2021**, capítulo 4 y apéndice 3; **LAR 91, diciembre 2023**, §§91.160 y 91.300; **MATS v2.0**, §7.13: base del repaso meteo/VFR.
- **CAO ATS–INUMET 2024–2026**, revisión 01, julio 2024, §§2–6; **CAO INUMET Anexo II SULS**, efectivo 01/11/2025, §§2–9: roles, instrumental, comunicaciones y contingencias. PDFs escaneados leídos mediante OCR, con comprobación visual del circuito de cizalladura.
- **CAO DCA–COA**, efectiva 20/11/2023 por Circular Interna 018/2023: §§3–7 y Anexo 2; comprobación visual de las disposiciones VMO.
- **Doc. 8643**, copia aportada: correspondencia entre designadores y modelos; **Doc. 9613** y **Doc. 8168**: referencias de navegación/procedimientos del material previo.
- [DINACIA — AIP SULS AD 2.5](https://www.dinacia.gub.uy/node/579), página y paquete consultados el 07/09/2026: comprobación de referencia de cartas e información meteorológica local.
- `03 - Primeros cuatro días OJT.md`: relación con el plan guía, sin marcar actividades como cumplidas.

Pendientes de confirmación documental/local: renovación de la CAO general meteo de 2024, frecuencia de contingencia TWR–EMA y lista concreta de aeródromos/modelos que el instructor considere habituales. El plan de emergencia permanece como lectura indicada para el día 4.

> Material de estudio basado en las copias indicadas. Para operar prevalecen la documentación y cartas vigentes, los NOTAM y los procedimientos aplicables.
