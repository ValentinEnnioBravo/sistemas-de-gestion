---
tags: [sdg, precio]
aliases: [Markup, Margen, Precio de equilibrio, Elasticidad, Punto de equilibrio]
---

# 07 · Precio: markup, margen, equilibrio y elasticidad

← [[06 Costos, producción y stock]] · siguiente → [[08 Sueldos, indemnizaciones y ahorros]]

## 1. Costo total unitario (CTu)

$$CT_u = CV_u + \frac{CF_{producción}}{Q_{\text{producida}}}$$

- El **costo fijo unitario** se saca dividiendo por las unidades **producidas** (no las vendidas). [Clase 20/10]
- A más unidades, menor costo fijo unitario: **economía de escala** → [[06 Costos, producción y stock]] (sección 8).
- **Qué entra** en el costo para el markup: MP, MOD, gastos fabriles, mano de obra indirecta de planta, **depreciación de máquinas de planta** y sueldos de empleados que ya estaban (aunque no sean incrementales para el flujo). [Clase 16/10] [Clase 20/10] [Clase 23/10]
- **Qué no entra**: comisiones, sueldos de vendedores y analistas comerciales (S&M), administración (G&A), intereses (financiero). [Clase 20/10]

> [!warning] ⚠️ Consultar: depreciación de la máquina **nueva** del proyecto en el markup
> - [Clase 16/10]: *"En la depreciación nueva, no la voy a incluir dentro del costo. Porque todavía no está aprobado."*
> - [Clase 20/10]: la depreciación de máquinas de planta *"tiene que estar"*. Ante *"las anteriores sí y la nueva no"* respondió *"Correcto"*, pero después explicó que si la máquina hace falta para producir, el producto *tiene* que absorber su depreciación.
>
> **Seguro**: incluí la depreciación de activos **existentes o traídos** al proyecto. Para la máquina nueva, poné un supuesto o preguntá.

## 2. Markup vs margen

| | **Markup** (sobre el costo) | **Margen** (sobre el precio) |
|---|---|---|
| Fórmula | $P = CT_u \times (1 + mk)$ | $\text{margen} = \dfrac{P - C}{P}$ → $P = \dfrac{C}{1 - m}$ |
| Ejemplo costo 100, 80% | P = **180** | P = **500** |

- **Markup**: *"El costo total unitario lo multiplicás por el markup y ahí tenés el precio de venta unitario."* [Clase 20/10]
- **Margen bruto**: un alumno sumaba 100 + 80% = 180, pero así el margen da 80/180 = **44%**, no 80%. La forma correcta es plantear margen = M/V = 0,8 y despejar → **P = 500**. [Clase 16/10]

> [!warning] ⚠️ Consultar: ej 50 Piletazo ("mark-up de 70%")
> La [Planilla amigo] lo resuelve como **margen** (C/V = 0,3 → P = C/0,3). Con la definición de clase (markup multiplica) sería **P = C × 1,70**. Para el parcial: si dice **markup**, multiplicá por (1 + mk). Si dice **margen**, dividí por (1 − m).

## 3. Ej 51 · Markup sobre el valor libro (con IVA)

> "Vender todas las maquinarias adquiridas hace 9 años por \$4,84M con un markup del 20% sobre el VL (IVA incluido)."

| Paso | Cálculo | Resultado |
|---|---|---:|
| Precio de venta sin IVA | 4.840.000 / 1,21 | **4.000.000** → IAI |
| Valor libro | 4.000.000 / 1,20 | **3.333.333** → GND |
| Ganancia gravada | 4.000.000 − 3.333.333 | 666.667 |

(Es una lectura de los datos del enunciado, no salió de una resolución oficial.)

## 4. Precio de equilibrio

| Tipo | Condición | Cómo se calcula |
|---|---|---|
| **Corto plazo** (punto de equilibrio) | Ingresos = costos totales del año | Fórmula directa |
| **Largo plazo** | **VAN = 0** | Buscar objetivo / tanteo → **no se toma en papel** |

$$Q_e = \frac{CF}{P - CV_u} \qquad\qquad P_e = \frac{CF + CV_u \cdot Q}{Q}$$

- **Margen de contribución** = P − CVu (lo que aporta cada unidad a cubrir fijos). [Clase 16/10]
- El **costo fijo** entra completo (no unitario). La **Q** es la que vas a **vender**. [Clase 20/10]
- **Intereses: nunca** (son financiación; el precio tiene que salir igual con el flujo puro). [Consulta 02/10] [Clase 20/10]

> [!warning] ⚠️ Consultar: ¿la depreciación entra en el precio de equilibrio?
> - Gonzalo (Toldo): *"las amortizaciones no son un costo"* → no las incluyó. [Consulta 02/10]
> - Jorge: en el equilibrio **económico**, si invertiste en máquinas, la depreciación *"la tengo adentro del costo fijo… tendrían que estar"*. [Clase 20/10]
>
> **Criterio**: Jorge manda → **incluirla** como costo fijo. Escribí el supuesto.

### Toldo (ej 45): el precio del año 1 "para quedar en equilibrio" con comisión sobre la venta

Si la comisión es un % de la venta, depende del precio (es circular). Se despeja: [Consulta 02/10]

$$P \cdot Q = CV + CF + c \cdot P \cdot Q \;\;\Rightarrow\;\; P = \frac{CV + CF}{Q\,(1 - c)}$$

(Con c = 1% se divide por 0,99.)

## 5. Elasticidad precio de la demanda

$$E = \frac{\Delta Q / Q_1}{\Delta P / P_1} \quad\Rightarrow\quad P_2 = P_1 \left(1 + \frac{(Q_2 - Q_1)/Q_1}{E}\right)$$

- E es **negativa** en una demanda normal: si te dan "elasticidad 0,9", usá **−0,9**. Si la cantidad sube, el precio baja.
- Se usa con **variaciones porcentuales**, no con diferencias de unidades.
- Supone que **todas las demás variables quedan fijas** (la demanda es multivariable). [Clase 25/09]

### Ej 46 Bielsa (verificado contra la clase)

Precio año 2 = \$350 · E = −0,9

| Año | Q | ΔQ% | Precio |
|---|---:|---:|---:|
| 2 | 80.000 | — | 350,00 |
| 3 | 100.000 | +25,0% | 350 × (1 − 0,25/0,9) = **252,78** |
| 4 | 120.000 | +20,0% | **196,60** |
| 5 | 130.000 | +8,3% | **178,40** |

### Ej 41 · Si parte del aumento de demanda NO es por precio

> "En el año 4 se prevé un incremento de demanda de 500 unidades por acciones comerciales y las otras 500 por variación del precio, elasticidad 1,5."

Las 500 de la promo **se sacan** de la cuenta: la elasticidad se calcula **solo con las 500 que vienen por precio**. [Clase 20/10]

P₃ = 200 × 1,1 × 1,1 = 242 · ΔQ% = 500 / 2.000 = 25% → P₄ = 242 × (1 − 0,25/1,5) ≈ **201,67**

### Ej 50 · Elasticidad "de pregunta"
Si baja el precio y las unidades se mantienen ante un mercado que cae, la planilla resuelve E ≈ **−1,2** (precio −5% ante caída de mercado 6%: 6/5 = 1,2). Es una lectura de la planilla.

## Fuentes
[Clase 16/10] · [Clase 20/10] · [Clase 23/10] · [Clase 25/09] · [Consulta 02/10] · [Guía ej 34, 35, 41, 45, 46, 50, 51] · [Planilla amigo: Toldo, 50] · [Resumen amigo: Markup, Elasticidad]
