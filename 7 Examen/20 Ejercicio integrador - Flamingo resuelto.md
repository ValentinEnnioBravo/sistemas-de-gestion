---
tags: [sdg, examen, ejercicio-resuelto]
aliases: [Flamingo, Ejercicio 34]
---

# 20 · Ejercicio integrador: Flamingo (ej 34) resuelto

← [[19 Errores comunes y trampas]] · siguiente → [[21 Mapa de ejercicios de la guía]]

Es un ejercicio corto que repasa casi toda la Parte 1–4: ventas, costos variables y fijos, depreciación, terreno, WC por meses de costo y VAN. (Las preguntas de equilibrio son de sensibilización y no entran en el parcial.)

## Datos [Guía ej 34]

| Dato | Valor |
|---|---|
| Costo variable unitario | Agua 10 + azúcar 12 + saborizantes 30 + MOD 23 = **\$75** |
| Demanda / precio | Año 1: 1.850 a \$100 · Año 2: 2.000 a \$110 · Año 3: 3.000 a \$120 |
| Terreno | \$15.000, sin vida útil, salvamento \$15.000 |
| Tecnología | \$10.000, 3 años |
| Obras físicas | \$20.000, 3 años |
| WC | 2 meses de costo variable |
| Costos indirectos de fabricación | \$3.000/mes |
| IIGG | 10% |
| Tasa | 13% |

## Paso 1 · Cálculos auxiliares

| Concepto | Año 1 | Año 2 | Año 3 |
|---|---:|---:|---:|
| Ventas (P × Q) | 185.000 | 220.000 | 360.000 |
| CV (75 × Q) | 138.750 | 150.000 | 225.000 |
| CIF (3.000 × 12) | 36.000 | 36.000 | 36.000 |
| Depreciación tecnología (10.000/3) | 3.333 | 3.333 | 3.333 |
| Depreciación obras (20.000/3) | 6.667 | 6.667 | 6.667 |

**WC** (CV anual / 6): año 1 = 23.125 · año 2 = 25.000 · año 3 = 37.500 → [[13 Capital de trabajo (Working Capital)]]

## Paso 2 · Flujo de fondos

| Concepto | Año 0 | Año 1 | Año 2 | Año 3 |
|---|---:|---:|---:|---:|
| **IAI** Ventas | | 185.000 | 220.000 | 360.000 |
| **IAI** Venta terreno | | | | 15.000 |
| **EAI** Costos variables | | −138.750 | −150.000 | −225.000 |
| **EAI** CIF | | −36.000 | −36.000 | −36.000 |
| **GND** Depreciaciones | | −10.000 | −10.000 | −10.000 |
| **GND** VL terreno | | | | −15.000 |
| **UAI** | | **250** | **24.000** | **89.000** |
| IIGG 10% | | −25 | −2.400 | −8.900 |
| **UN** | | 225 | 21.600 | 80.100 |
| Ajuste depreciaciones | | 10.000 | 10.000 | 10.000 |
| Ajuste VL terreno | | | | 15.000 |
| **ENAI** Terreno + tecnología + obras | −45.000 | | | |
| **ENAI** Inversión en WC | −23.125 | −1.875 | −12.500 | |
| **INAI** Recupero WC | | | | 37.500 |
| **Flujo de caja** | **−68.125** | **8.350** | **19.100** | **142.600** |

$$VAN_{13\%} = -68.125 + \frac{8.350}{1{,}13} + \frac{19.100}{1{,}13^2} + \frac{142.600}{1{,}13^3} \approx \mathbf{53.051}$$

(Verificado por cálculo. En la consulta, la ayudante dijo que le daba ≈ 53.057; la diferencia es de redondeo. [Clase 25/09])

## Qué mirar

1. **Terreno**: no deprecia; aparece 3 veces en el año 3 (venta, VL, ajuste) y no paga impuesto porque venta = VL. [Consulta 02/10]
2. **Tecnología y obras** se deprecian del todo en 3 años y no tienen salvamento → VL 0, no hay venta.
3. **WC**: el ΔWC de cada año está **un año antes**; el recupero es el total acumulado (37.500).
4. La UAI del año 1 es casi 0, pero el flujo de caja da positivo por el ajuste de las depreciaciones.

> [!warning] Diferencias con la [Planilla amigo]
> La planilla pone obras físicas en **\$15.000** (el enunciado dice \$20.000) y no tiene el WC. Las depreciaciones y la UAI coinciden.

## Las preguntas 1–3 (sensibilización)

1. **Precio de equilibrio de largo plazo** = el que hace **VAN = 0**.
2. **Cantidad mínima anual** para estar indiferente = la que hace VAN = 0. Mantenés la relación de crecimiento entre años (Q₂ y Q₃ en función de Q₁) y movés solo Q₁. [Consulta 02/10]
3. **Costo máximo del saborizante** = el que hace VAN = 0, con todo lo demás fijo.

Se resuelven tanteando (bisección) o con *Buscar objetivo* en Excel. **No entra en el parcial.** [Clase 25/09] [Consulta 02/10]

## Fuentes
[Guía ej 34] · [Consulta 02/10] · [Clase 25/09] · [Planilla amigo: Flamingo]
