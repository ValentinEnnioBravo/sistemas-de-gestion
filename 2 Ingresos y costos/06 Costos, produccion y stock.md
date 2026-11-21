---
tags: [sdg, costos]
aliases: [Costo variable, Costo fijo, Costo directo, Costo indirecto, Desperdicio, Obsolescencia, CMV]
---

# 06 · Costos, producción y stock

← [[05 Ventas, IIBB e IVA]] · siguiente → [[07 Precio - markup, margen, equilibrio y elasticidad]]

## 1. Dos clasificaciones que se cruzan

| | **Directo** (se apropia al producto) | **Indirecto** |
|---|---|---|
| **Variable** (depende de Q) | Materia prima, MOD, gastos fabriles variables | — |
| **Fijo** (se paga aunque Q = 0) | — | Mano de obra indirecta (mantenimiento, gerente de planta), alquiler, seguros, depreciación de planta |

- **Costo del producto** = MP + MOD + gastos fabriles (directos e indirectos de **planta**). [Clase 16/10]
- **Fuera del costo del producto** (gastos del período): **sales & marketing** (comisiones, sueldos de vendedores, publicidad, logística por supuesto), **G&A** (administración, gerente general) y **financieros** (intereses). [Clase 16/10] [Clase 20/10]
- Para decidir si alguien es directo o indirecto: *"¿tiene incumbencia sobre la fabricación del producto?"*. El supervisor de la línea suele ser directo; el gerente de planta o de mantenimiento, indirecto. [Clase 16/10]

> [!note] Clasificación por naturaleza del gasto
> Todo egreso va a una de tres bolsas del estado de resultados: **productivo**, **G&A** o **S&M**. Las tres son **EAI** en el flujo; la clasificación solo importa para el **costo del producto / markup**. [Clase 20/10]

## 2. En el flujo: costos sobre lo **vendido**

> [!important] Vendido para el FF, producido para el WC
> - **Flujo de fondos**: costo variable × **unidades vendidas** (es el costo de la mercadería vendida, CMV).
> - **Working Capital**: costo variable × **unidades producidas**.
> - **Costos fijos**: se pagan igual, produzcas lo que produzcas.
>
> [Clase 25/09] [Clase 16/10] [Clase 20/10] [Consulta 02/10]

**¿Por qué?** (criterio de lo **devengado**, Gonzalo en [Consulta 02/10]): cuando fabricás, contablemente **no hay pérdida**. Baja la caja y sube la cuenta *mercaderías* (es un intercambio dentro del activo). El costo pasa a resultados **recién cuando vendés** (CMV). La plata inmovilizada en stock es un tema **financiero**, y eso lo captura el **Working Capital**. Al final del proyecto, el **recupero del WC** devuelve también el inventario que quedó. [Clase 25/09]

## 3. Desperdicio (scrap)

Si un insumo tiene un **desperdicio d**, para que te queden *q* unidades útiles tenés que comprar:

$$q_{comprada} = \frac{q_{necesaria}}{1 - d}$$

> [!warning] No es q × (1 + d)
> Multiplicar por 1,01 en vez de dividir por 0,99 está mal, aunque *"no es un error grave"* porque la diferencia son decimales. **Lo correcto es dividir por (1 − d).** [Clase 20/10]

Ejemplo (ej 50, PVC con 20% de desperdicio): 5.000 g necesarios → 5.000 / 0,8 = **6.250 g comprados** (no 6.000 g).

El desperdicio **es costo del producto** (va en el costo variable unitario).

## 4. Política de stock de materia prima ≠ desperdicio

Ej 49: *"la empresa tiene como política de stock adquirir un 12% adicional de la materia prima"*.
- **No** es desperdicio y **no** va al costo del producto.
- Es **inventario** (un amortiguador) → va al **Working Capital**. [Clase 16/10] [Clase 20/10]

## 5. Obsolescencia (productos perecederos)

