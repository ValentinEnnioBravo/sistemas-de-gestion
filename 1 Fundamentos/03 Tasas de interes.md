---
tags: [sdg, fundamentos, tasas]
aliases: [TNA, TEA, TEM, Capitalización, Tasa efectiva]
---

# 03 · Tasas de interés

← [[02 Estructura del flujo de fondos]] · siguiente → [[04 VAN, TIR y Payback]]

El flujo es **anual**, así que **toda tasa se lleva a efectiva anual (TEA)** antes de usarla: en el VAN, en el préstamo y en el WACC.

> [!warning] Trampa clásica: "tasa anual del X%"
> Si dice **"tasa anual del 60% capitalizable mensualmente"**, es una **TNA**. Hay que pasarla a TEA (Bielsa: 60% → **79,59%**). En la planilla: *"Dice TASA ANUAL → TNA ⇒ trampa ⇒ calcular TEA"*. [Planilla amigo, Bielsa]

## 1. Definiciones

| Tasa | Qué es |
|---|---|
| **TNA** (nominal anual) | Tasa "dibujada": se divide por la cantidad de capitalizaciones del año para sacar la tasa del período |
| **Tasa del período** (TEM, efectiva bimestral, etc.) | TNA / m, o la que te dan directamente |
| **TEA** (efectiva anual) | La que realmente rinde/cuesta en un año |

## 2. Fórmulas

**De TNA (capitalizable m veces por año) a TEA:**

$$TEA = \left(1 + \frac{TNA}{m}\right)^{m} - 1$$

**De una tasa efectiva de un período a TEA** (por ejemplo una mensual):

$$TEA = (1 + i_{período})^{\text{períodos por año}} - 1$$

**Forma general de la planilla** (notación de la cátedra, en días):

$$i_{(w)} = \left(1 + J_{(t)} \cdot \frac{t}{u_t}\right)^{w/t} - 1$$

| Símbolo | Significado | Ejemplo Toldo |
|---|---|---|
| $J_{(t)}$ | TNA capitalizable cada *t* días | 0,42 |
| $t$ | días del período de capitalización | 30 (mensual) |
| $u_t$ | días del año comercial | 360 |
| $w$ | días del plazo de la tasa que querés | 360 (anual) |
| $i_{(w)}$ | tasa efectiva para *w* días | **51,11%** |

| Capitalización | m | días *t* |
|---|---:|---:|
| Mensual | 12 | 30 |
| Bimestral / "a 60 días" | 6 | 60 |
| Trimestral / "a 90 días" | 4 | 90 |
| Semestral | 2 | 180 |
| Anual | 1 | 360 |

## 3. Tabla de conversiones de los ejercicios (verificadas)

| Ejercicio | Dato | Cálculo | TEA |
|---|---|---|---:|
| Guía 1 | \$1.000, TNA 25%, intereses mensuales | 1.000 × (1 + 0,25/12)¹² | **\$1.280,73** ✔ |
| 45 Toldo (préstamo) | 42 puntos nominal, cap. mensual | (1 + 0,035)¹² − 1 | **51,11%** |
| 45 Toldo (descuento) | resguardo 2,5% **mensual** | (1,025)¹² − 1 | **34,49%** |
| 46 Bielsa | TNA 60% cap. mensual | (1,05)¹² − 1 | **79,59%** |
| 37 | TNA 10% cap. bimestral | (1 + 0,10/6)⁶ − 1 | **10,43%** |
| 47 (1er préstamo) | 60% cap. trimestral | (1,15)⁴ − 1 | **74,90%** |
| 47 (2do préstamo) | 40% cap. bimestral | (1 + 0,40/6)⁶ − 1 | **47,29%** |
| 50 Piletazo | 7% efectiva **bimestral** | (1,07)⁶ − 1 | **50,07%** |
| 51 Scaloni | TNA 35% cap. semestral | (1 + 0,35/2)² − 1 | **38,06%** |

> [!tip] Respuestas teóricas de la guía (ej 2, 3, 6)
> - **A igual TNA, cuanto más frecuente la capitalización, más rinde** (ej 2: bimestral > trimestral > anual).
> - **"25% anual es mejor que 24% mensual porque 25 > 24" es FALSO**: 24% capitalizable mensual da 26,8% efectiva (ej 3).
> - Siempre comparar **en efectiva**, nunca en nominal.

## 4. Valor presente (para mover plata en el tiempo)

$$VP = \frac{VF}{(1+i)^n}$$

Ej 5: para tener \$10.000 en 3 años con TNA 6% bimestral → $VP = 10.000/(1+0{,}01)^{18} =$ **\$8.360,17** ✔.

## 5. Tasa de descuento ≠ tasa del préstamo

- **Tasa de descuento** (también: costo de oportunidad, tasa de corte, costo promedio del capital, tasa de resguardo): descuenta los flujos → VAN. Casi siempre es el **WACC** ([[15 WACC y tasa de descuento]]).
- **Tasa del préstamo**: sirve para armar la tabla de cuotas ([[14 Préstamos - francés, alemán, americano y gracia]]).

Las dos se pasan a TEA, pero son cosas distintas.

## Fuentes
[Guía ej 1–6] · [Guía ej 37, 45, 46, 47, 50, 51] · [Planilla amigo: Toldo (fórmula J(t), i(w)), Bielsa, 37, 47, Calamar] · [Resumen amigo: TNA y TEA]
