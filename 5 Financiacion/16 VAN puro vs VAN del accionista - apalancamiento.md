---
tags: [sdg, financiacion, apalancamiento]
aliases: [VAN puro, VAN del accionista, Apalancamiento financiero, Escudo fiscal]
---

# 16 · VAN puro vs VAN del accionista: apalancamiento

← [[15 WACC y tasa de descuento]] · siguiente → [[17 Quebranto impositivo]]

## 1. Los dos flujos

| | **Flujo puro** | **Flujo del accionista** |
|---|---|---|
| Inversión | **Total** | **Total** (igual) |
| Préstamo recibido | — | **INAI** año 0 |
| Intereses | — | **EAI** (bajan el IIGG) |
| Amortización de capital | — | **ENAI** |
| Tasa | WACC | **WACC** (criterio de la cátedra) |
| Responde | ¿El **proyecto** agrega valor? | ¿El **préstamo** le conviene al accionista? |

*"Lo único que cambia entre el VAN del accionista y el puro es meterle los flujos del préstamo: el monto, la amortización de capital y el interés."* [Clase 25/09]

> [!warning] Error clásico: restar el préstamo de la inversión
> La inversión va **siempre por el total** (por ejemplo −1.100.000), y el préstamo va aparte como INAI (+770.000). No pongas "inversión −330.000". La plata que pone el accionista de su bolsillo **es el flujo neto del año 0**. *"Es un error que se solía dar mucho antes."* [Clase 25/09]

### ¿Por qué se evalúa primero el flujo puro?
*"Si yo consigo una tasa mucho más baja, capaz el VAN da positivo solamente porque tengo el préstamo, y el proyecto solo no lo paga. Entonces más que una decisión de inversión es una decisión de financiamiento."* [Clase 16/10]

## 2. Apalancamiento financiero

$$\Delta VAN = VAN_{accionista} - VAN_{puro}$$

| ΔVAN | Interpretación |
|---|---|
| > 0 | **Hay apalancamiento**: el préstamo suma valor |
| < 0 | No hay: mejor con capital propio |
| = 0 | Indiferente |

### Regla rápida con tasas
- **Tasa efectiva del préstamo < WACC** → apalanca seguro. [Guía ej 28] [Clase 25/09]
- **Tasa del préstamo = WACC** → igual gana, por el **escudo fiscal** de los intereses. [Guía ej 29]
- **Tasa del préstamo > WACC** → en general no apalanca, **pero puede pasar que sí** si el escudo fiscal pesa (interés alto, IIGG alto). [Clase 20/10]

> *"Si yo me estoy tomando una deuda con una tasa menor al WACC se me está haciendo apalancamiento, no tengo duda. Pero puede darse en algunas condiciones que, siendo mayor, igualmente el VAN me da mayor."* [Clase 20/10]

> [!tip] Contra qué tasa comparás
> Contra la tasa del **préstamo del proyecto** (no contra el Kd promedio). Si el proyecto tiene **dos préstamos**, usá su **promedio ponderado**. [Clase 23/10]

> [!example] Bielsa en clase [Clase 25/09]
> Con el préstamo al **79,59%** (WACC ≈ 35%), el VAN puro le gana al del accionista: no apalanca. Jorge bajó la tasa al **20%** (< WACC) y el VAN del accionista pasó a ser mayor: **apalanca**. El WACC con el que se descuenta **no cambió**.

## 3. Cuándo no se consigue financiación barata (ej 28)
Con **riesgo crediticio** alto, o si ya hay mucha más deuda que capital propio, el préstamo sale caro y se pierde el apalancamiento. [Guía ej 28]

## 4. Para el parcial
- Si el enunciado tiene deuda para el proyecto, **entregás el flujo del accionista**. [Clase 16/10] [Clase 23/10]
- Preguntas típicas: *"Detalle el VAN puro y el VAN del accionista. Explique por qué se da la variación"* (ej 48, 49) y *"¿Tiene apalancamiento financiero?"* (ej 37, 41, 46, 47, 50).
- Respuesta modelo: comparar los VAN, explicar la diferencia por la **tasa del préstamo vs el WACC** y por el **escudo fiscal** de los intereses.

> [!warning] ⚠️ Polo (ej 48)
> En la [Planilla amigo] el VAN del accionista da mayor que el puro aunque la TEA del préstamo (19,4%) es mayor que el WACC (17,3%). Jorge dijo que puede pasar por el escudo fiscal [Clase 20/10], pero **esa hoja tiene errores** y no sirve para comprobarlo:
> - la UAI del año 1 (597M) es **mayor que la venta neta** (237M): los costos parecen **sumados** en vez de restados;
> - en el flujo del accionista, la utilidad neta es igual a la UAI (no se restó el impuesto).
>
> Rehacelo antes de sacar conclusiones.

## Fuentes
[Guía ej 28, 29, 37, 41, 46, 47, 48, 49, 50] · [Clase 25/09] · [Clase 16/10] · [Clase 20/10] · [Clase 23/10] · [Resumen amigo: Apalancamiento] · [Planilla amigo: 48 Polo]
