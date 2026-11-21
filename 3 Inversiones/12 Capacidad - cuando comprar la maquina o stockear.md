---
tags: [sdg, inversiones, capacidad, stock]
aliases: [Capacidad, Stock, Stockear, Producción vs demanda]
---

# 12 · Capacidad: ¿comprar la máquina o stockear?

← [[11 Reinversión y desinversión]] · siguiente → [[13 Capital de trabajo (Working Capital)]]

Aparece en Bielsa (46), Toldo (45), Polo (48), pipeta (43), yogur (44), pozo (38) y ODF (49): **la demanda de algún año supera la capacidad** de la máquina.

## 1. Las opciones

| Opción | Qué hacés | Cuándo |
|---|---|---|
| **A · Estándar** | Producís **= demanda** y comprás la 2ª máquina **a comienzo del año** en que hace falta | Caso por defecto: *"el caso frecuente es que yo no estoqueo, sino que produzco todo lo que voy a vender"* [Clase 25/09] |
| **B · Stock** | Producís de más en los años con capacidad ociosa y usás ese stock en los años de pico. Comprás la máquina **más tarde** o nunca | Si el producto **no es perecedero** (o vence después de cuando lo vendés) |
| **C · Todo al inicio** | Comprás toda la capacidad en el año 0 | **Subóptimo**. Es el único que *"te podría haber bajado un punto"* [Clase 25/09] |
| **D · No atender** el exceso | Perdés esas ventas | Válido si lo justificás y el enunciado no prohíbe dejar demanda sin atender [Clase 25/09] |

> [!important] Para el parcial
> - **A y B están bien** si justificás. *"Si invertías en la máquina, bárbaro; si no invertías y justificabas… estaba bien también, los dos."* [Clase 25/09]
> - Para simplificar: **producción = venta** (*"le pego de punta para arriba"*). [Clase 23/10]
> - Primero probá si te alcanza sin la segunda máquina con: **Stock final = Stock inicial + Producción − Venta**. [Clase 23/10]

## 2. Si stockeás: ¿cuándo producís el extra? → lo más tarde posible

*"La lógica siempre es: cuanto más adelante puedas patear los costos, maximizás el VAN por la tasa de descuento."* [Consulta 02/10]

### Toldo (ej 45): capacidad 200.000

| | Año 1 | Año 2 | Año 3 | Año 4 | Año 5 |
|---|---:|---:|---:|---:|---:|
| Demanda | 120.000 | 120.000 | **300.000** | 125.000 | 50.000 |
| Producción (patear lo más tarde) | **140.000** | **200.000** | 200.000 | 125.000 | 50.000 |
| Stock acumulado | 20.000 | 100.000 | 0 | 0 | 0 |

Faltan 100.000 para el año 3. El año 2 aporta lo máximo (80.000) y el año 1 solo lo que falta (20.000). Es mejor que 170/170. [Consulta 02/10] [Planilla amigo, Toldo v2]

### Bielsa (ej 46): capacidad 100.000 con un telar

| | Año 1 | Año 2 | Año 3 | Año 4 | Año 5 |
|---|---:|---:|---:|---:|---:|
| Demanda | 90.000 | 80.000 | 100.000 | 120.000 | 130.000 |
| **A · Estándar**: 2º telar a comienzo del año 4 (columna 3) | 90.000 | 80.000 | 100.000 | 120.000 | 130.000 |
| **B · Stock**: produzco 100.000 siempre | 100.000 | 100.000 | 100.000 | 100.000 | 100 + **20** |
| Stock acumulado (B) | 10.000 | 30.000 | 30.000 | 10.000 | 0 |

En B el stock alcanza hasta el año 4. Para el año 5 faltan 20.000 → el 2º telar se compra **a comienzo del año 5 (columna 4)**. [Clase 25/09] [Planilla amigo, Bielsa v2]

## 3. Qué cambia en cada parte del flujo

| Parte | Con stock |
|---|---|
| **Ventas** | Siempre las unidades **vendidas** |
| **Costos variables en el FF** | Sobre lo **vendido** (CMV) |
| **Costos fijos** | Iguales |
| **Working Capital** | Costo variable sobre lo **producido** → más WC antes. Se recupera al final (el inventario está adentro del WC) |
| **Inversión** | La 2ª máquina se mueve de año (o desaparece) |
| **Depreciación / VL** de la 2ª máquina | Cambia según cuántos años la usás |

→ WC con stock: [[13 Capital de trabajo (Working Capital)]] §5.

## 4. Productos perecederos

Si vence (Polo: 24 meses; pipeta: 18 meses), **no podés stockear más de lo que vendés antes del vencimiento**. Lo que se vence es **obsolescencia** (EAI a costo) y es ineficiente: *"Te puse como gerente de planta para que me hagas el producto lo más barato posible."* [Clase 16/10] [Clase 20/10] → [[06 Costos, producción y stock]] §5.

## 5. Ej 18 de la guía: una máquina grande vs varias chicas

Una grande (1.600.000 u/año, \$25M) contra una chica (900.000 u/año, \$10M) que después se complementa con dos más. **Gana la de las chicas** (VAN −37,2M contra −42,3M): sumar capacidad **cuando crece la demanda** evita mantener *"ese monstruo"* de costo fijo y depreciación desde el principio. [Guía ej 18] [Clase 25/09]

## 6. Bielsista: comparar las dos opciones rápido

Un alumno propuso comparar *(costo del stock × años inmovilizado)* contra *(inversión × años que se posterga)*. Jorge: *"Es excelente… eso sería Bielsa en la vida real."* Se puede argumentar en una línea: *"conviene postergar la máquina porque el valor del dinero en el tiempo de esa inversión es mayor que stockear antes"*. [Clase 20/10]

## 7. Pregunta típica (ej 45.3)
*"¿Qué alternativa daría a la compra de la maquinaria, en relación con la demanda? (producción ociosa vs producción limitada)"*. Discutí capacidad ociosa (máquina grande desde el inicio) contra producción limitada (stockear o perder ventas), con los argumentos de arriba.

## Fuentes
[Clase 25/09] · [Clase 16/10] · [Clase 20/10] · [Clase 23/10] · [Consulta 02/10] · [Guía ej 18, 43, 45, 46, 48] · [Planilla amigo: Bielsa v2, Toldo v2, 48]
