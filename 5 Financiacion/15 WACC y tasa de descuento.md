---
tags: [sdg, financiacion, wacc]
aliases: [WACC, CAPM, Ke, Kd, Beta, Tasa de descuento, ROE]
---

# 15 · WACC y tasa de descuento

← [[14 Préstamos - francés, alemán, americano y gracia]] · siguiente → [[16 VAN puro vs VAN del accionista - apalancamiento]]

## 1. Fórmula

$$WACC = K_e \cdot X_e + K_d \cdot X_d \cdot (1 - T)$$

| Símbolo | Qué es | De dónde sale |
|---|---|---|
| $K_e$ | Costo del capital propio | **CAPM** (o ROE, o suma de riesgos) |
| $K_d$ | Costo de la deuda **existente** | Promedio **ponderado** de las deudas previas |
| $X_e$, $X_d$ | Proporción de capital propio y de deuda | "El equity financia el 60% de los activos", o el balance |
| $T$ | Tasa de IIGG | Enunciado |

> [!important] El WACC es la tasa de la empresa ANTES del proyecto
> *"Cuando yo voy a calcular el WACC, es con el estado de situación previo al proyecto."* El **préstamo nuevo** del proyecto **no** entra en el Kd (*"no lo pedí todavía, lo voy a estar evaluando"*). [Clase 16/10] [Clase 20/10]
> Trampas de este tipo: ej 50 (el crédito de \$25M con *), ej 51, ej 47.

## 2. Ke por CAPM

$$K_e = R_f + \beta\,(R_m - R_f) \;[+\; RP]$$

- $R_f$ = **tasa libre de riesgo** (*risk free*): lo que rinde una inversión sin riesgo, por ejemplo un bono del tesoro. Es el piso de la tasa.
- $R_m$ = **rendimiento esperado del mercado** (*market*): lo que rinde en promedio el mercado de acciones.
- $\beta$ = **riesgo no diversificable** de la empresa o sector: cuánto se mueve su acción respecto del mercado (β > 1 se mueve más, β < 1 menos).
- $R_m - R_f$ = **prima de riesgo de mercado**, también llamada **premio por riesgo** (o premio de mercado). Son sinónimos: si el enunciado dice "el premio por riesgo es 8%", ese 8% ya es $R_m - R_f$ y **no hay que restar nada** (a veces te dan la prima directo).
- $RP$ = **riesgo país**, si lo dan (1.350 pb = 13,5%).
- "Acción perfectamente correlacionada con el mercado" → **β = 1**.

| Ej | Datos | Ke |
|---|---|---:|
| 30 | Rf 4%, β = 1, Rm 6% | **6%** (sin deuda → WACC = 6%) |
| 37 | Rf 3,5%, β 1,2, Rm 10% | 3,5 + 1,2 × 6,5 = **11,3%** |
| 48 Polo | Rf 5%, β 0,9673 (regresión), Rm 10%, RP 13,5% | **23,34%** [Planilla amigo] |
| 50 Piletazo | Rf 5%, Rm 25%, β = **1,8** | 5 + 1,8 × 20 = **41%** |

> [!tip] Ej 50: beta con una función
> *"Las acciones de Piletazo son más volátiles que el mercado… f(x) = x² − 1,3x + 0,9, cuyas raíces son 0,5 y 1,8."* Más volátil que el mercado → β > 1 → **β = 1,8**. [Planilla amigo]

> [!note] Beta por regresión (ej 48)
> $\beta = \dfrac{Cov(R_m, R_{acción})}{Var(R_m)}$. Es cosa de Excel: **no se toma en el parcial**. [Clase 20/10]

## 3. Kd: promedio ponderado de las deudas existentes

$$K_d = \frac{\sum D_i \cdot k_i}{\sum D_i}$$

| Ej | Deudas | Kd |
|---|---|---:|
| 36 | 30% al 8%, 70% al 12% | **10,8%** |
| 48 Polo | 100.000 al 10% · 120.000 al 11% · 300.000 al 14% | **12,54%** |
| 50 Piletazo | 2M al 18% · 6M al 35% · 5M al 30% (**sin** el de 25M) | **30,46%** |
| Resumen amigo | 100.000 al 10% · 900.000 al 20% | **19%** (no 15%) |

