---
tags: [sdg, working-capital]
aliases: [Working Capital, WC, Capital de trabajo, Déficit acumulado]
---

# 13 · Capital de trabajo (Working Capital)

← [[12 Capacidad - cuándo comprar la máquina o stockear]] · siguiente → [[14 Préstamos - francés, alemán, americano y gracia]]

## 1. Qué es

Es la plata que hay que poner para que **el negocio gire solo** hasta que lo que cobrás alcanza para pagar lo que gastás. Es **activo corriente − pasivo corriente**, sobre todo **inventario y cuentas por cobrar**. [Clase 25/09] [Clase 16/10]

- Aparece porque **cobrás después de pagar** (plazos de cobro y pago, stock).
- Es una **inversión**: va en **ENAI** (no paga impuesto) y **no se deprecia**.
- Se **recupera al final** del proyecto → **INAI** en el último año.
- Se calcula para el **flujo puro**: lo pone el accionista. La financiación es otra decisión. [Clase 16/10]

## 2. Qué entra y qué no entra

| ✅ Entra | ❌ No entra |
|---|---|
| Cobranza de ventas (usá la **venta neta**, ya con IIBB descontado) | Préstamo, **intereses**, amortización de capital |
| Costos variables (MP, MOD, insumos) | **Depreciaciones** y VL |
| Costos fijos de **todas** las áreas (planta, admin, marketing) | **Venta de activos** (máquinas) |
| Sueldos (prorrateados con SAC: × 13 / 12) | **Ahorros** por despidos |
| Comisiones, regalías, gastos comerciales | **Indemnizaciones** del año 0 |
| Pagos adelantados (en la columna de contado) | **Costo de oportunidad** (criterio final, ver ⚠️) |
| | Pagos del año 0 (licencia del ej 51 pagada en el año 0) |

Fuentes: [Clase 25/09] [Clase 16/10] [Clase 20/10] [Clase 23/10].

> *"Todo lo que vos necesitás para operar la compañía lo vas a poner. ¿Ponele que no pongas un gasto de estructura de marketing? ¿Y qué hacés, no le pagás el sueldo?"* [Clase 23/10]

> [!warning] ⚠️ Consultar: costo de oportunidad e indemnización en el WC
> - **Costo de oportunidad**: en [Clase 16/10] dijo que sí; en [Clase 20/10] y [Clase 23/10], que **no** (*"no voy a necesitar plata para pagar eso"*, *"es discutible"*). **Usá NO.**
> - **Indemnización**: en el **año 0, no**. Si fuese en el **año 3**, Jorge dijo que lo tenía que pensar (*"me hiciste dudar"*). No se resolvió en clase. [Clase 23/10]

## 3. Los métodos que aparecieron

| Método | Cuándo lo usás | Ejercicios |
|---|---|---|
| **A · Déficit acumulado máximo** (mensual) | Te dan **plazos de cobro y pago** | 37, 40, 41, 43, 46, 47, 48, 49, 50, 51 |
| **B · Meses de costo** | "Se estima en X meses de costo variable" | 34 Flamingo (2 meses de CV), 42 Cervezas (4 meses de CV sin comisiones), 45 Toldo |
| **C · Monto dado** | "Requiere una inversión en WC de $X" | 39 (\$1.000, +50%), 44 Yogur (\$100.000) |
| **D · Por variación de días** de cuentas | Te dan balance y rotación (días de cobro, inventario) | 36 (−2 días de cobranza, −5 días de inventario) |

### Método A · Déficit acumulado máximo, paso a paso

1. Abrí el **primer año en 12 meses** (venta anual / 12 si no hay estacionalidad).
2. **Ingresos**: cobranza según la política (contado → mes 1, 30 días → mes 2, 60 días → mes 3…).
3. **Egresos**: cada costo en el mes en que se **paga** (contado, 30, 60 días).
4. **Saldo** del mes = ingresos − egresos.
5. **Saldo acumulado** mes a mes.
6. **WC = el máximo déficit acumulado** (el acumulado más negativo). **Mirá los 12 meses**: *"no hay que festejar el término del partido"* cuando da positivo un mes. [Clase 25/09]

