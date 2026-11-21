---
tags: [sdg, inversiones, reinversion, desinversion]
aliases: [Reinversión, Desinversión, Desactivación, Baja de activo]
---

# 11 · Reinversión y desinversión

← [[10 Venta de activos y valor residual]] · siguiente → [[12 Capacidad - cuándo comprar la máquina o stockear]]

Este tema le faltaba al [Resumen amigo]. Junta todo lo anterior: [[09 Inversión inicial y depreciación|depreciación]] + [[10 Venta de activos y valor residual|venta de activos]] + timing ([[01 Proyecto y flujo incremental|"a comienzo del año N"]]).

---

## 1. Reinversión

Una **reinversión** es comprar un activo **durante** el proyecto (no en el año 0): más capacidad, una mejora, reemplazar algo que se termina.

| Aspecto | Tratamiento |
|---|---|
| Fila | **ENAI** en la columna del año en que se invierte |
| Timing | "A comienzo del año N" → **columna N − 1** |
| Depreciación | Empieza el **año siguiente** a la columna de la compra; usa **su** vida útil |
| Valor amortizable | Precio + instalación/transporte (igual que la inversión inicial) |
| Al final del horizonte | Se vende (si te dan valor) o se da de baja por su **VL** (GND + ajuste) |
| Financiación | Si dice "con capital propio", **no** entra en el préstamo (ej 30, 37, 38) |

### ¿Por qué hay reinversiones? (casos de la guía)

| Motivo | Ejercicios |
|---|---|
| **Falta capacidad** (la demanda supera a la máquina) | 38, 43, 44, 46, 48, 49 |
| **Mejora o ampliación** planificada | 30 (20% del VO), 31 (equipo IT), 37 y 38 (mejoras del modelo, \$100.000), 41 (suplementos) |
| **Más licencias** | 36 (10 licencias a comienzo del año 3) |
| **Reemplazo** porque se termina la vida útil | 18B (máquina pequeña de 3 años → dos nuevas) |
| Servidor nuevo | 47 ("para el año 3" → la planilla lo pone en el año 2: *"PARA año 3 es año 2 creo"*) |

> [!tip] ¿Cuándo comprar la máquina de capacidad?
> Lo **más tarde posible**, cuando realmente la necesitás. Una inversión que se patea hacia adelante se descuenta más y mejora el VAN. *"Yo voy a tratar de tirar la compra de la segunda máquina cuando realmente la necesito."* [Clase 25/09] → detalle en [[12 Capacidad - cuándo comprar la máquina o stockear]].

---

## 2. Desinversión

**Desinvertir** = **sacar un activo (o una parte) del proyecto**: se da de baja, deja de depreciarse y **puede o no venderse**.

> [!important] Desactivar ≠ vender
> - **Desactivás y te dan un precio de venta** → la venta es **IAI**, el VL de esa parte es **GND** (+ ajuste).
> - **Desactivás y NO te dicen que se vende** → **no hay ingreso**. Solo va el **VL de esa parte como GND** (+ ajuste): una pérdida que da escudo fiscal.
> - **Si te dicen que se vende al final "con el resto"** → se vende junto con el resto al final.
>
> *"Si el tipo no te dice que lo vendas… ¿por qué carajo tendrías que suponer?"* Ejemplo de Jorge: la fotocopiadora a la que le sacás el alimentador. Si no lo vendiste en el año 3, al final vendés **la máquina completa, con el complemento**. [Clase 20/10]

### Técnica: partir la depreciación

Para no equivocarte, **dividí el activo en dos líneas de depreciación** desde el principio: la parte que se desinvierte y la que sigue. [Clase 16/10] [Consulta 02/10]

| Toldo (ej 45): 10% desinvertido en año 4 | Años 1–4 | Año 5 |
|---|---|---|
| Depreciación 90% | 4.183.884 | 4.183.884 |
| Depreciación 10% | 464.876 | — (ya se desinvirtió) |
| VL del 10% en el año 4 | 4.648.760 − 4 × 464.876 = **2.789.256** (GND año 4) | |

*"Partimos ahí la depreciación para hacer más fácil después la amortización y la venta de los libros."* [Consulta 02/10]

---

## 3. Ejemplo completo de la guía (ej 30): reinversión + desinversión con venta

> Inversión \$100.000 a 5 años lineal. **A comienzo del año 4** se reinvierte el 20% del VO (\$20.000, capital propio). **Ese mismo año** se desinvierte el 50% de la inversión inicial, vendida en **\$20.000**. Ahorro \$30.000/año. IIGG 10%. Tasa 6% (CAPM: 4% + 1 × (6% − 4%), sin deuda).

Timing: "comienzo del año 4" → **columna 3**.

| Concepto | Año 0 | Año 1 | Año 2 | Año 3 | Año 4 | Año 5 |
|---|---:|---:|---:|---:|---:|---:|
| **IAI** Ahorro | | 30.000 | 30.000 | 30.000 | 30.000 | 30.000 |
| **IAI** Venta 50% del equipo | | | | 20.000 | | |
| **GND** Depreciación equipo | | −20.000 | −20.000 | −20.000 | −10.000 | −10.000 |
| **GND** Depreciación reinversión | | | | | −4.000 | −4.000 |
| **GND** VL 50% vendido | | | | −20.000 | | |
| **GND** VL reinversión (no se vende) | | | | | | −12.000 |
| **UAI** | | 10.000 | 10.000 | 10.000 | 16.000 | 4.000 |
| IIGG 10% | | −1.000 | −1.000 | −1.000 | −1.600 | −400 |
| **UN** | | 9.000 | 9.000 | 9.000 | 14.400 | 3.600 |
| Ajuste depreciaciones | | 20.000 | 20.000 | 20.000 | 14.000 | 14.000 |
| Ajuste VL | | | | 20.000 | | 12.000 |
| **ENAI** Compra equipo | −100.000 | | | | | |
| **ENAI** Reinversión | | | | −20.000 | | |
| **Flujo de caja** | **−100.000** | **29.000** | **29.000** | **29.000** | **28.400** | **29.600** |