### Qué deudas entran
- ✅ Deudas **financieras** (bancarias, de largo plazo, obligaciones negociables).
- ❌ **Proveedores**: financian el capital de trabajo, no los activos. *"La financiación generalmente es todo menos proveedores."* [Clase 16/10] [Clase 20/10]
- ❌ El **préstamo nuevo** del proyecto.

> [!warning] Si no hay datos de la deuda
> *"Si no tenés estructura de la deuda, Kd = 0."* [Clase 20/10]
> El ej 47 se va a corregir agregando un Kd actual del 10%. [Clase 20/10]

## 4. Xe y Xd

| Fuente del dato | Cómo |
|---|---|
| "El equity financia el 60% de los activos" / "30% deuda y 70% capital propio" | Directo |
| **Valor de mercado** (precio de la acción × cantidad de acciones) | $X_e = E / (E + D)$. Ej 30: 4,5 × 100.000 = 450.000, sin deuda → $X_e = 100\%$ |
| **Balance** | Sacás **proveedores**: $X_d$ = deudas financieras / (deudas financieras + PN) [Clase 16/10] [Clase 20/10] |

*"Siempre tengo que tomar los valores de mercado por sobre los valores contables. Si no tengo los datos del mercado, voy al balance."* [Clase 16/10]

> [!example] Ej 36 (balance)
> Deudas 300.000 · PN = 152.600 + 4.444 = 157.044 · Proveedores 41.531 (**afuera**).
> $X_d = 300.000 / 457.044 ≈ 65,6\%$ · $X_e ≈ 34,4\%$ · $K_d = 10{,}8\%$ · T = 35%.
> (Proporciones calculadas aplicando el criterio de clase.)

## 5. Ke cuando NO hay CAPM

| Situación | Ke | Fuente |
|---|---|---|
| La empresa **no cotiza** | **ROE** = Utilidad neta / Patrimonio neto | [Clase 16/10] [Clase 23/10] |
| Empresa **nueva / startup** (sin historia) | **Suma de riesgos**: Rf + riesgo país + riesgo sector + riesgo management… | [Clase 23/10] |
| Ej 23 de la guía (Rf 10%, RP 2000 pb, β 1,3, riesgo empresa 2%) | La respuesta **32%** coincide con 10% + 20% + 2% (sin Rm, la β no se puede aplicar) | [Guía ej 23] |

> [!warning] ⚠️ Datos que faltan en la guía
> - **Ej 51**: falta Rm (o la prima de riesgo). Jorge: *"No está el hijo de su madre… hay que agregarlo"* (va en la versión siguiente de la guía). [Clase 20/10]
> - **Ej 36**: no da datos para Ke (pregunta abierta en la [Planilla amigo]).

## 6. ¿Con qué tasa se descuenta cada flujo?

> [!important] Criterio de la cátedra: el WACC para TODO
> El **flujo puro** y el **flujo del accionista** se descuentan **los dos con el WACC**. Los libros dicen que el del accionista va con Ke y que hay que apalancar la beta. La cátedra lo simplificó a propósito: *"Esa fue la decisión que tomamos… el WACC se calcula así y es lo mismo para un flujo que el otro."* [Clase 25/09] [Clase 16/10]

> [!note] Bielsista: los tres cash flows [Clase 16/10]
> - **Free cash flow**: EBIT × (1 − T) + depreciaciones − ΔWC − CAPEX (sin deuda).
> - **Cash flow del accionista**: además resta intereses y cancelaciones, y suma la deuda nueva.
> - **Capital cash flow**.
>
> Para el parcial alcanza con el template de [[02 Estructura del flujo de fondos]].

## 7. Pregunta típica: "¿Hay otra alternativa para la tasa de corte?" (ej 38)
Sí: Ke solo (si no hay deuda), ROE, suma de riesgos, o el costo de oportunidad del inversor (tasa de resguardo, como en Toldo). [Clase 23/10] [Guía ej 45]

## 8. "¿En qué casos no podría usar el WACC?" (ej 43.5)
Por ejemplo, cuando no hay datos de mercado (no cotiza, startup) → ROE o suma de riesgos. [Clase 16/10] [Clase 23/10]

## Fuentes
[Guía ej 23, 30, 36, 37, 38, 43, 47, 48, 50, 51] · [Clase 16/10] · [Clase 20/10] · [Clase 23/10] · [Clase 25/09] · [Resumen amigo: WACC, CAPM] · [Planilla amigo: 30, 36, 37, 47, 48, 50]
