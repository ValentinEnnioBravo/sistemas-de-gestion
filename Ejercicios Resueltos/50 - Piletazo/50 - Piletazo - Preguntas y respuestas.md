# Ej 50 · Piletazo (+Awado): preguntas y respuestas

Consultas hechas mientras se resuelve el ejercicio, con la respuesta concreta de cada una. Los criterios siguen las notas del apunte ([[06 Costos, producción y stock]], [[07 Precio - markup, margen, equilibrio y elasticidad]], [[11 Reinversión y desinversión]], [[15 WACC y tasa de descuento]]).

**Supuestos a dejar escritos en la hoja:**
- Los **$50M con IVA 21%** son solo la máquina. Traslado e instalación (5% del VO sin IVA) van aparte.
- Año comercial de **360 días**: 7% bimestral → 6 períodos por año.
- El **estudio del CONICET ($20M)** ya se contrató → **costo hundido**, no va al flujo.
- Sueldos × **13** (aguinaldo) × **1,45** (cargas sociales).
- Desperdicio: se **divide por (1 − d)**, no se multiplica por (1 + d).

---

## Datos ya procesados (para controlar la planilla)

### Inversión en la máquina

| Concepto | Cálculo | Importe |
|---|---|---:|
| Valor de origen (sin IVA) | 50.000.000 / 1,21 | 41.322.314 |
| Traslado e instalación | 5% × 41.322.314 | 2.066.116 |
| **Valor amortizable (ENAI año 0)** | | **43.388.430** |
| Depreciación anual (10 años) | 43.388.430 / 10 | **4.338.843** |

### Costo variable por caja

| Insumo | Cálculo | $/caja |
|---|---|---:|
| Resina | 1,35 kg / 0,99 × (400 / 5) | 109,09 |
| Pigmentos | 0,35 L / 0,95 × 150 | 55,26 |
| PVC | 5 kg / 0,80 × 580 | 3.625,00 |
| Barniz | 8 L / 0,95 × 268 | 2.256,84 |
| Caja + impresión | (63 + 44) / 0,99 | 108,08 |
| **Materia prima** | | **6.154,28** |
| MOD | | 115,00 |
| **CV unitario (sin comisión)** | | **6.269,28** |

- 8.000 cm³ = **8 litros**.
- La comisión del 1% sobre la venta neta es variable, pero es comercial: **no entra en el costo para el markup**.

### Estructura comercial (EAI fijo anual)

(1.500.000 + 2 × 400.000 + 10 × 300.000) × 13 × 1,45 = **99.905.000**

### Préstamo de $25M (francés, 3 cuotas anuales)

"La amortización de capital crece proporcionalmente" = **sistema francés**.

- TEA = 1,07⁶ − 1 = **50,073%** (no redondear)
- Cuota = **17.778.181**

| Año | Interés | Amortización |
|---|---:|---:|
| 1 | 12.518.259 | 5.259.922 |
| 2 | 9.884.456 | 7.893.725 |
| 3 | 5.931.828 | 11.846.353 |

### Tasa de descuento

- **Kd** = (2M × 18% + 6M × 35% + 5M × 30%) / 13M = **30,46%** (el préstamo de 25M **no entra**: es la deuda nueva del proyecto).
- Xd = 0,4 · Xe = 0,6 · T = 35%

| β | Ke = 5% + β × 20% | WACC |
|---|---:|---:|
| **1,8** (criterio de la planilla) | 41% | **32,52%** |
| 0,9 (lectura literal "al cruzar el eje y") | 23% | 21,72% |

---

## Trampas y dudas a definir antes de armar el flujo

> [!warning] ⚠️ Beta: la función no tiene esas raíces
> f(x) = x² − 1,3x + 0,9 tiene discriminante 1,69 − 3,6 < 0 → **no tiene raíces reales**. 0,5 y 1,8 serían raíces de x² − 2,3x + 0,9. Lo único que coincide es el producto: 0,5 × 1,8 = 0,9 = f(0), o sea donde la curva **cruza el eje y**.
> - "Más volátiles que el mercado" → β > 1 → **β = 1,8** (lo que usa la [Planilla amigo] y el apunte).
> - Lectura literal de "al cruzar el eje y" → β = 0,9, pero contradice "más volátiles".
> - Usar **1,8** y escribir el supuesto.

> [!warning] ⚠️ Markup del 70%
> Con la definición de clase: **P = CTu × 1,70**. La [Planilla amigo] lo toma como margen (P = CTu / 0,30). Ver [[07 Precio - markup, margen, equilibrio y elasticidad]] §2.
> - CTu = CVu + CF de producción / unidades **producidas** del año 1. Los costos comerciales y la comisión no entran.
> - Definir si entra la depreciación de la máquina nueva y la del estibador (⚠️ abierto en el apunte).
> - El precio se fija en el año 1 y se mantiene en los años 2–4. Año 5: **−5%**.

