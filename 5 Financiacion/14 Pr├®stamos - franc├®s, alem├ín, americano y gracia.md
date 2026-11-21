---
tags: [sdg, financiacion, prestamos]
aliases: [Préstamo, Sistema francés, Sistema alemán, Sistema americano, Período de gracia, Cuota]
---

# 14 · Préstamos: francés, alemán, americano y gracia

← [[13 Capital de trabajo (Working Capital)]] · siguiente → [[15 WACC y tasa de descuento]]

## 1. Cómo entra un préstamo en el flujo (del accionista)

| Concepto | Fila | Año | Por qué |
|---|---|---|---|
| **Préstamo recibido** | **INAI** | 0 (o el que diga) | Permutativo: no es ganancia |
| **Intereses** | **EAI** | 1…n | Son gasto: **reducen el IIGG** (escudo fiscal) |
| **Amortización de capital** | **ENAI** | 1…n | Devolver lo prestado no es gasto |

> [!important] Nunca pongas la cuota entera
> *"¿Por qué no pongo la cuota? Porque el interés lo podés deducir de ganancias. Si pongo la cuota ahí, me estoy perdiendo de ahorrarme el 35% del interés."* [Clase 25/09]

### ¿Sobre qué base se calcula el préstamo?
- **Lo que diga el enunciado** ("75% del valor de compra", "80% de la inversión inicial", "activo fijo", "también el WC"…). [Clase 20/10]
- "Activo fijo" = máquina **+ instalación** (y capacitación, si es parte). [Clase 20/10]
- **Siempre sin IVA**. [Consulta 02/10] [Clase 20/10]
- La tasa se pasa a **efectiva anual** ([[03 Tasas de interés]]). La cuota es anual.

| Ej | Base | Monto |
|---|---|---:|
| 45 Toldo | 75% de USD 1.250.000 / 1,21 × 45 | \$34.865.702 |
| 46 Bielsa | 70% × (1.000.000 + 10% instalación) | \$770.000 |
| 31 | 40% de la inversión en fresado (\$130.000) | \$52.000 |
| 37 | 80% de la inversión inicial | \$80.000 |
| 42 Cervezas | 75% del activo fijo (\$23M) + 100% del WC (\$900.000) | \$18.150.000 |

## 2. Los tres sistemas

$$\text{Interés}_t = \text{Saldo inicial}_t \times i \qquad \text{(siempre, en cualquier sistema)}$$

> [!note] Qué es el "saldo" de cada fila
> El saldo de la fila del año *t* es el **saldo inicial** de ese año (lo que debés **antes** de pagar la amortización de *t*). Es igual al saldo final del año *t − 1*. Por eso el interés se calcula sobre el saldo **de la misma fila**, y por eso el año 1 usa el préstamo completo.

| Sistema | Amortización de capital | Cuota | Interés |
|---|---|---|---|
| **Francés** | Creciente | **Constante** | Decreciente |
| **Alemán** | **Constante** = P / n | Decreciente | Decreciente |
| **Americano** | Todo en la **última** cuota | Solo interés hasta el final | Constante |

**Cuota francesa:**

$$C = P \cdot \frac{i\,(1+i)^n}{(1+i)^n - 1} \qquad \text{(en Excel: =PAGO)}$$

> [!tip] La fórmula se lleva
> *"Llevate la fórmula, porque no me la acuerdo yo."* Podés llevar todas las fórmulas que quieras. [Clase 16/10] [Clase 20/10]

### Ej 27 de la guía (verificado): \$15.000, 3 años, TEA 10%

| Año | Francés: saldo | Cuota | Interés | Capital | Alemán: saldo | Cuota | Interés | Capital | Americano: cuota |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| 1 | 15.000 | 6.032 | 1.500 | 4.532 | 15.000 | 6.500 | 1.500 | 5.000 | 1.500 |
| 2 | 10.468 | 6.032 | 1.047 | 4.985 | 10.000 | 6.000 | 1.000 | 5.000 | 1.500 |
| 3 | 5.483 | 6.032 | 548 | 5.483 | 5.000 | 5.500 | 500 | 5.000 | 16.500 |

