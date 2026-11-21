---
tags: [sdg, inversiones, venta-activos]
aliases: [Valor libro, Valor residual, Valor de rezago, Valor de salvamento, Venta de activo]
---

# 10 · Venta de activos y valor residual

← [[09 Inversión inicial y depreciación]] · siguiente → [[11 Reinversión y desinversión]]

## 1. Sinónimos (para el parcial son lo mismo)

**Valor residual = valor de rezago = valor de reventa = valor de salvamento (salvataje) = valor de venta** al final. [Clase 20/10]

El que **no** es sinónimo es el **valor libro (VL)**:

$$VL = \text{Valor de origen} - \text{Depreciación acumulada}$$

## 2. Mecánica de la venta en el flujo (3 líneas)

| Línea | Fila | Signo |
|---|---|---|
| Precio de venta (sin IVA) | **IAI** | + |
| Valor libro del activo vendido | **GND** | − |
| Ajuste del valor libro | **Ajustes GND** | + |

- Se paga IIGG solo por la **diferencia** venta − VL. Si VL > venta, hay pérdida → **ahorro** de impuesto.
- El VL se **resta** para calcular el impuesto y se **vuelve a sumar** porque no es salida de caja. [Consulta 02/10]

> *"Cuando vendés cualquier bien tenés que pagar IIGG por la diferencia entre tu valor de venta y el valor libro. Restás tu valor libro, sumás tu valor de venta, y después volvés a compensar el valor libro porque en realidad no hubo un costo."* [Consulta 02/10]

> [!important] Ojo: lo que se resta como GND y se ajusta es el **valor libro**, no el precio residual
> - El **precio residual** (lo que cobrás) va **solo como IAI**.
> - El **VL** (origen − depreciación acumulada) va como **GND (−)** y como **ajuste (+)**.
> - Solo coinciden si el activo se vende por su VL. Si se deprecia el 100% (residual contable 0), el VL al final de la vida útil es 0 y no hay GND de baja; si se vende antes de depreciarlo todo, el VL es mayor que el residual.
> - Ejemplo Estrella (ej 47), servidor nuevo: origen \$2.000.000, depreciado 3 años a \$400.000 → VL \$800.000 (GND y ajuste) y venta al 10% = \$200.000 (IAI). Se paga impuesto por 200.000 − 800.000 = −600.000 (ahorro).

### Ejemplos de la guía

| Ej | Activo | Venta | VL | Efecto |
|---|---|---:|---:|---|
| 14 | VO 120.000 a 3 años, vendido en año 2 | 70.000 | 40.000 | Gana 30.000 → paga IIGG |
| 18A | Máquina \$25M a 6 años, vendida en año 5 | 2.500.000 | 4.166.667 | Pierde → ahorro de IIGG |
| 18B | Máquinas 2 y 3 a 3 años, compradas en año 3, vendidas en año 5 | 3.000.000 c/u | 3.333.333 c/u | Pierde → ahorro |
| 19 | Equipos \$80M a 10 años, vendidos en año 5 | 52.500.000 | 40.000.000 | Gana → paga |

## 3. ¿Sobre qué base se calcula el valor de venta?

> [!important] Sobre el valor de origen del activo (sin instalación)
> *"Cuando te dice el valor de origen del activo, es el activo sin la instalación… el mercado te dice que vale el 50% del valor de origen del activo, del activo solito."* Si alguien lo toma con instalación, *"no le ponemos mal"*. [Clase 20/10]
> El **VL** sí incluye la instalación (porque se depreció).

Ejemplo [Resumen amigo]: compra 10.000.000 + inst. 1.000.000 + transp. 500.000; se vende en el **20% del precio de compra** → venta = **2.000.000** (no 2.300.000).

## 4. Si el enunciado da el valor de venta en OTRO año

### a) Te dan el valor en el año 10 y el proyecto termina en el 5 → interpolar

Método de la guía (ej 19): **promedio simple** entre el valor de compra y el valor de venta del año 10.

$$\text{Venta}_{año\,5} = \frac{VO + \text{Venta}_{año\,10}}{2} = \frac{80M + 25M}{2} = 52{,}5M$$

