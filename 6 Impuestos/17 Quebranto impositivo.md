---
tags: [sdg, impuestos, quebranto]
aliases: [Quebranto, Pérdida fiscal, Traslado de quebranto]
---

# 17 · Quebranto impositivo

← [[16 VAN puro vs VAN del accionista - apalancamiento]] · siguiente → [[18 Método paso a paso para el parcial]]

## 1. ¿Cuándo hay quebranto?

Solo si el enunciado dice que **la empresa en su conjunto proyecta pérdidas** en algún año (ej 51: *"la empresa proyecta para el año siguiente (1) quebranto, pero para los otros proyecta utilidades"*).

- *"Si la empresa planifica ganancias, no vas a tener quebrantos."* [Clase 16/10]
- **No es automático**: que la UAI **del proyecto** dé negativa **no** es quebranto. Si la empresa gana plata, el impuesto negativo del proyecto **es un ahorro** y se pone (ver [[02 Estructura del flujo de fondos]]). [Clase 23/10]

## 2. El procedimiento de la cátedra

> [!important] Regla (vale si la UAI del proyecto ese año es positiva o negativa)
> 1. En el año de quebranto: **IIGG = 0**.
> 2. La **UAI del proyecto** de ese año (no la utilidad neta) se lleva al **año siguiente** como **GND**, **con el mismo signo**.
> 3. Se calcula el IIGG del año siguiente con ese GND incluido.
> 4. En **Ajustes de GND** se pone el mismo importe con **signo contrario** (no es caja de ese año).
>
> *"En el segundo año te llevás ese mil o menos mil como si fuese un gasto no desembolsable. Le calculás el impuesto y después lo volvés a sumar con signos cambiados. Como si fuese una depreciación."* [Clase 20/10] [Clase 23/10]

### Caso A · El proyecto da POSITIVO en el año de quebranto

| Concepto | Año 1 (empresa en quebranto) | Año 2 |
|---|---:|---:|
| UAI propia del proyecto | +1.000.000 | +2.000.000 |
| GND: quebranto trasladado | | **+1.000.000** |
| **UAI para impuestos** | +1.000.000 | **+3.000.000** |
| IIGG 35% | **0** | −1.050.000 |
| Utilidad neta | +1.000.000 | +1.950.000 |
| Ajuste del quebranto | | **−1.000.000** |
| Aporte a la caja | +1.000.000 | +950.000 |

El millón del año 1 no pagó impuesto ese año y lo paga en el año 2. *"Si es positivo, para tu proyecto es una cagada, porque le vas a pagar 35%."* [Clase 23/10]

### Caso B · El proyecto da NEGATIVO en el año de quebranto

| Concepto | Año 1 (empresa en quebranto) | Año 2 |
|---|---:|---:|
| UAI propia del proyecto | −1.000.000 | +2.000.000 |
| GND: quebranto trasladado | | **−1.000.000** |
| **UAI para impuestos** | −1.000.000 | **+1.000.000** |
| IIGG 35% | **0** | −350.000 (en vez de −700.000) |
| Ajuste del quebranto | | **+1.000.000** |

La pérdida no se pudo usar en el año 1 y baja el impuesto del año 2 (ahorro de 350.000). [Resumen amigo] [Planilla amigo, Template]

| Resumen | GND (año siguiente) | Ajuste |
|---|---|---|
| UAI positiva | **+** | **−** |
| UAI negativa | **−** | **+** |

## 3. ¿Por qué se traslada aunque sea positivo?

Porque tu UAI es **parte** del resultado total de la empresa, que es lo que se traslada como quebranto. [Clase 23/10]

> [!example] El Excel de Jorge [Clase 23/10]
> | | Año 1 |
> |---|---:|
> | Negocio principal | −1.000 |
> | Proyecto 1 (el nuestro) | +30 |
> | Proyecto 2 | +40 |
> | **Quebranto de la empresa** | **−930** |
>
> El quebranto que se traslada es **−930**, que ya incluye nuestro +30. Si no lo llevaras, la empresa trasladaría −1.000 (más quebranto del que tiene) y el auditor no lo firmaría. Por eso tu +30 tiene que aparecer al año siguiente sumando a la base.

## 4. Errores que hay que evitar

- Calcular IIGG en el año de quebranto porque el proyecto da positivo.
- Trasladar la **utilidad neta** en vez de la **UAI**. *"Si te hubieses llevado la utilidad neta estaba mal."* [Clase 23/10]
- Cambiar el signo al ponerlo en GND.
- Olvidar el **ajuste** con signo contrario. En ese caso el flujo cuenta dos veces plata que no se movió. *"Por eso existe el ajuste del quebranto."* [Clase 23/10]
- Aplicar quebranto sin que el enunciado lo diga.

> [!note] Método alternativo que también aceptó
> Un alumno trasladaba el **crédito fiscal** (UAI × T) y lo restaba directamente del impuesto del año siguiente. *"Está bien, es una posibilidad, no está mal."* Jorge prefiere el GND (*"es la que usa Sapag"*) porque se ve el impacto real. [Clase 23/10]

## 5. Contraste: empresa que nunca paga impuestos (ej 15 de la guía)

La empresa A *"tiene pérdidas fiscales acumuladas y probablemente no pagará impuestos en un futuro previsible"* → **no se calcula IIGG en ningún año** (tampoco se traslada nada). La empresa B paga 35%.
VAN(A) = **14.634** > VAN(B) = **3.666**. *"La diferencia es la cuota del pago del impuesto a las ganancias."* [Guía ej 15]

## Fuentes
[Clase 16/10] · [Clase 20/10] · [Clase 23/10] · [Guía ej 15, 51] · [Resumen amigo: Quebranto] · [Planilla amigo: Template (casos ±300k)]
