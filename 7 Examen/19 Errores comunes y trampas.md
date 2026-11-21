---
tags: [sdg, examen, trampas]
aliases: [Trampas, Errores comunes]
---

# 19 · Errores comunes y trampas

← [[18 Método paso a paso para el parcial]] · siguiente → [[20 Ejercicio integrador - Flamingo resuelto]]

## Trampas de enunciado (las que Jorge pone a propósito)

| Trampa | Cómo detectarla | Qué hacer | Nota |
|---|---|---|---|
| **IVA incluido** | "con IVA", "IVA incluido", "+ IVA" | ÷ 1,21 (o 1,105) y nunca lo pongas en el flujo | [[05 Ventas, IIBB e IVA]] |
| **"Tasa anual del X% capitalizable…"** | "capitalizable", "puntos nominales" | Es TNA → pasar a TEA | [[03 Tasas de interés]] |
| **"A comienzo del año N"** | "a principios", "al comienzo" | Columna **N − 1** | [[01 Proyecto y flujo incremental]] |
| **Costo hundido** | "ya se pagó", "fue abonado al inicio del estudio", "estudio de perfil" | Afuera | [[01 Proyecto y flujo incremental]] |
| **Empleados que ya trabajan** | "se asignan al proyecto 2 empleados que trabajan actualmente" | No van al flujo (sí al markup) | [[08 Sueldos, indemnizaciones y ahorros]] |
| **Deuda nueva en el Kd** | El préstamo del proyecto aparece en la lista de deudas (ej 50, con *) | Afuera del Kd | [[15 WACC y tasa de descuento]] |
| **Proveedores en el balance** | Balance con "Proveedores" | Afuera del Kd y de Xd | [[15 WACC y tasa de descuento]] |
| **Valor de venta de otro año** | "VR en el año 10", "para su 5to año de vida" | Interpolar / regla de tres | [[10 Venta de activos y valor residual]] |
| **Valor de venta sobre el VO** | "30% del valor de compra" | Sin instalación | [[10 Venta de activos y valor residual]] |
| **Calendario de pagos** | Tabla "monto / se abona (año)" | Usar la columna del pago | [[09 Inversión inicial y depreciación]] |
| **Activo que no es del proyecto** | "como beneficio por los años trabajados" (camioneta del ej 51) | Afuera | [[01 Proyecto y flujo incremental]] |
| **CS incluidas** | "(incluido en los montos)" | No multiplicar por (1 + CS) | [[08 Sueldos, indemnizaciones y ahorros]] |
| **"No remunerativo"** | Comisión o premio "no remunerativo" | Sin CS | [[08 Sueldos, indemnizaciones y ahorros]] |
| **Monotributista** | "consultor", "monotributista", "honorarios" | × 12, sin SAC, sin CS, sin indemnización | [[08 Sueldos, indemnizaciones y ahorros]] |
| **"Valor residual" que en realidad es VL** | Activo viejo con "su valor residual es…" | Tomalo como VL al inicio | [[09 Inversión inicial y depreciación]] |
| **Inflación** | "Se espera una inflación del 40%" | Ignorarla (*"ni bola"*; *"es bait"*) | [Clase 23/10], [Planilla amigo, 47] |
| **Datos de relleno** | Vencimiento del producto, costos de almacenamiento "despreciables" | Ver si limitan algo; si no, ignorar | [[06 Costos, producción y stock]] |
| **"Inversión" en marketing / RRHH** | "inversión en marketing del X% de la venta" | EAI, no se deprecia | [[09 Inversión inicial y depreciación]] |
| **Licencia periódica** | "licencia anual" | EAI, no se deprecia | [[09 Inversión inicial y depreciación]] |
| **Gracia** | "años de gracia", "comenzando en el año 4" | Interés sí, capital no; n = restantes | [[14 Préstamos - francés, alemán, americano y gracia]] |
| **Quebranto** | "la empresa proyecta pérdidas / quebranto" | IIGG = 0 y trasladar | [[17 Quebranto impositivo]] |

> Trampas de un ejercicio completo: [[Estrella (ej 47) - trampas del ejercicio]].

## Errores de mecánica

| Error | Correcto |
|---|---|
| Poner la cuota entera como egreso | Interés (EAI) + capital (ENAI) |
| Restar el préstamo de la inversión | Inversión total (ENAI) + préstamo (INAI) |
| Costos variables sobre lo producido en el FF | Sobre lo **vendido** (lo producido va al WC) |
| Desperdicio × (1 + d) | ÷ (1 − d) |
| Restar el valor residual antes de depreciar | Depreciar el 100%, vender aparte |
| Sumar instalación al % de venta del activo | El % va sobre el VO del activo solo |
| Vender lo desinvertido sin que lo digan | Solo VL como GND |
| Depreciar el terreno | No deprecia; VL = costo |
| WC del año *t* en el año *t* | En el año **t − 1** |
| Recuperar solo el WC inicial | Recuperar el **acumulado** |
| Meter préstamo, ventas de activos o ahorros en el WC | Afuera |
| WC con el primer mes positivo | Mirar los 12 meses, tomar el máximo déficit |
| Calcular IIGG en el año de quebranto | IIGG = 0 y trasladar la UAI |
| Trasladar la UN en el quebranto | Trasladar la **UAI** |
| Olvidar el ajuste de algún GND | Revertir **todos** |
| Descontar el año 0 | El año 0 va sin descontar |
| Valor de venta del año 5 menor que el del año 10 | Interpolar sin descontar |
| Kd promedio simple | Kd **ponderado** por monto |
| Margen = costo × (1 + %) | Margen: C / (1 − m). Markup: C × (1 + m) |
| Regalía restada para llegar a la venta neta | Es EAI aparte |

## Fuentes
Todas las notas · [Clase 16/10] · [Clase 20/10] · [Clase 23/10] · [Resumen amigo: errores comunes]
