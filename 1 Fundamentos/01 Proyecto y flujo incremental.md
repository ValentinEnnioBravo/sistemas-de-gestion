---
tags: [sdg, fundamentos]
aliases: [Incremental, Costo hundido, Costo de oportunidad]
---

# 01 · Proyecto y flujo incremental

← [[00 Índice]] · siguiente → [[02 Estructura del flujo de fondos]]

## 1. ¿Qué estamos haciendo?

Un ejercicio de flujo de fondos **evalúa un proyecto de inversión**: decide si conviene hacerlo desde lo **financiero** (¿genera caja?) y desde el **impacto económico** (¿agrega valor?). [Clase 16/10]

El resultado es una serie de flujos de caja por año (**año 0, 1, …, n**). Esos flujos se descuentan con una tasa y dan el **VAN** (ver [[04 VAN, TIR y Payback]]).

> [!important] Regla de oro: solo lo incremental
> En el flujo entra **únicamente lo que aparece, desaparece o cambia por hacer el proyecto**.
> La pregunta para cada dato: **«¿Este ingreso o gasto existiría igual si NO hacemos el proyecto?»**
> - Si existiría igual y no se sacrifica nada → **no va**.
> - Si aparece, desaparece o cambia → **va** (como ingreso, egreso o ahorro).
>
> *"Siempre tengo que manejarme por datos incrementales. Eso es grabándoselo a fuego."* [Clase 20/10]

## 2. Tres conceptos que deciden si un dato entra o no

| Concepto | Definición | ¿Va al flujo? | Ejemplos de la guía |
|---|---|---|---|
| **Costo hundido** | Ya se gastó, pasó lo que pasó con la decisión | ❌ No | Estudio de mercado ya pagado (ej 48: \$2M; ej 50: \$20M del CONICET; ej 51: investigación de \$700.000 "abonada al inicio del estudio") |
| **Costo de oportunidad** | Lo que se deja de ganar por usar un recurso propio en el proyecto | ✅ Sí, como **EAI** | Espacio propio que se podría alquilar (ej 46: \$10.000/mes; ej 48: depósito \$550.000/mes) |
| **Costo incremental** | Aparece o cambia por el proyecto | ✅ Sí | Sueldos nuevos, máquina nueva, ahorros por despidos |

### Costo de oportunidad: ¿por qué entra si no es una salida real?

Para la **evaluación** se pone igual: si mañana *"la tía"* que te prestaba el lugar te lo pide, tenés que salir a alquilar. Jorge lo justifica con el **criterio de prudencia** contable. [Clase 16/10]

> [!warning] ⚠️ Consultar: costo de oportunidad en el Working Capital
> En el **flujo de fondos** el costo de oportunidad **va siempre**. En el **WC** el criterio fue cambiando:
> - [Clase 16/10]: *"Sí, entra independientemente de cualquier cosa"*.
> - [Clase 20/10] y [Clase 23/10]: **no** entra, porque *"no voy a necesitar plata para pagar eso"*. Lo aclara como **discutible**.
>
> **Criterio a usar (el último): NO va al WC.** La resolución de Bielsa de la cátedra lo incluye, pero Jorge dijo que no la va a defender. Ver [[13 Capital de trabajo (Working Capital)]].

## 3. Recursos que la empresa ya tiene

| Situación | Tratamiento | Fuente |
|---|---|---|
| Empleado que **ya trabaja** y sigue cobrando lo mismo | ❌ No va al flujo (*"es trampa"*) | Ej 47 (2 empleados de soporte), [Planilla amigo] |
| Ese mismo empleado, para calcular el **costo del producto / markup** | ✅ Sí se incluye su costo | [Clase 23/10] → ver [[07 Precio - markup, margen, equilibrio y elasticidad]] |
| Activo viejo que **se trae** al proyecto (estantería, estibador, mobiliario) | Se incluye su **depreciación pendiente** como GND (y su ajuste) | [Clase 20/10], ej 45, 50, 51 → [[09 Inversión inicial y depreciación]] |
| Activo de la empresa que **no es del proyecto** (camioneta regalada a un exgerente, ej 51) | ❌ No va | [Clase 20/10], [Clase 23/10] |
| Espacio propio sin uso | Costo de oportunidad → **EAI** | Ej 46, 48 |

## 4. Año 0, años del proyecto y horizonte

- **Año 0** = el momento de arranque: inversiones iniciales, WC inicial, préstamo recibido, indemnizaciones del inicio.
- **"A comienzo del año N"** = **final del año N−1** → se pone en la **columna N−1**.
  - Ej 30: "en el año 4 (comienzo) se prevé una reinversión" → columna **año 3** (así lo resuelve la guía).
  - Ej 36: "reinversión para principios del año 3" → columna **año 2** [Planilla amigo].
- **Horizonte** = años que se evalúan (lo pide "el directorio"). **No coincide necesariamente con la vida útil** de los activos.
- **Todo lo que empieza en el proyecto termina en el proyecto**: los activos se venden (o se dan de baja por su valor libro) y los préstamos se cancelan en el último año. [Clase 23/10]

> [!tip] Devengado: no partas la venta entre años
> La venta de diciembre se cobra en enero del año siguiente, pero en el **flujo de fondos** va toda en el mismo año. Esos días de desfasaje se compensan entre años y, al final, *"son 60 [días] que van al año 6, que está fuera del proyecto"*. El desfasaje de cobros y pagos se trata **solo** en el [[13 Capital de trabajo (Working Capital)|Working Capital]]. [Clase 16/10]

## 5. Supuestos

Se pueden escribir supuestos cuando el enunciado no dice algo, pero:
- **No inventes un dato que se puede calcular.** *"No me pongan 'supongo que la tasa es 25% porque lo dijo el CFO'… te di un montón de datos para que lo calcules con el WACC"*. [Clase 16/10]
- **No supongas situaciones fuera del proyecto** (*"el monotributista me va a hacer juicio…"*). Se evalúa con lo que dice el enunciado.
- Un supuesto razonable y escrito puede salvar puntos si la interpretación es lógica.

## Fuentes
[Clase 16/10] · [Clase 20/10] · [Clase 23/10] · [Guía ej 30, 36, 46, 47, 48, 50, 51] · [Resumen amigo] (Glosario y regla de oro)
