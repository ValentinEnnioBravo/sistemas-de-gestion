# Ej 48 · POLO Hermanos: preguntas y respuestas

Consultas hechas mientras se resolvía el ejercicio, con la respuesta concreta de cada una. Los criterios siguen las notas del apunte ([[09 Inversión inicial y depreciación]], [[10 Venta de activos y valor residual]], [[11 Reinversión y desinversión]], [[12 Capacidad - cuándo comprar la máquina o stockear]]).

**Supuestos a dejar escritos en la hoja:**
- Los **$5M con IVA** son solo la línea. La instalación (10% del VO) se suma aparte.
- IVA del **21%**: el enunciado no indica alícuota.
- Año de **360 días** para pasar la tasa de 60 días a anual (6 períodos).
- Los 40K bidones que faltan en el año 3 se producen en el año 1 y se stockean. El módulo se compra a comienzo del año 4 (**columna 3**).
- El VL del 10% desinvertido se muestra en el **año 5**, junto con la venta (⚠️ ver [[Dudas abiertas para consultar]] #4).

---

## 1. ¿Qué significa f.e.m.?

En este ejercicio no es la "fuerza electromotriz" de Física. Es el **costo de energía** del proceso productivo. Es un **costo variable de $29,80 por bidón** (EAI).

Costo variable por bidón (10 litros):

| Componente | Cálculo | $/bidón |
|---|---|---:|
| Ácido sulfónico | 0,08 kg × 210 × 10 L | 168,0 |
| Ácido oxálico | 0,04 kg × 180 × 10 L | 72,0 |
| Agua | 1 L × 25 × 10 L | 250,0 |
| Urea | 0,02 kg × 80 × 10 L | 16,0 |
| Bidón | 1.300 / 100 | 13,0 |
| Etiquetas | 2 × 195 / 100 | 3,9 |
| f.e.m. | | 29,8 |
| **Total** | | **552,7** |

## 2. La línea cuesta $5M con IVA: ¿se lo saco? ¿La instalación es el 10% sin IVA?

Sí a las dos. El IVA se recupera como crédito fiscal, así que no es costo del proyecto.

| Concepto | Cálculo | Importe |
|---|---|---:|
| Valor de origen (sin IVA) | 5.000.000 / 1,21 | 4.132.231 |
| Instalación | 10% × 4.132.231 | 413.223 |
| **Valor amortizable (ENAI año 0)** | | **4.545.454** |

> [!warning] Lectura alternativa
> Si los 5M ya incluyeran la instalación: VO = 4.132.231 / 1,1 = 3.756.574. Se descartó porque el enunciado habla de la instalación como un costo aparte.

## 3. Tasa efectiva a 60 días del 3%: ¿TNA = 0,03 y m = 2?

**No.** El 3% es lo que rinde cada período de 60 días, no una tasa anual. Y m = 2 sería capitalización semestral (180 días).

- Períodos por año: 360 / 60 = **6**
- **TEA = 1,03⁶ − 1 = 19,41%** ← la que va en el préstamo francés anual (3 cuotas)
- TNA = 0,03 × 6 = 18%. No se usa para el cálculo, porque la tasa del préstamo es efectiva.

## 4. Valor residual del 20% del VO en el año 10: ¿deprecia 8% por año?

**No.** Criterio de la cátedra: **siempre se deprecia el 100%**. El valor residual no se resta para depreciar; es el **precio de venta** y va aparte como IAI ([[09 Inversión inicial y depreciación]] §2).

- "Todas las inversiones se deprecian a 10 años de manera lineal" → **10% anual = 454.545**.
- Por eso, al año 10 el VL es 0 aunque el activo valga 20%. El 20% sirve para **estimar el precio de venta al año 5** con el promedio simple de la guía (ej 19):

$$\text{Venta}_{año\,5} = \frac{100\% + 20\%}{2} = 60\% \text{ del VO} = 0{,}6 \times 4.132.231 = \mathbf{2.479.339}$$

El precio de venta se calcula sobre el VO **sin instalación**. El VL sí la incluye ([[10 Venta de activos y valor residual]] §3).

## 5. ¿Qué hago con los IIBB?

Son un **EAI**: un porcentaje sobre la **venta neta** (sin IVA, después de los descuentos por canal). Se restan antes de Ganancias porque son deducibles.

- AMBA: **1,5%** sobre su venta.
- Córdoba, desde el año 3: **2%** sobre su venta (10% de la venta total, todo por mayorista).
- Una línea por región y por canal (ver [[05 Ventas, IIBB e IVA]]).

Precio neto por canal: mayorista 3.800 × 0,6 = **2.280** · supermercado 3.800 × 0,7 = **2.660**.

## 6. ¿El IIBB es un EAI?

**Sí.** Es un egreso afecto a impuestos: pasa por el estado de resultados y reduce la base de Ganancias. Con IIGG al 35%, cada $100 de IIBB cuesta $65 netos.

## 7. Cargas sociales del 40% "adicional": ¿les pago un 40% más?

A la empresa le cuesta un 40% más, pero el empleado no lo cobra: va al Estado. Como el enunciado dice "**adicional**", se suma sobre el salario ([[08 Sueldos, indemnizaciones y ahorros]]):

$$(4 \times 570.000 + 1.000.000) \times 13 \times 1{,}4 = \mathbf{59.696.000} \text{ por año (EAI)}$$

## 8. La desinversión del 10%: ¿es un ingreso no afecto en el año de la reinversión?

**No.** El enunciado dice que *"se venderá al final con el resto del equipamiento"*, así que **en el año de la reinversión no entra plata**. Lo que pasa ese año es una **baja**: esa parte se desactiva y **deja de depreciarse**.

Además, una venta de activos nunca es INAI: el precio es IAI y el VL va como GND más su ajuste. Solo tributa la diferencia.

Partiendo la depreciación de la línea (10% de 4.545.454 = 454.545):

| | Años 1–3 | Años 4–5 |
|---|---:|---:|
| Depreciación 90% que sigue | 409.091 | 409.091 |
| Depreciación 10% desinvertido | 45.455 | — |
| VL del 10% al final del año 3 | 454.545 − 3 × 45.455 = **318.182** | |

> [!warning] ⚠️ Consultar
> No está claro si el VL del 10% se da de baja en el año 3 o en el año 5 junto con la venta. Lo coherente con "se venderá al final con el resto" es el **año 5**.

## 9. ¿La línea y el módulo se venden los dos al final?

**Sí, en el año 5.** El enunciado lo dice y además siempre se simula la venta de todo al final.

| Activo | Venta (IAI) | VL (GND + ajuste) | Resultado |
|---|---:|---:|---|
| Línea (incluye el 10% desinvertido) | 60% × 4.132.231 = **2.479.339** | 90%: 4.090.909 − 5 × 409.091 = 2.045.455 + 10%: 318.182 = **2.363.637** | Gana 115.702 → paga IIGG |
| Módulo | 80% × 3.000.000 = **2.400.000** | 3.300.000 − 2 × 330.000 = **2.640.000** | Pierde 240.000 → ahorro de IIGG |

Del módulo: la venta se calcula sobre el valor de compra **sin instalación** y el VL **con instalación**. Por eso no coinciden.

## 10. ¿La segunda máquina deprecia 4% por año?

**No.** El 4% sale de repartir 20% de pérdida en 5 años, pero:
1. "Todas las inversiones se deprecian a **10 años** lineal" → **10% anual**.
2. El módulo no está los 5 años: si se compra en la columna 3, deprecia solo los años 4 y 5.

Valor amortizable 3.000.000 + 10% = 3.300.000 → **330.000 por año**. El 80% del año 5 es su **precio de venta**, no la base para depreciar.

## 11. ¿Cuándo compro el módulo?

**Lo más tarde posible, stockeando.**

| | Año 1 | Año 2 | Año 3 | Año 4 | Año 5 |
|---|---:|---:|---:|---:|---:|
| Demanda | 99K | 150K | 190K | 220K | 250K |
| Capacidad | 150K | 150K | 150K | 250K | 250K |
| Producción | **139K** | 150K | 150K | 220K | 250K |
| Stock final | 40K | 40K | 0 | 0 | 0 |

- El año 1 tiene 51K de capacidad ociosa y el año 2 ninguna. Los 40K que faltan en el año 3 solo se pueden producir en el año 1.
- Vencimiento de 24 meses: lo producido en el año 1 se vende en el año 3, dentro del plazo.
- El año 4 ya no se puede cubrir con stock → módulo a **comienzo del año 4 = columna 3** (ENAI 3.300.000).
- Con el módulo, la capacidad pasa a 250K, que cubre justo la demanda del año 5.

Qué cambia en el flujo ([[12 Capacidad - cuándo comprar la máquina o stockear]] §3):
- **Ventas y costo variable del FF**: sobre lo **vendido**.
- **Capital de trabajo**: el costo variable va sobre lo **producido**. En el año 1 hay más WC por los 40K stockeados.

## 12. Mi amigo pone la desinversión como ingreso afecto a impuestos (IAI). ¿Está bien?

**En el año de la desinversión, no.** La [Planilla amigo] tiene el mismo patrón en Bielsa y Toldo: un IAI por "venta" de la parte desinvertida (el % del VO) en el año de la baja. El apunte lo marca como error ([[11 Reinversión y desinversión]] §4):

- Criterio de Jorge [Clase 20/10]: **si no te dice que se vende, venta = 0**. Solo va el VL como GND más su ajuste.
- En Polo el enunciado sí dice que se vende, pero **"al final con el resto del equipamiento"**. Entonces no hay ingreso en el año de la baja: el ingreso entra en el **año 5**, dentro de la venta de toda la línea (pregunta 9).
- Además, el VO completo nunca puede ser el precio de venta de una parte usada. Esa parte ya lleva 3 años depreciándose.

| Dónde pone el IAI | ¿Está bien? |
|---|---|
| Año de la reinversión, por el 10% del VO | ❌ No hay venta ese año |
| Año 5, como parte de la venta de la línea | ✅ Es la venta de activos de siempre: IAI + VL como GND + ajuste |

La [Planilla amigo] del 48 ya está marcada con errores en [[Dudas abiertas para consultar]] #20. Revisá en qué año pone ese ingreso.

## 13. ¿El VL del 10% va como GND + ajuste en el año 4? ¿En el año 5 vendo el 100% o el 90%?

**No va en el año 4.** El módulo se compra a comienzo del año 4 = **columna 3**. El 10% se deprecia en los años 1–3 y desde el año 4 ya no.

Como el enunciado dice que se vende "al final con el resto", el VL congelado del 10% va en el **año 5**, junto con la venta. En el año 3 solo se corta la depreciación.

**En el año 5 se vende el 100% de la línea**, porque el 10% se vende con el resto:

| Año 5 | Fila | Importe |
|---|---|---:|
| Venta de la línea completa (60% × 4.132.231) | IAI | +2.479.339 |
| VL del 90% | GND | −2.045.455 |
| VL del 10% (congelado desde el año 3) | GND | −318.182 |
| Ajuste de los VL | Ajuste | +2.363.637 |

Ganancia: 115.702 → paga IIGG.

> [!note] Cuándo va el GND en el año de la baja
> Solo cuando lo desinvertido **no se vende** (ej 51, mobiliario): ahí el VL va como GND + ajuste en la columna de la baja.
> Si en Polo lo ponés en la columna 3, en el año 5 restás solo el VL del 90%, pero la venta sigue siendo del 100%. La deducción total es la misma; solo cambia el año (⚠️ [[Dudas abiertas para consultar]] #4).

## 14. Si el residual es 20% en el año 10, ¿en el año 5 vale 10%?

**No, vale 60%.** El valor arranca en 100% y **baja** hasta 20% en el año 10, así que en el año 5 está en el medio:

$$\frac{100\% + 20\%}{2} = 60\% \quad\text{(o lineal: pierde 8\% por año → } 100\% - 5 \times 8\% = 60\%)$$

Control de cordura ([[10 Venta de activos y valor residual]] §4): el valor del año 5 **no puede ser menor** que el del año 10.

Ese 8% es la caída del **valor de mercado**, no la depreciación (que sigue siendo 10% anual). Venta año 5 = 60% × 4.132.231 = **2.479.339**.

## 15. ¿Cuánto da la cuota del francés? A mí 1.718.043,65 y a mi amigo 1.710.075,90

La fórmula es la misma: $C = P \cdot \frac{i(1+i)^n}{(1+i)^n - 1}$, con P = 80% × 4.545.454,55 = **3.636.363,64** y n = 3. Lo que cambia es la TEA:

| | TEA | Cuota |
|---|---|---:|
| Mía | ≈ 19,7% (año de 365: 1,03^(365/60) − 1) | 1.718.043,65 |
| Amigo | 19,4% redondeada | 1.710.075,90 |
| **Correcta** | **1,03⁶ − 1 = 19,4052%** | **≈ 1.710.217** |

- La cátedra usa **año comercial de 360 días** ([[03 Tasas de interés]]): "a 60 días" → m = 6.
- **No redondear la tasa.** En Excel: `=1,03^6-1` en la celda de la TEA, o `=PAGO(1,03^6-1;3;-C46)`.

## 16. ¿Los costos fijos anuales son 99.744.000?

**No: 104.336.000.** Con 99.744.000 los sueldos se multiplicaron por 12 y faltó el **SAC** (aguinaldo): sueldos × **13** ([[08 Sueldos, indemnizaciones y ahorros]]).

| Concepto | Mensual | Anual |
|---|---:|---:|
| Costo de oportunidad del depósito | 550.000 | 6.600.000 |
| Seguros | 120.000 | 1.440.000 |
| Gastos generales productivos | 150.000 | 1.800.000 |
| Administración y comercialización | 2.000.000 | 24.000.000 |
| Seguridad | 900.000 | 10.800.000 |
| **Subtotal sin sueldos** | **3.720.000** | **44.640.000** |
| Sueldos: (4 × 570.000 + 1.000.000) × 13 × 1,4 | | **59.696.000** |
| **Total costos fijos** | | **104.336.000** |

Diferencia con × 12: 4.592.000 = el aguinaldo con sus cargas sociales. Para el WC mensual, prorratear: sueldo × 13 / 12 por mes.

## 17. ¿El aguinaldo va para los 5 trabajadores por igual?

Lo cobran los 5, pero **no el mismo monto**: cada uno recibe **un sueldo extra propio** por año (medio en junio y medio en diciembre).

| Empleado | Sueldo mensual | Aguinaldo anual | Costo anual (× 13 × 1,4) |
|---|---:|---:|---:|
| Operario (× 4) | 570.000 | 570.000 c/u | 10.374.000 c/u → 41.496.000 |
| Supervisor | 1.000.000 | 1.000.000 | 18.200.000 |
| **Total** | 3.280.000 | 3.280.000 | **59.696.000** |

Como todos cobran un sueldo más, multiplicar la masa salarial por 13 da lo mismo que calcularlo uno por uno. Las cargas sociales también se aplican sobre el aguinaldo.

## 18. Revisión de ventas y costos (IAI y EAI)

| Fila | Año 1 | Año 2 | Año 3 | Año 4 | Año 5 |
|---|---:|---:|---:|---:|---:|
| Ventas AMBA mayorista | 135.432.000 | 205.200.000 | 233.928.000 | 270.864.000 | 307.800.000 |
| Ventas AMBA súper | 105.336.000 | 159.600.000 | 181.944.000 | 210.672.000 | 239.400.000 |
| Ventas Córdoba mayorista | | | **43.320.000** | **50.160.000** | **57.000.000** |
| Costos variables (552,7 × vendidos) | 54.717.300 | 82.905.000 | 105.013.000 | 121.594.000 | 138.175.000 |
| Costos fijos | 104.336.000 | 104.336.000 | 104.336.000 | 104.336.000 | 104.336.000 |
| IIBB AMBA (1,5%) | 3.611.520 | 5.472.000 | 6.238.080 | 7.223.040 | 8.208.000 |
| IIBB Córdoba (2%) | | | **866.400** | **1.003.200** | **1.140.000** |

- **Error encontrado:** Córdoba estaba corrida dos años. Tomaba el 10% de la demanda de t − 2 (9.900, 15.000 y 19.000 bidones) en vez de la del año: 19.000, 22.000 y 25.000.
- **Control:** AMBA + Córdoba = demanda total (año 3: 171.000 + 19.000 = 190.000).
- El precio de $3.800 se toma **sin IVA**: el enunciado no dice "IVA incluido" ([[05 Ventas, IIBB e IVA]] §4).

---

## Aprendizaje para otros ejercicios

> [!tip] Stockear al máximo para patear la máquina
> Cuando la demanda supera la capacidad, la lógica es **stockear lo máximo posible para postergar la compra de la máquina lo más que se pueda**. Una inversión que se patea hacia adelante se descuenta más y mejora el VAN.
> 1. Armar la tabla demanda vs capacidad y encontrar el primer faltante.
> 2. Cubrirlo con capacidad ociosa de años anteriores. Producir el extra **lo más tarde posible** y respetar el **vencimiento** si el producto es perecedero.
> 3. Comprar la máquina a comienzo del primer año que el stock ya no cubre (**columna N − 1**).
> 4. Costo variable del FF sobre lo vendido; WC sobre lo producido.

> [!tip] Desinversión parcial: depreciar la parte por separado
> Cuando se desinvierte una parte de un activo, **partí la depreciación en dos líneas desde el año 1**: la parte que se desinvierte y la que sigue. Desde la desinversión, **esa parte deja de depreciarse**: su línea se corta y queda su VL congelado.
> - Ej 48: 10% de 4.545.454 → **45.455/año** en los años 1–3 y nada después (VL 318.182). El 90% sigue con 409.091/año hasta el año 5.
> - Así el VL de la parte desinvertida sale directo, para darla de baja o para venderla.
> - La desinversión **no es un ingreso** salvo que el enunciado diga que se vende y en qué año.

> [!tip] Se deprecia el valor + la instalación
> El valor amortizable es **precio sin IVA + instalación** (+ transporte si lo hay), y la depreciación sale de ahí ([[09 Inversión inicial y depreciación]] §1).
> - Línea: 4.132.231 + 413.223 = **4.545.454** → 454.545/año.
> - Módulo: 3.000.000 + 300.000 = **3.300.000** → 330.000/año.
> - Ojo: el **precio de venta** se calcula sobre el valor **sin** instalación (60% × 4.132.231, 80% × 3.000.000). La instalación entra en el VL pero no en el precio de venta.

> [!note] Otras trampas de este ejercicio
> - **Residual ≠ base de depreciación.** Se deprecia el 100%; el residual es el precio de venta y, si está en otro año, se interpola.
> - **Venta sobre el VO sin instalación, VL con instalación.** Casi nunca coinciden.
> - **Desinversión que "se vende al final con el resto"**: no hay ingreso en el año de la baja, solo se corta la depreciación.
> - **Tasa efectiva a 60 días** → TEA = (1 + i)⁶ − 1 con año de 360 días, no TNA con m = 2. No redondear la TEA.
> - **Sueldos × 13** (aguinaldo) × (1 + cargas sociales), no × 12.
> - **Estudio de mercado ($2M)**: costo hundido, no va. **Depósito propio ($550.000/mes)**: costo de oportunidad, va como EAI.

---

## Respuestas finales del ejercicio

| Punto | Respuesta |
|---|---|
| 1. VAN puro y VAN del accionista | Pendiente |
| 2. Premio por riesgo de 6% a 10% | Pendiente |
| 3. Precio de equilibrio de largo plazo | Pendiente |
| 4. Costo de MOD por bidón en el año 1 | Pendiente |