> [!warning] Control de cordura
> El valor del año 5 **no puede ser menor** que el del año 10. *"Si podías sacar más guita, ¿cómo en el año 5 vas a sacar menos guita que en el 10?"* Sirve cualquier método razonable (promedio, lineal), pero no traigas el valor del año 10 a valor presente. [Clase 20/10]

### b) Te dan el valor para el "5to año de **vida**" y el activo se compró a mitad del proyecto → regla de tres lineal

Ej 46 Bielsa, **segundo telar**: VO \$1.200.000, "valor de reventa = 30% del valor de compra para su 5to año de vida". Se compra a comienzo del año 4 (columna 3) → al final del año 5 tiene **2 años de vida**. [Clase 25/09]

| Paso | Cálculo | Resultado |
|---|---|---:|
| Valor a los 5 años | 30% × 1.200.000 | 360.000 |
| Pérdida total en 5 años | 1.200.000 − 360.000 | 840.000 |
| Pérdida por año | 840.000 / 5 | 168.000 |
| **Valor de venta con 2 años de vida** | 1.200.000 − 2 × 168.000 | **864.000** → IAI año 5 |
| VL con 2 años (VO + 10% inst. = 1.320.000, 264.000/año) | 1.320.000 − 2 × 264.000 | **792.000** → GND año 5 |

> *"Lo del quinto año es una trampita medio común: te dan un valor de un año y tenés que trasladarlo a otro."* [Consulta 02/10]
> *"En el fondo hagan la regla de tres simple, no nos vamos a complicar."* [Clase 25/09]

## 5. Si NO te dicen que se vende → venta = 0

*"Si el formulador no te dice que se vendió, va al valor de venta cero: no te lo compra nadie."* Igual se da de baja por su **valor libro** (GND + ajuste). [Clase 20/10]

Ej: software desarrollado para el proyecto → reventa 0, salvo que te den un valor. Ej 30 (guía): la reinversión no se vende y su VL de \$12.000 va como GND en el año 5 (escudo fiscal).

## 6. Terreno

- No deprecia → **VL = valor de compra**.
- Al final se "vende" al valor de salvamento que te den (Flamingo: \$15.000) o, en el ej 51, en \$50M (comprado a \$300M). [Clase 16/10] [Consulta 02/10]

| Flamingo, año 3 | Fila | Importe |
|---|---|---:|
| Venta del terreno | IAI | +15.000 |
| VL del terreno | GND | −15.000 |
| Ajuste VL | Ajustes | +15.000 |

*"Aparece tres veces en la columna: el valor libro, el valor de venta y el ajuste."* [Consulta 02/10]

> [!tip] ¿Por qué se simula la venta de todo al final?
> *"Tengo que hacer de cuenta que termino con todos los activos, como si la empresa se cerrase."* Si no, un proyecto de comprar un departamento nunca sería rentable. [Clase 16/10]

## 7. Desinstalación ligada al valor de rezago (ej 46 Bielsa)

> "Los costos de desinstalación en el último año, para todo el activo, se estiman en el 5% del valor de rezago."

Como **valor de rezago = valor de venta**:
- Telar 1: 5% × 300.000 = **15.000** (es lo que pone la resolución de la cátedra). [Consulta 02/10, consulta corta]
- Telar 2: 5% × 864.000 = 43.200.
- → **EAI en el año 5**.

> [!warning] ⚠️ Consultar: rezago = ¿valor libro o valor de venta?
> En la [Planilla amigo] la desinstalación del telar 1 da **0**, porque tomaron rezago = VL (y el telar ya estaba depreciado del todo). La resolución oficial da 15.000 = 5% del **valor de venta**. El ayudante dijo *"es un gris, llevale esto a Jorge"*. En [Clase 20/10] Jorge confirmó que rezago y reventa **son sinónimos**, así que manda el valor de venta.

## Fuentes
[Guía ej 14, 18, 19, 30, 34, 46] · [Clase 16/10] · [Clase 20/10] · [Clase 25/09] · [Consulta 02/10 (Flamingo, Bielsa)] · [Resumen amigo: Valor residual] · [Planilla amigo: EJ 2A/2B, 19, Bielsa, Flamingo]
