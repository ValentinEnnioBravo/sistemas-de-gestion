---
tags: [sdg, fundamentos, template]
aliases: [Template, IAI, EAI, GND, INAI, ENAI, Estructura FF]
---

# 02 · Estructura del flujo de fondos (el template)

← [[01 Proyecto y flujo incremental]] · siguiente → [[03 Tasas de interés]]

## 1. El esqueleto

Es el **template** que se lleva impreso al parcial (sale de la planilla "Template" y de las resoluciones de la guía):

| # | Fila | Qué va | Signo |
|---|---|---|---|
| 1 | **Ingresos afectos a impuestos (IAI)** | Ventas netas, venta de activos, ahorros (de personal, de costos) | + |
| 2 | **Egresos afectos a impuestos (EAI)** | Costos variables, fijos, sueldos, comisiones, regalías, licencias, intereses del préstamo, indemnizaciones, costos de oportunidad | − |
| 3 | **Gastos no desembolsables (GND)** | Depreciaciones, **valor libro** de lo que se vende o da de baja, quebranto trasladado | − (o el signo que corresponda) |
| 4 | **Utilidad antes de impuestos (UAI)** | 1 + 2 + 3 | |
| 5 | **− Impuesto a las ganancias (IIGG)** | UAI × T | |
| 6 | **Utilidad neta (UN)** | 4 − 5 | |
| 7 | **Ajustes de GND** | Se **vuelven a sumar** los GND de la fila 3 (signo contrario) | + |
| 8 | **Ingresos no afectos (INAI)** | Préstamo recibido, recupero de WC | + |
| 9 | **Egresos no afectos (ENAI)** | Inversiones, reinversiones, inversión en WC, amortización de capital del préstamo | − |
| 10 | **FLUJO DE CAJA** | 6 + 7 + 8 + 9 | |

> [!important] ¿Por qué esta forma?
> - Lo que pasa por el **estado de resultados** (ganancias y pérdidas) va **arriba de la utilidad**: modifica el impuesto.
> - Lo que es un **movimiento permutativo patrimonial** (compro una máquina: baja caja, sube activo) va **abajo**: no paga ni ahorra impuesto. [Guía ej 20]
> - Los **GND** son gastos contables sin salida de caja: se **restan** para calcular el impuesto (dan *escudo fiscal*) y después se **vuelven a sumar** en los ajustes para llegar a la caja.

> [!tip] Gasto ≠ desembolso
> La depreciación es un gasto contable, pero no sale plata. Por eso: **(1)** se resta como GND para calcular IIGG y **(2)** se suma de vuelta en Ajustes. [Resumen amigo]

## 2. Ejemplo mínimo: venta de un activo [Guía ej 14]

> Activo con valor de origen \$120.000, se amortiza en 3 años, se vende en el **año 2** a \$70.000. IIGG 50%.

| Concepto | Año 0 | Año 1 | Año 2 |
|---|---:|---:|---:|
| **IAI** · Ingreso por venta | | | 70.000 |
| **GND** · Depreciación | | −40.000 | −40.000 |
| **GND** · Valor libro (lo que falta depreciar) | | | −40.000 |
| **UAI** | | −40.000 | −10.000 |
| IIGG 50% | | **+20.000** (ahorro) | **+5.000** (ahorro) |
| **UN** | | −20.000 | −5.000 |
| **Ajustes GND** (dep. + VL) | | +40.000 | +80.000 |
| **ENAI** · Inversión | −120.000 | | |
| **Flujo de caja** | **−120.000** | **20.000** | **75.000** |

Cómo se lee:
- El valor libro al vender es 120.000 − 2 × 40.000 = **40.000**. Se vende a 70.000, así que la ganancia contable es 30.000.
- La UAI del año 2 da −10.000 porque la depreciación del año (40.000) es mayor que esa ganancia.
- Con UAI negativa el impuesto **da a favor** (escudo fiscal). Eso vale cuando **la empresa en conjunto gana plata** (ver [[17 Quebranto impositivo]]).

> [!important] Utilidad negativa del proyecto → igual se calcula IIGG (con signo +)
> Si la **empresa proyecta utilidades**, el proyecto con UAI negativa le **ahorra** impuesto a la empresa: *"la empresa paga en su conjunto"*. Por eso el impuesto con UAI < 0 suma. [Clase 20/10] [Guía ej 18, 30]
> La excepción es el **quebranto**: si la empresa proyecta pérdidas, ese año **IIGG = 0** → [[17 Quebranto impositivo]].

## 3. ¿Se calcula IIGG en el año 0?

**Sí.** Si en el año 0 hay algo afecto (venta de una máquina vieja, una indemnización, una licencia pagada por adelantado), **se le calcula el impuesto en el año 0**.

> *"¿Por qué le calculás el impuesto si el año 0 no es un año contable? No me calienta… lo hago en el valor presente. Después contablemente lo va a registrar el contador en el año 1."* [Clase 16/10] [Clase 20/10]

Ejemplo de la planilla (EJ 1 de clase, máquina vieja): venta 700 − VL 600 = UAI +100 → IIGG 35 en el **año 0**. [Planilla amigo]

## 4. Las dos versiones del flujo

| Flujo | Qué incluye | Se usa para |
|---|---|---|
| **Puro** (sin financiación) | Todo **menos** el préstamo | Evaluar si el **proyecto** agrega valor |
| **Del accionista** (con financiación) | Puro **+** préstamo (INAI año 0) **+** intereses (EAI) **+** amortización de capital (ENAI) | Ver si el préstamo **apalanca** |

→ Detalle en [[16 VAN puro vs VAN del accionista - apalancamiento]].

> [!tip] En el parcial
> Si hay deuda para el proyecto, entregás **solo el flujo del accionista** (no hay tiempo para los dos). [Clase 16/10] [Clase 23/10]

## 5. Orden práctico para llenar el template

1. Leer **todo** el enunciado primero (que no aparezca un párrafo de IIBB al final). [Clase 16/10]
2. Armar la hoja de **ventas** → venta neta ([[05 Ventas, IIBB e IVA]]).
3. Costos y sueldos ([[06 Costos, producción y stock]], [[08 Sueldos, indemnizaciones y ahorros]]).
4. Inversiones, depreciaciones, ventas de activos ([[09 Inversión inicial y depreciación]] → [[11 Reinversión y desinversión]]).
5. **Después** del flujo: el WC ([[13 Capital de trabajo (Working Capital)]]).
6. Préstamo ([[14 Préstamos - francés, alemán, americano y gracia]]) y WACC ([[15 WACC y tasa de descuento]]), en el momento que quieras.
7. Flujo de caja → VAN.

Ver checklist completo en [[18 Método paso a paso para el parcial]].

## Fuentes
[Guía ej 14, 18, 20, 30] · [Clase 16/10] · [Clase 20/10] · [Planilla amigo: Template, EJ 1] · [Resumen amigo]
