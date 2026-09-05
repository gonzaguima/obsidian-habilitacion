# Lecturas — APP–TWR, GRF, METAR y aproximaciones SULS

> Resumen de las lecturas anotadas al finalizar el día 2: procedimientos APP–TWR SULS, GRF y coordinación con CAISA, lectura de METAR y cartas de aproximación instrumental de SULS.
> Es material de estudio. Para operar prevalecen la AIP, los NOTAM, el ATIS y los procedimientos vigentes.

## Para ubicarse rápido

- **APP–TWR:** quién encamina, coordina y transfiere cada llegada o salida.
- **GRF:** CAISA evalúa y genera el RCR; TWR recibe, actualiza y transmite la información.
- **METAR:** leer siempre en el mismo orden y traducir cada grupo a una consecuencia operativa.
- **Cartas:** identificar procedimiento, ayudas, altitudes, mínimos y aproximación frustrada antes de mirar detalles secundarios.

---

## 1. Procedimiento APP–TWR SULS

Fuente: **ATS-PATS-007, versión 2.0, 20/11/2025**.

### Reparto básico de responsabilidades

| Tema | APP Carrasco | TWR SULS / TWLS |
|---|---|---|
| Secuencia de llegadas IFR | La determina y encamina al IAF | Establece pista en uso e informa cambios |
| Aproximación visual IFR | Puede autorizarla, con aceptación previa de TWR | Acepta la transferencia con posición y altitud conocidas |
| Salidas IFR | Proporciona/coordina SID o instrucciones | Encaminamiento a pista, despegue y transferencia posterior |
| Llegadas VFR | Encaminamiento inicial y transferencia antes del ATZ | Decide cuándo autoriza el ingreso al ATZ |
| Salidas VFR | Recibe el tránsito transferido | Encaminamiento inicial y coordinación si puede afectar IFR |

### Llegadas IFR

- APP establece la secuencia para la pista en uso.
- Por necesidad operacional o solicitud, puede emplearse otra pista con coordinación y aceptación de TWR.
- APP encamina al **IAF del procedimiento de la pista en uso**; otro punto requiere coordinación previa.
- TWR establece la pista en uso, mantiene informada a APP y actualiza el FDD.
- Para una aproximación visual IFR debe existir aceptación previa de TWR y cumplirse las condiciones meteorológicas y visuales aplicables.
- La aceptación de una aproximación visual debe incluir **ubicación y altitud**.

#### Espaciamiento de llegadas

- Regla del procedimiento: APP asegura normalmente **10 NM** entre la aeronave que aterriza y la siguiente.
- Para aproximaciones a RWY **08 o 19**, con aeronaves de igual performance, puede reducirse a **7 NM**, previa coordinación y aceptación de TWR.
- Deben considerarse velocidad de aproximación y estela turbulenta.

#### Aproximación frustrada o arremetida

- Si se ejecuta la frustrada publicada, TWR avisa a APP cuanto antes y transfiere control y comunicaciones inmediatamente después de iniciada.
- Si la aeronave no puede aterrizar pero tampoco puede cumplir la frustrada publicada, TWR informa la arremetida y coordina con APP las instrucciones.
- Cualquier maniobra que altere la trayectoria de aproximación final debe coordinarse con APP.

### Salidas IFR

- TWR encamina a la pista en uso; otra pista requiere coordinación con APP.
- Si sale una aeronave rápida detrás de una lenta, TWR debe advertirlo a APP al coordinar las instrucciones o tan pronto como sea posible.
- Se utilizan las SID de la pista en uso previa coordinación. Si no se aplica una SID, TWR solicita instrucciones específicas a APP.
- TWR comunica el tiempo que necesita para la salida; si el tránsito no puede cumplirlo, pide nuevas instrucciones.

### Llegadas VFR

| Procedencia | Encaminamiento indicado | Altitud máxima/objetivo |
|---|---|---:|
| VFR1 | Minas → Pan de Azúcar vía VFR3 | Descenso hasta 2.000 ft MSL |
| Alternativa VFR2 | San Ramón → Frigorífico → desembocadura del Solís Grande | Descenso hasta 2.000 ft |
| Oeste/costa | Línea de costa → desembocadura del Solís Grande | Máximo 2.000 ft |
| Este | Costa → SUPE | Descenso hasta 2.000 ft |
| Otros sectores | Minas, Pan de Azúcar, Puente o lo coordinado | Descenso hasta 2.000 ft |