> [!note] Estibador (activo viejo traído al proyecto)
> VO = 200.000 × 10 = 2.000.000 · VL al inicio 1.200.000 → le quedan 6 cuotas. Partir en 80% / 20% (160.000 / 40.000 por año).
> - Año 2: se desinvierte el 20% → VL 240.000 − 2 × 40.000 = **160.000** como GND + ajuste. **Sin venta** (el enunciado no da precio).
> - Año 5: venta al 30% del VO. Definir si es 30% del VO total (600.000) o del 80% que queda (480.000).
> - Lo usamos 4 años pero se vende en el 5: ¿el año 5 deprecia?
> - ¿Va su VL como costo de oportunidad en el año 0? Ver [[10 Venta de activos y valor residual]].

> [!note] Otras a revisar
> - **Capacidad**: 500.000 cajas/mes sobra para cualquier demanda → no hay stock ni reinversión.
> - **IIBB 1%** y **comisión 1%** sobre la **venta neta** (bruta − 3% de descuento).
> - **WC**: cobro 10% contado / 10% a 30 / 80% a 70 días · CV a 60 días · MOD a mes vencido · CF a 30 días. El préstamo y sus intereses no van al WC.
> - **Elasticidad (punto 3)**: el precio baja 5% y las unidades se mantienen ante un mercado que cae 6% → E ≈ 6 / 5 = **−1,2** (lectura de la planilla, ver [[07 Precio - markup, margen, equilibrio y elasticidad]] §5).
> - **Precio de equilibrio de largo plazo (punto 4)**: el que da **VAN puro = 0** (Buscar objetivo).
> - **Punto 5**: todo a 60 días → cambia solo la cobranza del WC. Recalcular y comparar el VAN.

---

## 1. ¿Qué hago con el desperdicio? ¿Lo considero para la producción?

**Va al costo, no a las unidades.** El desperdicio es de los **insumos**: para que queden 5.000 g útiles de PVC tenés que comprar más. La **cantidad de cajas** no cambia.

- Por cada caja **comprás** q / (1 − d) de cada insumo, y pagás eso ([[06 Costos, producción y stock]] §3):
  - PVC: 5.000 / 0,8 = **6.250 g** → 6,25 × 580 = 3.625 por caja (sin desperdicio serían 2.900).
  - Caja de cartón: 1 / 0,99 = 1,0101 cajas → (63 + 44) × 1,0101 = 108,08.
- **Producción = ventas**: 60.000 · 95.000 · 150.000 · 190.000 · 190.000 cajas. No hay stock.
- **Capacidad**: las 500.000 cajas/mes son de producto terminado. El desperdicio no la baja, y sobra igual.
- En el flujo y en el WC usás el **CV unitario con el desperdicio adentro** (6.269,28) × cajas. No hay una fila aparte de desperdicio.

> [!warning] Error común
> Producir más cajas para "cubrir" el desperdicio (60.000 / 0,99…). El enunciado pone el desperdicio por insumo y por caja, no sobre el producto terminado.

## 2. La resina viene en paquetes de 5 kg: ¿el CVu va por paquete?

**No. Se prorratea por kilo:** 400 / 5 = **$80 el kilo**.

- Por caja: 1,35 / 0,99 = 1,3636 kg × 80 = **109,09**.
- El paquete es solo cómo te lo venden. Con miles de cajas al año, un paquete abierto alcanza para varias cajas: 5 / 1,3636 ≈ 3,7.
- Comprar un paquete entero por caja daría 400 por caja y estaría mal.
- Redondear los paquetes del año para arriba (60.000 × 1,3636 / 5 = 16.364 paquetes) cambia un solo paquete: es despreciable.
- Lo mismo con pigmentos y barniz: precio por litro × litros por caja.

## 3. El variable de los vendedores (1%): ¿lleva cargas sociales?

**Sí.** Es **salario variable**, o sea remunerativo, y paga cargas sociales igual que el sueldo ([[08 Sueldos, indemnizaciones y ahorros]] §Comisiones). Solo no las lleva si el enunciado dice "no remunerativo", como en Toldo.

$$\text{Comisión} = 1\% \times \text{Venta neta} \times 1{,}45$$

- **Base**: el enunciado dice "venta neta" → bruta − descuento − IIBB = **96,03% de la bruta** (ver pregunta 9). Jorge prefiere la venta neta comercial (97%, sin restar el IIBB), pero *"si te dice venta neta, venta neta"* ([[05 Ventas, IIBB e IVA]] §2). Escribir el supuesto.
- Es un **EAI** comercial: va al flujo, pero **no al costo para el markup**.
- "Correspondiente a sus cuentas asignadas" solo dice que cada venta tiene un único vendedor: la comisión no se duplica. El total sigue siendo 1% de toda la venta neta.
- El SAC (× 13) se aplica a los sueldos fijos. Sobre la comisión no se usa (supuesto; legalmente el aguinaldo también la incluye).

