---
tags: [sdg, ingresos, ventas]
aliases: [Venta neta, Venta bruta, IIBB, IVA, Regalías, Comisiones, Descuentos comerciales]
---

# 05 · Ventas, IIBB e IVA

← [[04 VAN, TIR y Payback]] · siguiente → [[06 Costos, producción y stock]]

## 1. De venta bruta a venta neta (criterio de Jorge)

La hoja de ventas reproduce la estructura del estado de resultados (*gross to net*). [Clase 16/10] [Clase 20/10]

| Paso | Concepto | Base de cálculo |
|---|---|---|
| 1 | **Venta bruta** | P × Q (cantidad **vendida**) |
| 2 | − **Devoluciones** | sobre la **venta bruta** (si el % es "de la venta bruta") |
| 3 | − **Descuentos comerciales** | sobre **bruta − devoluciones** (si te devuelven, el descuento también se netea) |
| 4 | − **Ingresos brutos (IIBB)** | sobre **bruta − devoluciones − descuentos** |
| = | **Venta neta** | → va a **IAI** |

> *"Ingresos brutos, ¿sobre qué base lo calculo? Por la bruta, esa es la que dice la lógica, pero es la bruta menos los descuentos comerciales."* [Clase 20/10]
> *"Yo pago ingresos brutos por lo vendido neto, neto de devoluciones y neto de descuentos."* [Clase 16/10]

> [!important] El enunciado manda
> Si dice "descuento del 2% **de la venta bruta**", se calcula sobre la bruta aunque haya devoluciones (ej 41, 50, 51). La tabla de arriba es el criterio **por defecto**.

### Ejemplo numérico (verificado)

Venta bruta \$1.000.000 · devoluciones 1% · descuentos 2% · IIBB 1,5% · comisión 1% · regalía 5% de la venta neta.

| Concepto | Cálculo | Importe |
|---|---|---:|
| Venta bruta | | 1.000.000 |
| − Devoluciones 1% | 1.000.000 × 1% | −10.000 |
| − Descuentos 2% | (1.000.000 − 10.000) × 2% | −19.800 |
| − IIBB 1,5% | (1.000.000 − 10.000 − 19.800) × 1,5% | −14.553 |
| **= Venta neta (IAI)** | | **955.647** |
| Comisión 1% **(EAI, aparte)** | sobre venta neta comercial: 970.200 × 1% | 9.702 |
| Regalía 5% **(EAI, aparte)** | 955.647 × 5% | 47.782 |

## 2. Regalías y comisiones NO restan para llegar a la venta neta

| Concepto | Dónde va | Base |
|---|---|---|
| **Regalía** | **EAI**. Es un costo (*"van abajo, como sales & marketing expenses, restando"*) | La que diga el enunciado: venta neta, bruta o costo |
| **Comisión de venta** | **EAI**. Gasto de *sales & marketing*, variable con la venta | La que diga el enunciado |
| **Licencia de uso de marca** | **EAI** en el año en que **se paga** | → [[09 Inversión inicial y depreciación]] |

> *"La comisión de venta no es menos venta neta. Es un gasto de sales and marketing que tiene la particularidad de ser variable dependiente de la venta."* [Clase 20/10]

> [!warning] ⚠️ Diferencia con el resumen del amigo
> El ejemplo del [Resumen amigo] calcula el **IIBB después de restar la regalía**. Según Jorge, la regalía **no** se resta para llegar a la venta neta: es un egreso aparte. Usá ese orden solo si un enunciado lo pide explícitamente.

### ¿Sobre qué venta se calcula la comisión o la regalía?
- **Seguí el enunciado** (*"si te dice sobre la venta neta, venta neta"*).
- Si dice solo "sobre la venta" y **no hay** descuentos, devoluciones ni IIBB → es la bruta (es la única).
- Si dice "sobre la venta" y **sí hay** descuentos → **escribí un supuesto**. [Clase 20/10] [Clase 23/10]

> [!note] Bielsista: "venta neta comercial"
> Para Jorge la comisión debería ir sobre la **venta neta comercial** = P×Q − descuentos − devoluciones, **sin** restar IIBB (*"ingresos brutos es un ticket to play"*). Si el enunciado dice "venta neta", usás venta neta. [Clase 20/10]

## 3. Ventas en varias regiones o canales

Una línea por región o canal (ej 48 Polo: AMBA y Córdoba, mayoristas y supermercados, cada una con su descuento y su IIBB). Es más fácil de corregir y te equivocás menos. *"No la pico ni en pedo… ponele más líneas."* [Clase 16/10]

| Polo (ej 48) | AMBA | Córdoba (desde año 3) |
|---|---|---|
| Canal | 60% mayoristas (−40%) / 40% súper (−30%) | 100% mayoristas (−40%) |
| Participación | 90% del total (desde año 3) | 10% del total |
| IIBB | 1,5% | 2% |

## 4. IVA: nunca va en el flujo

> [!important] Regla
> - El IVA **no es ganancia ni pérdida**: es un "pasamanos" (débito − crédito fiscal). **No entra al flujo.** [Clase 20/10] [Clase 23/10]
> - Si un importe dice **"IVA incluido"** → se lo sacás: **÷ 1,21** (o **÷ 1,105** si la alícuota es 10,5%).
> - Si **no dice nada** → se toma como neto, no hagas nada. [Clase 23/10] [Resumen amigo]
> - El préstamo también se calcula **sobre el valor sin IVA** (Toldo: 75% de USD 1.250.000 / 1,21). [Consulta 02/10] [Clase 20/10]

| Ejercicio | Dato con IVA | Neto |
|---|---|---:|
| 45 Toldo | Máquina USD 1.250.000 IVA incl. × \$45 | \$46.487.603 |
| 48 Polo | Inversión \$5M IVA incl. | \$4.132.231 |
| 50 Piletazo | Inversión \$50M IVA incl. 21% | \$41.322.314 |
| 51 Scaloni | Luz, gas, ABL \$1.210.000 (IVA 10,5%) | \$1.095.023 |
| 51 Scaloni | Venta de maquinarias \$4,84M IVA incl. | \$4.000.000 |
| 47 | Ticket \$1.210 IVA incl. | \$1.000 |

> [!note] Bielsista: cuándo sí importaría el IVA
> Solo cuando entre el IVA compra y el IVA venta pasa **más de un año** (fabricar un barco, un edificio, una película): ahí podría ir como INAI/ENAI por el diferimiento. *"Es muy border y dudo que vaya a entrar."* [Clase 20/10] [Consulta 02/10]

## 5. Ventas perdidas por falta de capacidad

Si no tenés capacidad, **no ponés la venta** (*"no puedo vender lo que no tengo"*). En un análisis incremental, la venta perdida vale el **margen** (venta − costo total unitario), no la venta entera. [Clase 16/10] → [[12 Capacidad - cuándo comprar la máquina o stockear]]

## Fuentes
[Clase 16/10] · [Clase 20/10] · [Clase 23/10] · [Consulta 02/10] · [Guía ej 41, 45, 47, 48, 50, 51] · [Resumen amigo: Ventas, IVA] · [Planilla amigo: 48 Polo, 50 Piletazo]