Si el VFR puede ser factor para una operación IFR, APP y TWR coordinan punto y momento de encaminamiento y transferencia.

### Salidas VFR

Sin coordinación adicional, siempre que no exista conflicto que obligue a coordinar:

- oeste/costa: Pan de Azúcar y luego desembocadura del Solís, hasta **1.000 ft**;
- VFR1: por VFR2 hacia San Ramón o VFR3 hacia Minas, vía Pan de Azúcar o directo, hasta **2.000 ft**;
- este/costa: desembocadura del arroyo Maldonado o Laguna, hasta **2.000 ft**;
- otros destinos: trayectoria de salida hasta **2.000 ft**, considerando posibles conflictos IFR.

En todos los casos se proporciona la información de tránsito VFR pertinente.

### Salida frente a llegada en IMC

| Relación de performance | Condición indicada en el POI |
|---|---|
| Misma performance | Puede considerarse la salida si la llegada está a **5 NM o más** del umbral. |
| Saliente más rápida | Se aplica la condición de **5 NM**. |
| Saliente más lenta que la llegada | La llegada debe estar a **10 NM o más** del umbral. |

Estos valores no reemplazan separación por estela, ocupación de pista ni el juicio operacional exigido por la situación.

### Coordinaciones

- TWR puede pedir con antelación otro espaciamiento de llegadas o una cesión temporal de espacio aéreo.
- VFR especial, inspecciones, entrenamiento que afecte ambos sectores y situaciones no previstas requieren coordinación oral.
- Para utilizar **2.500 ft dentro del ATZ**, TWR coordina previamente con APP.
- La coordinación silenciosa usa el campo ruta y las funciones `announce` y `transfer`.
- Si no existe acuse de la coordinación silenciosa, se recurre a medios orales.
- La coordinación o transferencia silenciosa **no implica cesión de espacio aéreo**.

### Transferencia de control y comunicaciones

La comunicación se transfiere en el mismo punto o momento que el control. Una transferencia anticipada no cede por sí sola el espacio aéreo.

| Operación | Momento/condición |
|---|---|
| Llegada IFR | Establecida en final y autorizada a completar la aproximación. |
| Llegada IFR visual | Después de que TWR acepte; deben conocerse ubicación y altitud. |
| Llegada VFR | Antes del punto previsto de ingreso al ATZ; TWR decide el ingreso. |
| Salida IFR | Inmediatamente después del despegue, libre de tránsito, con FPL activado y correlacionado. |
| Salida VFR | Libre de tránsito, respondedor correlacionado con distintivo y Modo C verificado. |

Si la aeronave no establece contacto, la dependencia receptora informa a la transferidora para adoptar medidas conjuntamente.

### FPL, meteorología y contingencia

- TWR aprueba FPL de salidas y sobrevuelos que afecten su ATZ y expide el SSR asignado por AIRCON.
- Coordina los VFR especiales después de su autorización por APP.
- Corrige los FPL de salida que estén en cola `Q` para ingresarlos al sistema.
- APP y TWR se mantienen mutuamente informados de meteorología significativa.
- Sin presentación radar en TWR: se coordinan por teléfono directo todas las llegadas y salidas.
- Ante falla radar total en APP y TWR: TWR suspende temporalmente los despegues y coordina las medidas siguientes.
- Sin impresión automática de fajas: APP realiza las transferencias oralmente.

---

## 2. GRF — estado de la superficie de pista

Fuentes: **ATS-PATS-02 GRF SULS v1.0** y **Anexo 10 de la CAO TWR SULS–CAISA**.

### Conceptos

- **GRF:** formato mundial de notificación del estado de pista.
- **RCR:** *Runway Condition Report*, informe de estado de pista.
- **RWYCC:** clave numérica que expresa, por cada tercio, el efecto esperado de la superficie sobre frenado y control lateral.
- **RCAM:** matriz utilizada para asignar o ajustar el RWYCC.

El RWYCC se transmite como tres cifras, una por tercio, en el orden de la pista informada: `n/n/n`. El sentido importa: si cambia el designador de pista, también cambia el orden de lectura de los tercios.

### Responsabilidades locales