### Cómo se calcula cada columna (receta de la tabla)

Se arma **fila por fila**, de arriba hacia abajo. Siempre en este orden:

| Columna | Qué es | Cómo se calcula |
|---|---|---|
| **Saldo inicial** (capital adeudado) | Lo que debés al **empezar** el año | Año 1 = **P** (el préstamo). Después = saldo final del año anterior |
| **Interés** | Costo del año | **Saldo inicial × i** (en todos los sistemas, y también en gracia) |
| **Amortización** (capital que devolvés) | Parte de la cuota que baja la deuda | Francés: **Cuota − Interés** · Alemán: **P / n** (constante) · Americano: **0** hasta el último año, donde es **P** |
| **Cuota** | Lo que pagás en el año | Francés: **fórmula PAGO** (constante) · Alemán y americano: **Amortización + Interés** |
| **Saldo final** | Lo que queda debiendo | **Saldo inicial − Amortización** (el interés no lo toca) |

Control: el saldo final del último año tiene que dar **0**, y la suma de las amortizaciones tiene que dar **P**.

Dónde va cada cosa en el flujo: **interés → EAI**, **amortización → ENAI**, **la cuota entera nunca**. Ver sección 1.

> [!example] Ej 42 Cervezas: P = 18.150.000 · i = 10% · 6 cuotas iguales de capital desde el año 4 (alemán con gracia)
> Amortización = 18.150.000 / **6** = 3.025.000 (se divide por las cuotas, no por el plazo total).
>
> | Año | Saldo inicial | Interés (10%) | Amortización | Cuota | Saldo final |
> |---:|---:|---:|---:|---:|---:|
> | 1 | 18.150.000 | 1.815.000 | 0 | 1.815.000 | 18.150.000 |
> | 2 | 18.150.000 | 1.815.000 | 0 | 1.815.000 | 18.150.000 |
> | 3 | 18.150.000 | 1.815.000 | 0 | 1.815.000 | 18.150.000 |
> | 4 | 18.150.000 | 1.815.000 | 3.025.000 | 4.840.000 | 15.125.000 |
> | 5 | 15.125.000 | 1.512.500 | 3.025.000 | 4.537.500 | 12.100.000 |
> | 6 | 12.100.000 | 1.210.000 | 3.025.000 | 4.235.000 | 9.075.000 |
> | 7 | 9.075.000 | 907.500 | 3.025.000 | 3.932.500 | 6.050.000 |
> | 8 | 6.050.000 | 605.000 | 3.025.000 | 3.630.000 | 3.025.000 |
> | 9 | 3.025.000 | 302.500 | 3.025.000 | 3.327.500 | 0 |
> | 10 | 0 | 0 | 0 | 0 | 0 |

## 3. ¿Cuál elegir? (pregunta típica)

| Objetivo del enunciado | Sistema | Por qué |
|---|---|---|
| **"Pagar menos intereses al principio"** (Toldo) | **Alemán** | Devuelve más capital antes, así que el saldo (y el interés) baja más rápido [Guía ej 25] [Consulta 02/10] |
| **"Disminuir la base imponible a valor actual"** / **"pagar menos IIGG al principio"** (ej 26, 51) | **Francés** | Paga **más interés** en los primeros años → más deducción [Guía ej 26] |
| ¿En cuál se cancela capital antes? | Alemán [Guía ej 25] | |

> [!note] Detalle
> El interés del **año 1** es igual en los dos sistemas (P × i). La diferencia aparece desde el año 2. Toldo pide calcular los dos para comparar: *"pensé que se iba a resolver teóricamente, pero no, te hace calcular los dos"*. [Consulta 02/10]

## 4. Período de gracia

> [!important] Gracia de capital (el caso de la cátedra)
> - Durante la gracia **se pagan los intereses** sobre el saldo completo y **no se amortiza capital**.
> - Que te den gracia **no** quiere decir que no pagues: *"el que te presta es un garca, no te regala nada… full intereses"*.
> - El **plazo total no cambia**: el capital se devuelve en los **años restantes**.
>
> $$n_{cuotas} = \text{Plazo total} - \text{Años de gracia}$$
>
> [Clase 20/10] [Clase 23/10]