**VAN (6%) = \$22.132** ✔ (verificado)

Lo que hay que mirar:
1. **VL del 50% vendido** al final del año 3: 50.000 − 3 × 10.000 = **20.000**. Se vende a 20.000 → ganancia 0.
2. Desde el año 4 el equipo deprecia **solo su mitad** (10.000).
3. **Reinversión** de 20.000 en la columna 3 → deprecia 4.000/año desde el año 4. Al final del año 5 lleva 2 años: VL = 20.000 − 8.000 = **12.000**. **No se vende** → GND (escudo fiscal) + ajuste.
4. La mitad que sigue termina de depreciarse justo en el año 5 → VL 0.

---

## 4. Más casos de la guía

### Ej 51 · Mobiliario reutilizado: 50% desinvertido en el año 1, sin precio de venta

Datos: cuotas de \$50.000, VL al inicio \$150.000 → quedan **3 cuotas**. Se parte en dos mitades de \$75.000. [Clase 23/10]

| Concepto | Año 1 | Año 2 | Año 3 |
|---|---:|---:|---:|
| Depreciación mitad que sigue | −25.000 | −25.000 | −25.000 |
| Depreciación mitad desinvertida | −25.000 | | |
| **VL mitad desinvertida (no se vende)** | **−50.000** | | |
| Ajustes (todo lo anterior) | +100.000 | +25.000 | +25.000 |

Control: 25 + 50 + 3 × 25 = **150** ✔ *"Si yo sumo todo esto, ¿cuánto me tiene que dar? 150."*

### Ej 46 Bielsa · 30% desinvertido al final del año 3

Telar: 1.000.000 + 10% instalación = 1.100.000 → 220.000/año, partido en 70% (154.000) y 30% (66.000).
- VL del 30% al final del año 3: 330.000 − 3 × 66.000 = **132.000** → GND año 3 (+ ajuste).
- El 70% sigue depreciándose los 5 años.

> [!warning] ⚠️ Consultar: ¿la desinversión de Bielsa (y la de Toldo) tiene venta?
> La [Planilla amigo] pone un **ingreso por venta** (Bielsa: 330.000 = 30% del VO; Toldo: 4.648.760 = 10% del VO). Pero ningún enunciado da un precio de venta para esa parte, y el criterio de [Clase 20/10] es **"si no te dice que se vende, venta = 0"**: solo va el VL como GND. Usá el criterio de Jorge y, si querés, aclaralo en un supuesto.

### Ej 48 Polo · desinversión que se vende "al final con el resto"

> "La implementación de la reinversión provoca una desinversión equivalente al 10% de la inversión inicial, que se venderá al final con el resto del equipamiento."

- En el año de la reinversión el 10% **deja de depreciarse** (se desactiva).
- **No hay venta en ese año**: se vende en el año 5 junto con el resto. La segunda máquina tiene su propio valor residual (80% en el año 5).

> [!warning] ⚠️ Consultar: VL del 10% desactivado que se vende al final
> No quedó explícito si su VL se da de baja en el año de la desactivación o recién en el año 5 junto con la venta. La planilla dejó la pregunta abierta. Lo coherente con "se venderá al final con el resto" es mostrar su VL **en el año 5** junto con la venta.

### Ej 50 Piletazo · estibador (activo viejo, 20% desinvertido en el año 2)

VO = 200.000 × 10 = 2.000.000; VL al inicio 1.200.000; se parte en 80% / 20% (depreciaciones 160.000 / 40.000). VL del 20% al final del año 2 = 240.000 − 2 × 40.000 = **160.000** → GND.
La planilla además pone una venta de 400.000 en el año 2, que el enunciado no da. Aplica el mismo ⚠️ de arriba.

### Ej 43 / 49 · reinversión que *provoca* una desinversión
Al ampliar con un módulo, se desinvierte el 10% de la inversión inicial. Misma mecánica: partir la depreciación, VL como GND en el año de la reinversión y venta solo si la dan.

---

## 5. ¿Desinvertir baja la capacidad?

En los ejercicios **se sigue produciendo lo mismo**. Jorge lo justifica: puede ser una parte que **no es el cuello de botella** (sacás dos desarrolladores, pero QA sigue siendo el que limita). Y no es "inchequeable": viene la auditoría y te pide ver el activo dado de baja. [Clase 20/10]

## 6. Checklist de reinversión / desinversión

- [ ] ¿Ubiqué la compra en la columna correcta ("comienzo del año N" → N−1)?
- [ ] ¿La depreciación de la reinversión arranca el año siguiente?
- [ ] ¿Partí la depreciación del activo que se desinvierte?
- [ ] ¿Corté la depreciación de la parte desinvertida desde ese año?
- [ ] ¿Puse el **VL** de lo desinvertido como GND + ajuste?
- [ ] ¿Puse **venta solo si el enunciado da un precio**?
- [ ] Al final: ¿vendí o di de baja por VL **todos** los activos (incluida la reinversión)?
- [ ] ¿La reinversión se financia con capital propio o con el préstamo?

## Fuentes
[Guía ej 18, 30, 31, 36, 37, 38, 41, 43, 45, 46, 47, 48, 49, 50, 51] · [Clase 20/10] · [Clase 23/10] · [Clase 25/09] · [Clase 16/10] · [Consulta 02/10] · [Planilla amigo: 30, 31, Bielsa, Toldo v2, 48, 50]