1. El Oficial de Operaciones de **CAISA** inspecciona y evalúa la pista conforme al LAR 153 y la circular aplicable.
2. CAISA documenta la evaluación en el formulario de estado de pista.
3. CAISA transmite a TWR, por canal 1 **160,290 MHz**, las claves de cada tercio.
4. TWR transmite la información a las tripulaciones por frecuencia aeronáutica y mantiene actualizados los medios correspondientes.

La CAO aclara que en la comunicación inicial CAISA transmite las **claves por tercio**, no necesariamente porcentaje, espesor y descripción. El mensaje completo ingresado en el sistema contiene esos elementos para el informe detallado o el ATIS.

### Escala RWYCC

| RWYCC | Acción de frenado asociada |
|---:|---|
| 6 | Pista seca; no tiene equivalencia de reporte de frenado. |
| 5 | Buena |
| 4 | Buena a mediana |
| 3 | Mediana |
| 2 | Mediana a deficiente |
| 1 | Deficiente |
| 0 | Inferior a deficiente |

Relaciones importantes para SULS:

- `6`: seca;
- `5`: mojada con humedad visible o agua de hasta **3 mm**;
- `3`: mojada y resbaladiza;
- `2`: agua estancada de más de **3 mm**;
- `1`: hielo;
- `0`: hielo mojado, agua sobre nieve compacta o nieve sobre hielo, según la matriz.

### Lectura resumida por frecuencia

- `6/6/6`: normalmente no se lee, salvo que represente una mejora reciente de mojada a seca; en ese caso, “6/6/6, seca”.
- `5/5/5`: “5/5/5, mojada”.
- `6/5/5`: “6/5/5, seca, mojada, mojada”.
- `5/2/5`: “5/2/5, mojada, agua estancada, mojada”.

### Estructura del RCR completo

Ejemplo del procedimiento:

`SULS 11041600 08 5/2/5 100/50/50 NR/04/NR MOJADA/AGUA ESTANCADA/MOJADA`

Se interpreta como:

- `SULS`: aeródromo;
- `11041600`: fecha y hora de observación;
- `08`: pista informada;
- `5/2/5`: RWYCC por tercio;
- `100/50/50`: porcentaje de cobertura por tercio;
- `NR/04/NR`: profundidad; `04` equivale a 4 mm y `NR` a no notificado;
- descripciones: contaminante o condición de cada tercio.

Al transmitir un informe completo debe conservarse el orden de los tres tercios y no completar por deducción un dato marcado `NR`.

### Reportes de frenado de pilotos

El reporte del piloto puede motivar una reevaluación o disminución de la clave conforme a la RCAM. Si el piloto utiliza términos no alineados con la escala OACI, TWR solicita que exprese la eficacia de frenado en la escala de **0 a 5**.

TWR transmite el reporte sin transformarlo en una evaluación propia de la pista: la evaluación formal corresponde al operador del aeródromo.

### Claves para no confundirse

- `WET/MOJADA` no equivale automáticamente a agua estancada.
- El límite decisivo es **hasta 3 mm** frente a **más de 3 mm**.
- El RWYCC no es un coeficiente de fricción medido.
- Cada cifra corresponde a un tercio, no a una pista distinta.
- La condición comunicada debe relacionarse con la pista y la hora del informe.

---

## 3. Lectura de METAR y SPECI

### Orden fijo de decodificación

Leer siempre en esta secuencia:

1. tipo de informe: `METAR` o `SPECI`;
2. aeródromo;
3. día y hora UTC;
4. viento;
5. visibilidad predominante;
6. RVR, si aparece;
7. tiempo presente;
8. nubosidad y techo;
9. temperatura/punto de rocío;
10. QNH;
11. información suplementaria y tendencia.

### Viento

Ejemplo: `22012G22KT` = viento desde 220°, 12 kt, ráfagas 22 kt.

- `VRB`: dirección variable.
- `00000KT`: calma.
- `dddVddd`: variación direccional significativa.
- Para seleccionar pista interesan componente de frente/cola y componente cruzada, usando viento medio y ráfaga cuando corresponda.

### Visibilidad y RVR