> [!example] Bielsa (ej 46) · versión que hizo Jorge en [Clase 25/09] (verificada)
> Venta anual 90.000 × \$300 = 27.000.000 → **2.250.000/mes**. Cobro 10% contado, 60% a 30 días, 30% a 60 días. Todos los costos se pagan a 30 días: regalía 1.350.000/12, CV 20.700.000/12, fijos 100.000, alquiler 10.000, gastos generales 100.000 (por mes).
>
> | | Mes 1 | Mes 2 | Mes 3 en adelante |
> |---|---:|---:|---:|
> | Cobros | 225.000 | 225.000 + 1.350.000 | 2.250.000 |
> | Pagos | 0 | 2.047.500 | 2.047.500 |
> | **Saldo** | +225.000 | **−472.500** | +202.500 |
> | **Acumulado** | +225.000 | **−247.500** ← máximo déficit | −45.000 → … positivo |
>
> **WC₁ = 247.500.** No es 472.500, porque el mes 1 ya entraron 225.000 de contado.
>
> ⚠️ En esa pasada no se incluyeron los **gastos comerciales (10% de la venta)**. Según [Clase 23/10] van. En tu resolución incluilos.

> [!tip] La política comercial pesa mucho
> Si en Bielsa no cobrás nada de contado (60 / 40), el WC pasa a ~697.500. Si vendés todo a 90 días, a ~2M. *"Postergar la cobranza implica que vamos a necesitar cada vez más capital de trabajo."* [Clase 25/09]

### Método B · Meses de costo

$$WC = \text{Costo anual considerado} \times \frac{\text{meses}}{12}$$

| Ej | Enunciado | Cálculo año 1 |
|---|---|---|
| 34 Flamingo | 2 meses de costo variable | CV₁ = 1.850 × 75 = 138.750 → /6 = **23.125** |
| 42 Cervezas | 4 meses de CV, sin comisiones ni gastos financieros | CV = 20.000 × 135 = 2.700.000 → /3 = **900.000** |
| 45 Toldo | "un **20% más** que dos meses de los costos de la tabla" | (CV producido / 6) × 1,2 |

> [!warning] ⚠️ Toldo: ¿qué "costos de la tabla"?
> Gonzalo [Consulta 02/10]: es *"ambiguo, no te voy a decir que no"*. Al pie de la tabla están los sueldos. Una lectura toma solo los CV; otra suma sueldos y comisiones. Escribí el supuesto que uses.

## 4. Variaciones año a año (regla de tres)

Con el WC del año 1, los siguientes se sacan **proporcionales a las unidades**. [Clase 25/09]

$$WC_t = WC_1 \times \frac{Q_t}{Q_1} \qquad\qquad \Delta WC_t = WC_t - WC_{t-1}$$

> [!important] Timing: el WC del año *t* se invierte en el año *t − 1*
> El WC que necesitás **para el año 1** se pone en el **año 0**. El incremento para el año 2 se pone en el **año 1**, y así. *"En el año 1 voy a estar poniendo capital de trabajo que necesito en el año 2."* En el **último año no se pone nada** (sería para el año 6). [Clase 25/09]

### Bielsa (continúa el ejemplo de clase)

| | Año 0 | Año 1 | Año 2 | Año 3 | Año 4 | Año 5 |
|---|---:|---:|---:|---:|---:|---:|
| Unidades del año siguiente | 90.000 | 80.000 | 100.000 | 120.000 | 130.000 | — |
| WC necesario | 247.500 | 220.000 | 275.000 | 330.000 | 357.500 | — |
| **ΔWC (ENAI / INAI)** | **−247.500** | **+27.500** | **−55.000** | **−55.000** | **−27.500** | — |
| **Recupero (INAI)** | | | | | | **+357.500** |

- Si las unidades **bajan**, la variación es **positiva**: un **recupero parcial**. *"Si recupero antes, ese valor viene positivo… es mejor para mi flujo."* [Clase 25/09]
- El recupero final es **todo lo acumulado** (la suma de lo invertido neto = el último WC).

### Flamingo (ej 34, 2 meses de CV): verificado

| | Año 0 | Año 1 | Año 2 | Año 3 |
|---|---:|---:|---:|---:|
| WC para el año siguiente | 23.125 | 25.000 | 37.500 | — |
| ΔWC | −23.125 | −1.875 | **−12.500** | — |
| Recupero | | | | +37.500 |

(El ayudante confirmó los 12.500 del año 2. [Consulta 02/10])

> [!note] ¿Y si cambian precios o costos y no solo las unidades?
> La regla de tres sobre unidades es lo que se usa en el parcial (*"vamos con la tablita lineal siempre"*). En la vida real recalculás el déficit de cada año (*"es una boludez, hacés uno por año"*). Si aumentan los sueldos en un año, para el parcial no se recalcula el WC. [Clase 25/09] [Clase 23/10]