- Si producís de más y el producto **se vence**, lo tirás: es un **costo de obsolescencia** valuado **a costo** (no a precio de venta). Es una pérdida, o sea **EAI**. [Clase 16/10]
- *"Si sabés que lo vas a tirar, ¿para qué producís tanto?"* La respuesta esperada es **producir de forma de no tirar nada**. [Clase 16/10] [Clase 20/10]
- Algunas industrias retiran el producto antes de que venza (ej.: farmacia, 6 meses antes). Si el enunciado lo dice, achicá la vida útil comercial.

> [!tip] Para el parcial
> En ejercicios como Polo (vence a 24 meses) o la pipeta (18 meses), el dato sirve para **limitar cuánto podés stockear**. Si planificás que nada quede en stock más del vencimiento, *"era de relleno"*. [Clase 20/10]

## 6. Transporte / logística

Hay empresas que lo ponen como costo del producto y otras como S&M. Si el enunciado no dice nada, escribí un supuesto (*"supongo que el transporte es S&M"* está bien). [Clase 16/10]

## 7. Costos dados por unidad

Si te dan "MOD \$100 por unidad", ese costo **ya incluye todo**: **no le sumes cargas sociales** (puede ser alguien que cobra por hora). [Consulta 02/10, Toldo]

## 8. Economía de escala: más ventas, menor costo fijo unitario

El **costo fijo total** no depende de las unidades (se paga igual); por eso, al aumentar las unidades, el **costo fijo por unidad baja**. Es la economía de escala.

$$CF_u = \frac{CF_{total}}{Q} \qquad CT_u = CV_u + \frac{CF_{total}}{Q}$$

- El **CV unitario** se mantiene (cada unidad cuesta lo mismo de producir o vender).
- El **CF unitario** baja a medida que crece Q, así que el **costo total unitario** también baja y **el margen por unidad sube**.
- Con el **mismo precio**, a mayor escala hay más utilidad por unidad. Es lo que explica que un proyecto con pocas ventas al principio sea menos rentable que en los años de más demanda.

> [!example] Estrella (ej 47): fijos \$2.400.000 al año (\$200.000 por mes) · CV \$300 por venta · precio neto \$1.000
> | Año | Unidades | CF unitario | CT unitario | Margen por unidad |
> |---|---:|---:|---:|---:|
> | 1 | 15.000 | 160 | 460 | 540 |
> | 2 | 20.000 | 120 | 420 | 580 |
> | 3 | 25.000 | 96 | 396 | 604 |
> | 4 y 5 | 30.000 | 80 | 380 | 620 |
>
> El margen de contribución (\$1.000 − \$300 = \$700) es constante. Lo que mejora es cuánto de ese margen se come el costo fijo por unidad.

> [!warning] Dónde importa y dónde no
> - **En el flujo de fondos**: el CF va por su **monto total** de cada año (mensual × 12). No lo dividas ni lo escales.
> - **Precio / markup / equilibrio**: acá sí se usa el CF por unidad, dividido por las unidades **producidas** (ver [[07 Precio - markup, margen, equilibrio y elasticidad]]).
> - **WC por regla de tres**: escala todo por unidades, aunque los fijos no escalen. Es una simplificación de la cátedra (*"vamos con la tablita lineal siempre"*, ver [[13 Capital de trabajo (Working Capital)]]).

> [!note] Límite de la escala
> Los fijos son fijos solo dentro de un rango de capacidad. Si la demanda supera la capacidad instalada hay que invertir en otra máquina y el fijo da un salto (ver [[12 Capacidad - cuándo comprar la máquina o stockear]]).

(Sección agregada a pedido; el ejemplo es un cálculo propio con los datos del enunciado, no sale de una clase.)

## Fuentes
[Clase 16/10] · [Clase 20/10] · [Clase 25/09] · [Consulta 02/10] · [Guía ej 43, 45, 48, 49, 50] · [Planilla amigo: Bielsa ("cuando produzco más de lo que vendo…"), Toldo v2, 50] · [Guía ej 47: datos del ejemplo de escala]