## 4. ¿Qué es el "descuento promedio empresa"?

Es la **rebaja comercial que la empresa les da a los clientes**, en promedio entre todos: por volumen, promociones, clientes grandes, etc. En vez de detallarla cliente por cliente, el enunciado da un promedio: **3% de la venta bruta**.

- **Baja el ingreso**: no se cobra. Bruta × 0,97 = venta neta **comercial** ([[05 Ventas, IIBB e IVA]] §1).
- Se muestra como una línea en negativo debajo de la venta bruta, o se pone directamente la venta neta. No es un egreso, como el sueldo.
- Sobre bruta − descuento se calcula el **IIBB** (pregunta 9).
- No es un descuento financiero por pronto pago ni tiene que ver con los plazos de cobro.

## 5. ¿Cómo saco el interés del préstamo?

**Interés del año = saldo al inicio del año × TEA.** Antes hay que pasar la tasa bimestral a anual.

1. **TEA**: hay 6 bimestres en el año → (1,07)⁶ − 1 = **50,073%**. No es 7% × 6 = 42% (eso sería la TNA).
2. **Cuota francesa** (constante): `=PAGO(1,07^6-1;3;-25000000)` = **17.778.181**.
3. Por año: **interés = saldo × TEA** · **amortización = cuota − interés** · **saldo nuevo = saldo − amortización**.

| Año | Saldo inicial | Interés (EAI) | Amortización (ENAI) | Saldo final |
|---|---:|---:|---:|---:|
| 1 | 25.000.000 | 12.518.259 | 5.259.922 | 19.740.078 |
| 2 | 19.740.078 | 9.884.456 | 7.893.725 | 11.846.353 |
| 3 | 11.846.353 | 5.931.828 | 11.846.353 | 0 |

- En Excel: `=IPAGO(tea;año;3;-25000000)` y `=PAGOPRIN(tea;año;3;-25000000)`.
- En el flujo del accionista: el **préstamo** entra en el año 0 como INAI (+25M), el **interés** es EAI (baja el IIGG) y la **amortización** es ENAI.
- Ninguno de los tres va en el flujo puro.

## 6. El estibador no tiene costo de oportunidad: ¿lo saco?

**No lo saques.** Es cierto que **no tiene costo de oportunidad**: el enunciado no dice que se pueda vender o alquilar hoy. Tampoco hay compra, porque es **costo hundido**. Pero igual entra por tres lados ([[01 Proyecto y flujo incremental]] §3, [[09 Inversión inicial y depreciación]] §5):

1. **Depreciación pendiente** como GND + ajuste → ahorra IIGG (200.000 × 35% = 70.000 por año).
2. **Desinversión del 20% en el año 2** → VL como GND + ajuste, **sin venta**.
3. **Venta en el año 5** al 30% del VO → IAI, con su VL como GND + ajuste.

**Datos:** VO = 200.000 × 10 = **2.000.000** · VL al inicio 1.200.000 → quedan 6 cuotas. Partir en 80% / 20%:

| | Año 1 | Año 2 | Año 3 | Año 4 | Año 5 |
|---|---:|---:|---:|---:|---:|
| Depreciación 80% (GND) | 160.000 | 160.000 | 160.000 | 160.000 | 160.000 |
| Depreciación 20% (GND) | 40.000 | 40.000 | — | — | — |
| VL 20% dado de baja (GND) | | 160.000 | | | |
| Venta estibador (IAI) | | | | | 480.000 |
| VL 80% (GND) | | | | | 160.000 |

- VL 20% al final del año 2 = 240.000 − 2 × 40.000 = **160.000**.
- VL 80% al final del año 5 = 960.000 − 5 × 160.000 = **160.000** → gana 320.000, paga IIGG.
- Todo lo que es GND (depreciaciones y VL) vuelve en el ajuste.

**Supuestos a escribir:**
- La venta es el 30% del VO de lo que **queda** (80% × 2.000.000 × 30% = 480.000), porque el 20% ya se dio de baja. Si se toma el 30% del VO total, son 600.000.
- "Usaremos durante 4 años" y "se vende en el año 5" no coinciden. Se deprecia hasta el año 5 y se vende al final. La alternativa es cortar la depreciación en el año 4.

## 7. Las 4 deudas: ¿cuáles van al Kd? ¿El 25M es el 40% de los activos?

La lista mezcla dos cosas distintas:

| Deuda | Qué es | Dónde va |
|---|---|---|
| 2M al 18% · 6M al 35% · 5M al 30% (EA) | Deudas que la empresa **ya tiene** | **Kd = 30,46%** → WACC |
| **25M al 7% bimestral** (*) | **Préstamo nuevo** del proyecto, para la máquina | **Flujo del accionista**: préstamo, interés y amortización |

- **El 25M no entra en el Kd.** Ya está explícito en el flujo del accionista; si también entra en la tasa, se cuenta dos veces. La comparación VAN accionista vs VAN puro mide justamente si **ese** préstamo apalanca.
- **El 40% no es el préstamo.** "El pasivo financia el 40% de los activos" es la estructura de **toda la empresa** → pesos del WACC: Xd = 0,4 y Xe = 0,6. El préstamo cubre 25 / 43,4 = **58%** de la máquina.
- **Pasar el 7% a TEA** es necesario porque el flujo es anual. Las otras tres ya vienen en EA.
- Apalancamiento: costo neto del préstamo = 50,07% × 0,65 ≈ **32,5%**, casi igual al WACC (32,52%) → el ΔVAN va a dar cerca de 0.

Es la misma trampa de POLO: **40/60** = toda la empresa (tasa) · **25M** = solo la máquina (flujo).

## 8. ¿Para qué sirven las 10 piezas y los 2,5 m² por caja?

**Para nada en los cálculos: son datos descriptivos.** Todo el ejercicio está en **cajas**:

| Dato | Unidad |
|---|---|
| Capacidad | 500.000 **cajas**/mes |
| Insumos y MOD | por **caja** |
| Comercialización | "se comercializa incluyendo 10 piezas por caja" → se vende la **caja** |
| Demanda | "unidades vendidas" → **cajas** (supuesto) |

- El precio con markup sale del costo por caja, así que es **precio por caja**.
- Solo servirían si la demanda viniera en m² o en piezas (60.000 piezas = 6.000 cajas; 60.000 m² = 24.000 cajas). No es el caso, pero conviene escribir el supuesto: **unidades = cajas**.
- Capacidad: 500.000 × 12 = 6.000.000 cajas/año contra 190.000 de demanda máxima → sobra muchísimo.

## 9. Descuento 3% e IIBB 1%: ¿los dos sobre la bruta y me quedo con el 96%?

**No: el IIBB va sobre la bruta menos el descuento.** Te quedás con el **96,03%**, no con el 96%.

> *"Yo pago ingresos brutos por lo vendido neto, neto de devoluciones y neto de descuentos."* [Clase 16/10] ([[05 Ventas, IIBB e IVA]] §1)

- El enunciado dice "3% **de la venta bruta**" solo para el descuento. Para el IIBB no aclara la base → criterio por defecto: bruta − descuento.
- Factor: 0,97 × (1 − 0,01) = **0,9603**.

| Año 1 | Cálculo | Importe |
|---|---|---:|
| Venta bruta | 60.000 × 13.377,77 | 802.666.200 |
| − Descuento 3% | 802.666.200 × 3% | −24.079.986 |
| = Venta neta comercial | | 778.586.214 |
| − IIBB 1% | 778.586.214 × 1% | −7.785.862 |
| **= Venta neta** | | **770.800.352** |
| Comisión (EAI aparte) | 1% × 770.800.352 × 1,45 | 11.176.605 |

- La diferencia con el 96% es chica (0,03% de la bruta), pero la base es otra.
- **Comisión**: va **aparte** como EAI. No resta para llegar a la venta neta.

---

## Respuestas finales del ejercicio

| Punto | Respuesta |
|---|---|
| 1. ¿Se recomienda el proyecto? | **Sí.** VAN puro 726.418.642 > 0 con WACC 32,52%. El FFA da positivo en el año 1 |
| 2. VAN del accionista, VAN puro y apalancamiento | Accionista **726.408.972** · Puro **726.418.642** · ΔVAN ≈ −9.670 → **no apalanca**: costo neto del préstamo 50,07% × 0,65 = 32,55% > WACC 32,52% |
| 3. Elasticidad precio de la demanda | **E ≈ −1,28** (año 4 → 5, separando la caída del mercado) → demanda elástica |
| 4. Precio de equilibrio de largo plazo | No resuelto (Buscar objetivo: VAN puro = 0 cambiando el precio del año 1) |
| 5. Cobro a 60 días para todos | No resuelto (solo cambia el WC; con los 70 días en el mes 4, el WC₁ baja a ≈ 17,8M) |

**Supuestos usados en la planilla:** β = 1,8 (raíces, "eje x") · markup sobre el costo total unitario de producción del año 1 · IIBB sobre bruta − descuento · comisión sobre la venta neta con CS · 70 días → mes 4 · WC proporcional a las unidades, sin cambio en el año 5 · estibador depreciado 4 años y venta = 30% del 80% restante · máquina sin venta, dada de baja por VL en el año 5.