- Cuatro cifras, por ejemplo `5000`: visibilidad predominante de 5.000 m.
- `9999`: 10 km o más.
- `CAVOK`: visibilidad de 10 km o más, sin nubosidad ni tiempo significativo dentro de los criterios establecidos; no significa simplemente “buen tiempo”.
- `R08/1200U`: RVR de RWY 08, 1.200 m, con tendencia ascendente.
- Tendencias RVR: `U` aumenta, `D` disminuye, `N` sin cambio significativo.

### Tiempo presente

| Código | Significado |
|---|---|
| `-` / `+` | Débil / fuerte |
| `RA` | Lluvia |
| `DZ` | Llovizna |
| `TS` | Tormenta |
| `SH` | Chubascos |
| `FG` | Niebla |
| `BR` | Neblina/bruma húmeda |
| `HZ` | Calima |

Los códigos pueden combinarse: `-RA`, `TSRA`, `SHRA`.

### Nubosidad y techo

- `FEW`: 1–2 octas.
- `SCT`: 3–4 octas.
- `BKN`: 5–7 octas.
- `OVC`: 8 octas.
- Las tres cifras expresan centenas de pies: `BKN008` = base a 800 ft.
- El **techo** es la base de la capa más baja `BKN` u `OVC`, o la visibilidad vertical `VV` cuando el cielo está oscurecido.
- `CB` y `TCU` identifican cumulonimbus y cúmulos de gran desarrollo vertical.

### Temperatura, punto de rocío y QNH

- `18/16`: temperatura 18 °C y punto de rocío 16 °C.
- `M02`: −2 °C.
- Una diferencia pequeña entre temperatura y punto de rocío indica aire próximo a saturación y favorece niebla o nubosidad baja, pero no basta por sí sola para afirmar que se formará.
- `Q1016`: QNH 1016 hPa.

### Tendencia

- `NOSIG`: no se prevén cambios significativos durante el período de tendencia.
- `BECMG`: cambio gradual o esperado hacia nuevas condiciones.
- `TEMPO`: fluctuaciones temporarias.

### Ejemplo integrado

`METAR SULS 041600Z 22012G22KT 5000 -RA BKN008 18/16 Q1012 TEMPO 2000 RA`

Lectura: informe de SULS del día 4 a las 16:00 UTC; viento 220°/12 kt con ráfagas de 22; visibilidad 5 km; lluvia débil; techo BKN a 800 ft; 18 °C, punto de rocío 16 °C; QNH 1012; temporalmente visibilidad de 2 km con lluvia.

### Traducción operacional

Después de decodificar, responder:

- ¿qué pista resulta más favorable y qué componentes genera el viento?;
- ¿hay techo/visibilidad que afecte VFR, VFR especial o el procedimiento IFR?;
- ¿corresponde RVR o procedimiento de baja visibilidad?;
- ¿hay tormenta, cortante, lluvia fuerte u otro fenómeno significativo?;
- ¿la pista puede estar mojada o contaminada y existe RCR vigente?;
- ¿hubo un cambio que APP, CAISA, ATIS o las aeronaves deban conocer?

---

## 4. Cartas de aproximación instrumental SULS

Fuente contrastada: **AIP Uruguay SULS AD 2.5**, publicada el 13/05/2026. Las cartas individuales muestran fecha **20 MAR 2025** y AIRAC AIP AMDT NR 01 dentro del paquete consultado.

### Procedimientos publicados

| Tipo | RWY 01 | RWY 08 | RWY 19 | RWY 26 |
|---|---|---|---|---|
| RNP Z | Sí | Sí | Sí | Sí |
| VOR Z | Sí | Sí | Sí | Sí |

En el paquete vigente consultado aparecen ocho aproximaciones: cuatro RNP Z y cuatro VOR Z. No deben estudiarse como vigentes cartas antiguas NDB, RNAV (GNSS) con otra identificación o procedimientos incluidos en carpetas de **proyecto**.

### Método de lectura de cada carta

1. Confirmar aeródromo, procedimiento, pista y fecha/enmienda.
2. Verificar frecuencias, elevación del aeródromo/umbral y altitud de transición.
3. Identificar IAF, IF, FAF/FAP, MAPt y MAHF.
4. Seguir rumbos, distancias, altitudes y restricciones de velocidad.
5. Revisar perfil vertical y gradiente/ángulo de descenso.
6. Leer OCA/H, DA/H o MDA/H y visibilidad para la categoría correspondiente.
7. Memorizar conceptualmente la frustrada: rumbo inicial, restricciones, viraje y espera.
8. Revisar obstáculos, zonas especiales y notas.

