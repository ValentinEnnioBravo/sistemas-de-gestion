---
tags: [sdg, fundamentos, evaluacion]
aliases: [VAN, TIR, Payback, VNA]
---

# 04 · VAN, TIR y Payback

← [[03 Tasas de interés]] · siguiente → [[05 Ventas, IIBB e IVA]]

## 1. VAN (Valor Actual Neto)

$$VAN = FC_0 + \sum_{t=1}^{n} \frac{FC_t}{(1+r)^t}$$

- $FC_0$ es el flujo del **año 0** y **no se descuenta**.
- $r$ = tasa de descuento **efectiva anual** (normalmente el WACC).

> [!warning] Excel: VNA no incluye el año 0
> `=VNA(r; FC1:FCn) + FC0`. Si metés el año 0 adentro de VNA, lo estás descontando un año de más. [Resumen amigo, checklist]

| Resultado | Interpretación |
|---|---|
| VAN > 0 | El proyecto rinde **más** que la tasa exigida → conviene |
| VAN = 0 | **Indiferente** respecto del costo de oportunidad [Guía ej 16] |
| VAN < 0 | Rinde **menos** que la tasa exigida. **No significa que pierda plata**: puede ganar, pero menos que la alternativa [Consulta 02/10] |

> [!example] Ej 9 de la guía
> Proyectos A y B de \$20.000 con flujos chicos; el banco paga 5%. VAN(A) = −1.730, VAN(B) = −426 → **conviene el banco**. La TIR de A (1,7%) y la de B (4,31%) son positivas, pero menores al 5%.

**Sensibilidad a la tasa** [Guía ej 17]: los proyectos con flujos grandes **al final** son más sensibles a cambios de tasa, porque el exponente del descuento es mayor.

## 2. TIR (Tasa Interna de Retorno)

Es la tasa que hace **VAN = 0**.

- Es **única** solo si la función VAN(i) es **monótona decreciente** [Guía ej 8]. Si los flujos cambian de signo varias veces puede haber **varias TIR** o ninguna [Guía ej 10, 12].
- Si no hay ningún flujo negativo, **no existe TIR** [Guía ej 12a].
- Deficiencias frente al VAN: puede no existir o no ser única, y *"no puede romper la temporalidad de la tasa"* [Guía ej 10].

> [!tip] Para el parcial: la TIR no se calcula
> *"¿La TIR? No va. ¿Qué carajo de valor me agrega?… Para eso está el Excel."* [Clase 23/10]
> Sí tenés que saber **interpretarla** (las preguntas teóricas de arriba).

## 3. Payback (período de recupero)

Se arma el **flujo acumulado** y se busca **el primer año en que deja de ser negativo**.

| Año | 0 | 1 | 2 | 3 |
|---|---:|---:|---:|---:|
| Flujo (ej 11) | −10.000 | 5.000 | 5.000 | 1.000 |
| Acumulado | −10.000 | −5.000 | **0** | 1.000 |

→ **Payback = 2 años** [Guía ej 11]. Ojo: el payback no dice si conviene. Con tasa 10% el VAN del ej 11 da **−571** → no conviene.

> [!important] Si el acumulado vuelve a ser negativo
> El payback es **el primero** en que lo recuperaste. *"Si te la devolví el primer año, si después la chocaste la Ferrari… el payback estaba hecho."* [Clase 23/10]

> [!note] Variante con fracción de año (planilla, ej 47)
> La planilla calcula el payback con fracción: año negativo + |acumulado negativo| / flujo del año siguiente ("1 año, 10 meses y 23 días"). En clase no se habló de esta variante. Si la usás, aclará cómo la calculaste.

## 4. Punto de equilibrio y VAN = 0

- **Equilibrio de corto plazo**: ingresos totales = costos totales, con la fórmula de punto de equilibrio.
- **Precio / cantidad de equilibrio de largo plazo**: el valor que hace **VAN = 0** [Guía ej 34 respuestas; Clase 20/10].

En Excel se saca con *Buscar objetivo*. A mano solo se puede tanteando (bisección), por eso **no se toma en el parcial en papel**. [Clase 20/10] [Consulta 02/10] → detalle en [[07 Precio - markup, margen, equilibrio y elasticidad]].

## 5. Riesgo [Guía ej 22, 24]

El riesgo se puede meter **en la tasa** o **en los flujos**. Una beta < 0 da una tasa de descuento menor a la tasa libre de riesgo.

## Fuentes
[Guía ej 7–17, 21, 22, 24, 34] · [Clase 20/10] · [Clase 23/10] · [Consulta 02/10] · [Planilla amigo: 47, Calamar] · [Resumen amigo]