### Ejemplo: \$1.000.000, 5 años, 10% TEA, 1 año de gracia de capital (verificado)

| Año | Alemán: interés | Capital | Cuota | Francés (n = 4): interés | Capital | Cuota |
|---|---:|---:|---:|---:|---:|---:|
| 1 (gracia) | 100.000 | 0 | 100.000 | 100.000 | 0 | 100.000 |
| 2 | 100.000 | 250.000 | 350.000 | 100.000 | 215.471 | 315.471 |
| 3 | 75.000 | 250.000 | 325.000 | 78.453 | 237.018 | 315.471 |
| 4 | 50.000 | 250.000 | 300.000 | 54.751 | 260.720 | 315.471 |
| 5 | 25.000 | 250.000 | 275.000 | 28.679 | 286.792 | 315.471 |

- **Alemán**: capital / 4. *"Si fuesen en 5 serían 20.000; como es en 4, son 25.000."* El interés de los años 1 y 2 es el mismo (el saldo no bajó). [Clase 23/10]
- **Francés**: la fórmula de la cuota con **n = 4** sobre el saldo después de la gracia. [Clase 23/10]
- *"Es como pagar un año de intereses solamente y después arrancar un préstamo de 4 años con el mismo capital."* [Resumen amigo]

### Ej 42 Cervezas: "seis cuotas iguales de capital, la primera en el cuarto año"
Años 1–3: solo interés (10% × 18.150.000 = 1.815.000). Años 4–9: capital 18.150.000 / 6 = **3.025.000** + interés sobre saldo. [Planilla amigo]

> [!warning] Gracia total (no se paga nada)
> Si el enunciado dice que no se paga **ni capital ni interés**, ese año va **en blanco** y se arma el préstamo en los años restantes. Si dice que los intereses se **capitalizan**, el saldo crece. *"Va a depender del atorrante que haga el enunciado… va a estar muy explícito."* [Clase 23/10]

> [!note] Variante: juntar las cuotas diferidas
> Un alumno propuso pagar las dos cuotas juntas en el año 2. Jorge: *"Es creativo, no está mal"*, siempre que lo aclares y **no pagues más capital del que te prestaron**. Lo estándar es redistribuir en los años que quedan. [Clase 23/10]

## 5. Préstamo más largo que el proyecto

*"Todo lo que empieza en el proyecto termina en el proyecto."* En el **último año** del horizonte: [Clase 23/10]
- Ponés el **interés de ese año** (EAI) y la **amortización de ese año**.
- **Más** una línea ENAI **"cancelación de la deuda"** por el **capital pendiente**.
- **No** sumás intereses futuros (no se devengaron).

> [!note] Bielsista
> Puede haber gastos de cancelación anticipada o una cláusula que no te deje cancelar antes del año X. Eso lo dice el contrato. [Clase 23/10]
> (En [Clase 20/10] había sugerido sumar capital e interés. En [Clase 23/10] lo corrigió: **solo capital**.)

## 6. Otros casos

| Caso | Tratamiento | Fuente |
|---|---|---|
| **Préstamo no reembolsable** (ej. una beca) | INAI, **sin** intereses ni amortización | [Clase 20/10] |
| Varios préstamos para el proyecto (ej 47) | Una tabla por préstamo | [Planilla amigo, 47] |
| "Amortización de capital acumulado crece proporcionalmente" (ej 50) | La planilla lo resuelve como **francés** (7% bimestral → 50% TEA) | [Planilla amigo, 50] |
| Gastos administrativos del banco | Si hay, suelen estar dentro del capital (te dan menos en mano) | [Clase 23/10] |
| El préstamo del proyecto en el WACC | **No va**: no está aprobado → [[15 WACC y tasa de descuento]] | [Clase 16/10] [Clase 20/10] |

## Fuentes
[Guía ej 25–29, 31, 37, 42, 45, 46, 47, 50, 51] · [Clase 25/09] · [Clase 16/10] · [Clase 20/10] · [Clase 23/10] · [Consulta 02/10] · [Resumen amigo: Préstamos] · [Planilla amigo: 27, 31, Bielsa, Toldo, 42, 47, 50]