### Datos comunes

- TWR: **118,3 / 122,1 MHz**.
- ATIS: **132,1 MHz**.
- VOR/DME LDS: **117,6 MHz**.
- Altitud de transición: **3.000 ft**.
- Las aproximaciones publicadas utilizan una trayectoria vertical nominal de aproximadamente **3° / 5,2 %**.
- El circuito de espera de las frustradas converge normalmente en **RENOM** o **BUSPI**, según procedimiento.

### Mínimos de aproximación directa

Los valores siguientes son una ayuda de estudio tomada de las cartas consultadas; deben verificarse siempre en la carta vigente y para la categoría real de aeronave.

| Procedimiento | Mínimo publicado | Visibilidad |
|---|---:|---:|
| RNP Z RWY 01 — LNAV/VNAV | 345 ft OCA / 250 ft OCH | 1.300 m |
| RNP Z RWY 01 — LNAV | 440 / 345 ft | 1.600 m |
| RNP Z RWY 08 — LNAV/VNAV | 380 / 285 ft | 900 m; 1.400 m ALS inoperativo |
| RNP Z RWY 08 — LNAV | 480 / 385 ft | 1.400 m; 1.800 m ALS inoperativo |
| RNP Z RWY 19 — LNAV/VNAV | 371 / 296 ft | 900 m; 1.400 m ALS inoperativo |
| RNP Z RWY 19 — LNAV | 460 / 385 ft | 1.400 m; 1.800 m ALS inoperativo |
| RNP Z RWY 26 — LNAV/VNAV | 322 / 250 ft | 800 m; 1.300 m ALS inoperativo |
| RNP Z RWY 26 — LNAV | 430 / 358 ft | 1.300 m; 1.700 m ALS inoperativo |
| VOR Z RWY 01 | 460 / 365 ft | 1.700 m |
| VOR Z RWY 08 | 530 / 435 ft | 1.600 m; 2.000 m ALS inoperativo |
| VOR Z RWY 19 | 540 / 465 ft | 1.800 m; 2.200 m ALS inoperativo |
| VOR Z RWY 26 | 480 / 408 ft | 1.500 m; 1.900 m ALS inoperativo |

`OCA/H` expresa altitud/altura de franqueamiento de obstáculos. No debe confundirse automáticamente con una DA/H o MDA/H operacional sin aplicar los criterios del operador y de la aeronave.

### Aproximaciones frustradas — estructura

| Procedimiento | Acción inicial resumida | Destino de la espera |
|---|---|---|
| RNP Z 01 | Ascender a 3.000 ft; rumbo 010° hasta LS006, cruzarlo a 850 ft o más; luego rumbo 050° | BUSPI |
| RNP Z 08 | Rumbo 084° hasta LS013 a 1.500 ft o más; rumbo 180° a LS014 a 2.000 ft o más; luego 224° | RENOM |
| RNP Z 19 | Ascender a 3.000 ft con rumbo 184° | RENOM, espera por derecha; máx. 230 kt |
| RNP Z 26 | Rumbo 264° hasta LS027 a 1.200 ft o más; luego viraje izquierda rumbo 165° | RENOM |
| VOR Z 01 | Rumbo 015° hasta 600 ft; viraje derecha para interceptar RDL 040 LDS | BUSPI; máx. 210 kt |
| VOR Z 08 | RDL 091 hasta 1.500 ft; viraje derecha rumbo 239° para interceptar RDL 184 | RENOM; máx. 230 kt |
| VOR Z 19 | Directo por RDL 184 LDS, ascendiendo a 3.000 ft | RENOM |
| VOR Z 26 | RDL 251 hasta pasar 1.200 ft; izquierda rumbo 166° para interceptar RDL 184 | RENOM; máx. 210 kt |

Este cuadro sirve para reconocer la lógica; la autorización y ejecución deben respetar el texto y la representación completa de la carta.

### Qué necesita saber TWR

Para cada aproximación conviene reconocer inmediatamente:

- pista y tipo de procedimiento;
- punto y trayectoria de final;
- FAF/FAP y MAPt;
- altitud mínima y condición meteorológica relevante;
- trayectoria inicial de frustrada y posible conflicto con salidas u otros circuitos;
- restricciones de velocidad;
- ayuda requerida y estado operativo;
- momento de transferencia previsto por el POI APP–TWR.

---

## 5. Integración de las lecturas

### Llegada IFR normal

1. APP secuencia y encamina al procedimiento.
2. TWR mantiene pista, meteorología, RCR y tránsito local actualizados.
3. APP transfiere cuando la aeronave está establecida en final y autorizada a completar.
4. TWR informa cambios esenciales, controla pista y expide aterrizaje cuando sea seguro.
5. Si frustra, TWR informa y transfiere de inmediato conforme al procedimiento.

### Pista mojada con RCR

1. CAISA inspecciona y asigna RWYCC.
2. CAISA transmite las claves por tercio a TWR.
3. TWR actualiza el sistema/ATIS y transmite el RCR pertinente.
4. APP recibe cualquier cambio significativo que afecte aproximaciones o secuencia.
5. La tripulación combina METAR, RCR, performance y mínimos; ATC no sustituye esa evaluación operacional.

### Cambio meteorológico durante la aproximación

1. Identificar qué cambió: viento, visibilidad/RVR, techo, fenómeno o pista.
2. Compararlo con la información ya recibida por la aeronave.
3. Transmitir el cambio significativo sin demora.
4. Actualizar/coordinar con APP, ATIS, INUMET o CAISA según corresponda.
5. Anticipar cambio de pista, demora, frustrada o nueva inspección GRF.

---

## Repaso activo

1. ¿Quién determina la secuencia IFR y quién establece la pista en uso?
2. ¿Qué separación de llegadas prevé el POI y cuándo puede reducirse?
3. ¿Cuándo transfiere APP una llegada IFR, una visual IFR y una VFR?
4. ¿Qué debe verificar TWR antes de transferir una salida IFR o VFR?
5. ¿Cuándo se requiere coordinación para utilizar 2.500 ft en el ATZ?
6. ¿Quién evalúa la pista y quién transmite la información a las aeronaves?
7. ¿Qué significa cada parte de `5/2/5`?
8. ¿Cuál es la diferencia entre pista mojada y agua estancada en GRF?
9. ¿Cómo se reconoce el techo en un METAR?
10. ¿Qué diferencia hay entre visibilidad predominante y RVR?
11. ¿Qué ocho aproximaciones aparecen publicadas para SULS?
12. ¿Qué cuatro elementos de una frustrada deben identificarse antes de iniciar la aproximación?

<details><summary>Ver respuestas</summary>

1. APP determina la secuencia; TWR establece la pista y mantiene informada a APP.
2. Normalmente 10 NM; 7 NM para RWY 08 o 19, misma performance y aceptación previa de TWR.
3. IFR establecida en final; visual IFR después de aceptación con posición/altitud; VFR antes del ingreso previsto al ATZ.
4. Que esté libre de tránsito y el FPL/respondedor estén activados y correlacionados; para VFR, además Modo C verificado.
5. Siempre: TWR debe coordinarlo previamente con APP.
6. CAISA evalúa y documenta; TWR recibe y transmite por frecuencia aeronáutica.
7. Son las claves de los tercios primero, segundo y tercero en el sentido de la pista informada.
8. Mojada admite agua de hasta 3 mm y normalmente RWYCC 5; más de 3 mm es agua estancada, RWYCC 2.
9. Es la capa más baja BKN/OVC o VV.
10. La primera describe la visibilidad general del aeródromo; RVR describe el alcance visual a lo largo de una pista.
11. RNP Z y VOR Z para cada una de las pistas 01, 08, 19 y 26.
12. Rumbo/trayectoria inicial, altitudes o gradiente, viraje/restricciones y punto de espera final.

</details>

## Fuentes

- ATS-PATS-007, *Procedimientos operativos APP/TWR SULS*, v2.0, 20/11/2025.
- ATS-PATS-02, *Condiciones de la superficie de pista (GRF) SULS*, v1.0.
- CAO TWR SULS–CAISA, Anexo 10, procedimiento local GRF.
- AIP Uruguay, SULS AD 2.5, publicación consultada del 13/05/2026.
- OACI Anexo 3 y material meteorológico disponible, para estructura y códigos METAR/SPECI.