## 5. WC con stock: producido, no vendido

En el WC el **costo variable** se calcula sobre lo **producido**. La venta, los fijos y la regalía siguen igual. [Clase 25/09]

> [!example] Bielsa con stock (producción 100.000/año)
> CV mensual = 230 × 100.000 / 12 = 1.916.667 → el déficit acumulado pasa de 247.500 a **439.167**. Los años siguientes la regla de tres va sobre **unidades producidas**: 100.000 en los años 1–4 → ΔWC = 0. En el año 5 se producen 120.000 → ΔWC = +20% en el año 4.

### Dos variantes para las variaciones con stock

| Variante | Regla | Estado |
|---|---|---|
| **"El mayor entre venta y producción"** | Regla de tres sobre max(Q vendida, Q producida) | Jorge la dio para simplificar: *"yo te lo voy a tomar bien"* [Clase 16/10] |
| **Mirando el stock** | Si el stock que ya tenés cubre la suba de demanda, **no** hay ΔWC aunque la venta suba | Es el concepto correcto (*"lo entendiste bien"*) [Clase 16/10] |

> [!warning] ⚠️ Las dos se aceptan
> El ayudante también dijo que hay *"dos variantes que Jorge siempre maneja"*. [Consulta 02/10] Elegí una y decí cuál.

## 6. Casos especiales

| Caso | Qué hacer | Fuente |
|---|---|---|
| El acumulado **nunca** da negativo | **WC = 0**, no ponés nada (*"30 de 33 meses con superávit"*) | [Clase 16/10] [Clase 20/10] |
| Da negativo los 12 meses | WC = el acumulado del mes 12 (y probablemente haya que revisar el año 2) | [Clase 20/10] |
| "Para que el proyecto **ruede por sí solo**" (Toldo) | Es **un único WC para todo el proyecto**: año 0 y recupero al final | [Consulta 02/10] |
| "Inversión inicial en WC de \$100.000 para hacer rodar" (ej 44) | Monto dado, año 0 | Guía |
| WC financiado con deuda (ej 42) | Igual se calcula. Si el enunciado lo dice, el préstamo lo cubre | Guía ej 42 |
| Sueldos con SAC | Prorrateá × 13 / 12 por mes | [Clase 25/09] [Clase 20/10] |
| MOD / sueldos | Siempre a **mes vencido** (30 días), aunque digan "fijos a 60" | [Clase 16/10] [Clase 20/10] |
| IIBB a pagar a 30 días | Simplificá: trabajá con la venta neta | [Clase 20/10] [Clase 23/10] |
| Pago adelantado | En la columna **contado** (o el mes anterior) | [Clase 20/10] |
| Puede haber **recupero a mitad** de proyecto y después reinversión | Sí, si baja la demanda | [Consulta 02/10] |

## 7. Recupero parcial con efecto impositivo

> Ej 39: "se espera recuperar un **80%** una vez concluido el proyecto".

Se trata como una **venta de activo**: lo recuperado es IAI y el WC total es el "VL" (GND). [Resumen amigo] [Planilla amigo, Template]

| Concepto (último año) | WC = 100.000, recupero 80%, IIGG 10% |
|---|---:|
| IAI: recupero 80% | +80.000 |
| GND: WC total | −100.000 |
| UAI | −20.000 |
| IIGG (ahorro) | +2.000 |
| UN | −18.000 |
| Ajuste GND | +100.000 |
| **Recupero neto** | **82.000** |

Fórmula directa: $\text{Recupero neto} = WC \cdot r + WC \cdot (1 - r) \cdot T$

> [!warning] ⚠️ Consultar
> Esta mecánica viene del [Resumen amigo] y de la planilla; no se trató en las clases grabadas. Tampoco está claro si al flujo principal va el 80% bruto (y el efecto impositivo por separado) o el neto (82.000). Confirmalo.

## 8. Ideas para "minimizar el capital de trabajo" (ej 43.2)
Cobrar antes (más contado), pagar más tarde a proveedores, producir lo justo (menos stock). Todo sale del mecanismo de arriba. [Clase 25/09] [Clase 20/10]

## Fuentes
[Clase 25/09] (método completo) · [Clase 16/10] · [Clase 20/10] · [Clase 23/10] · [Consulta 02/10] · [Guía ej 34, 36, 39, 40, 42, 44, 45, 46] · [Resumen amigo: WC] · [Planilla amigo: Template, Calamar, Bielsa, Toldo, 37, 42, 47, 48, 50]
