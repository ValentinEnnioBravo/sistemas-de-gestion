---
tags: [sdg, examen, trampas, estrella, ej47]
aliases: [Trampas Estrella, Trampas ej 47, Marketplace]
---

# Estrella (ej 47) · Trampas del ejercicio

← [[19 Errores comunes y trampas]] · [[00 Índice]]

Marketplace + middleware + sitio para Sellers. Resolución propia con los criterios del apunte (ver [[21 Mapa de ejercicios de la guía]]). Los números de abajo son del modelo con los supuestos indicados en cada fila.

## Datos y ventas

| # | Trampa | Qué hacer | Nota |
|---|---|---|---|
| 1 | **Inflación del 40% anual** | Ignorarla (*"es bait"*). No se ajustan sueldos ni precios | [[19 Errores comunes y trampas]] |
| 2 | **Mercado en \$ y ticket en \$** (dos datos de ventas) | No se ignora ninguno: mercado × % = ventas en \$; ÷ ticket neto = unidades | [[05 Ventas, IIBB e IVA]] |
| 3 | **Ticket "IVA incluido"** (\$1.210) | Precio neto = 1.210 / 1,21 = **\$1.000**. El IVA nunca va al flujo | [[05 Ventas, IIBB e IVA]] |
| 4 | **¿El mercado de \$250M incluye IVA?** | No lo aclara. Se tomó sin IVA (15M / 1.000 = 15.000 un., coincide con la pregunta 7). Escribir el supuesto | ⚠️ consultar |
| 5 | **Demanda "6% con +2% anual hasta llegar al 12%"** | 6, 8, 10, 12 y 12% (el año 5 se queda en 12%). Mercado constante todo el plazo | |

## Inversión y activos

| # | Trampa | Qué hacer | Nota |
|---|---|---|---|
| 6 | **Esfuerzo en hh "parte de la inversión"** | ENAI en el año 0 por el total y depreciación lineal en 5 años (GND). No son sueldos anuales | [[09 Inversión inicial y depreciación]] |
| 7 | **Cuenta de hh** | hh de **todos** los roles y componentes (2.240 hh) × USD 30 × \$165 = \$11.088.000 | |
| 8 | **2 empleados "que trabajan actualmente"** | Fuera del flujo: cobran lo mismo con o sin proyecto | [[08 Sueldos, indemnizaciones y ahorros]] |
| 9 | **RRHH \$200 por venta** | No es el sueldo de los 2 empleados: es un **costo variable por venta** (junto a Marketing \$100, total \$300) y sí va | [[06 Costos, producción y stock]] |
| 10 | **Servidor comprado hace 3 años** | Su precio es **hundido**. Solo entra la depreciación pendiente (2 cuotas de \$500.000) como GND. Sin costo de oportunidad inventado | [[09 Inversión inicial y depreciación]] |
| 11 | **"Para el año 3" compro el servidor nuevo** | ¿Columna 2 o 3? Se usó la **2** (criterio de la planilla del amigo). Aclararlo | [[11 Reinversión y desinversión]] |
| 12 | **Valor residual del 10% en ambos servers** | Depreciar el 100% y vender aparte en el año 5 (IAI): \$250.000 y \$200.000. El **valor libro** (nuevo: \$800.000; viejo: 0) va en **los dos lados**: GND (−) **y** ajustes de GND (+). El precio residual va solo en IAI | [[10 Venta de activos y valor residual]] |

## Costos y capital de trabajo

| # | Trampa | Qué hacer | Nota |
|---|---|---|---|
| 13 | **Fijos mensuales** | Administración + alquiler = \$200.000 × 12 = \$2.400.000 al año | |
| 14 | **WC "con CF y CV únicamente"** | Dejar afuera depreciación, intereses, ventas de activos y los 2 empleados | [[13 Capital de trabajo (Working Capital)]] |
| 15 | **Plazos del WC** | CV a 30 días, fijos contado; cobranza 40% a 30 y 60% a 60 días, sobre la venta **neta** | |
| 16 | **Déficit acumulado: no mirar solo un mes** | Máximo déficit = **\$275.000** (mes 2). El mes 3 ya da positivo | |
| 17 | **Timing del WC** | El WC del año t se invierte en t − 1. Regla de tres sobre unidades. Recupero total al final: \$550.000 | |

## Financiación y tasa

| # | Trampa | Qué hacer | Nota |
|---|---|---|---|
| 18 | **TNA "capitalizable"** | Pasar a TEA: trimestral m = 4 (74,90%), bimestral m = 6 (47,29%). No usar la nominal ni m = 3 | [[03 Tasas de interés]] |
| 19 | **Dos préstamos, dos sistemas** | Préstamo 1: amortización de capital iguales (alemán, 5 años). Préstamo 2: francés, 3 años. Una tabla por préstamo | [[14 Préstamos - francés, alemán, americano y gracia]] |
| 20 | **Cuota entera** | Interés en EAI y capital en ENAI, nunca la cuota | |
| 21 | **Préstamos de \$5M contra inversión de \$11,09M** | La inversión va por el total en ENAI y el préstamo aparte como INAI en el año 0. No restar | [[16 VAN puro vs VAN del accionista - apalancamiento]] |
| 22 | **Préstamos nuevos en el Kd** | Afuera: el Kd es de la deuda existente. El enunciado no da Kd; se usó **10%** (criterio de Jorge, [[Dudas abiertas para consultar]] #18) | [[15 WACC y tasa de descuento]] |
| 23 | **Ke con riesgo país** | Ke = Rf + β (Rm − Rf) + RP = 1 + 1,2 × 11 + 15 = **29,2%**. La "tasa de mercado" es Rm | |
| 24 | **Deuda/capital "en partes iguales"** | Es Xe = Xd = 50% para el WACC (17,85%) | |
| 25 | **Año 0** | No se descuenta | [[04 VAN, TIR y Payback]] |

## Preguntas finales

| # | Trampa | Qué hacer |
|---|---|---|
| 26 | **¿Apalanca?** | Comparar VAN accionista vs VAN puro. Los préstamos cuestan 74,9% y 47,3% contra un WACC de 17,85%: **no apalanca** |
| 27 | **Payback** | Acumulado: 2 años (el primero en que deja de ser negativo) |
| 28 | **Costo de la evaluación** | Es **hundido**: no va al flujo |
| 29 | **¿Por qué no IVA?** | Pasamanos (débito − crédito). Entraría si pasa más de un año entre IVA compra y venta, o si el crédito no es recuperable |
| 30 | **Cubrir costos con 15.000 un.** | Distinguir niveles: fijos, + depreciación, + intereses. No incluir los 2 empleados (no incrementales) salvo que se aclare |
| 31 | **Precio de equilibrio a largo plazo** | Es el precio con **VAN = 0** (buscar objetivo, no se toma en papel). Sin intereses en el equilibrio de corto plazo |

## Kd: las dos lecturas (y cómo se calcula cada una)

El enunciado **no da deuda existente**, así que hay dos opciones. Ver [[15 WACC y tasa de descuento]].

| | Kd | Cómo sale | WACC | VAN accionista | VAN puro |
|---|---:|---|---:|---:|---:|
| **Criterio de cátedra (usada)** | **10%** | Kd actual que Jorge iba a agregar al enunciado ([[Dudas abiertas para consultar]] #18). Los préstamos nuevos quedan **afuera** | 17,85% | \$15,7M | \$17,9M |
| Sensibilidad: Kd ponderado de los 2 préstamos | 61,1% | Σ(monto × TEA) / Σ monto | 34,46% | \$7,9M | \$8,3M |

**Procedimiento para encontrar el Kd (paso a paso):**

1. **Buscar en el enunciado las deudas financieras que la empresa ya tiene** (montos y tasas). Dejar afuera proveedores y los préstamos del proyecto (los que se están evaluando). En Estrella no hay ninguna.
2. **Pasar cada tasa a TEA** ([[03 Tasas de interés]]): TEA = (1 + TNA/m)^m − 1.
3. **Multiplicar el monto de cada deuda por su TEA.**
4. **Sumar esos productos y dividir por la suma de los montos:** Kd = Σ(monto × TEA) / Σ monto.
5. **Si no hay deudas existentes:** usar el Kd que dé la cátedra (acá 10%) o escribir un supuesto. No inventar uno.

**Cálculo del Kd ponderado de los préstamos** (aplicando los pasos 2 a 4 a los dos préstamos, solo como sensibilidad):

| Préstamo | Monto | TEA | Monto × TEA |
|---|---:|---:|---:|
| 1 | 2.500.000 | 74,90% | 1.872.516 |
| 2 | 2.500.000 | 47,29% | 1.182.242 |
| **Total** | **5.000.000** | | **3.054.758** |

Kd = 3.054.758 / 5.000.000 = **61,09%**. Con montos iguales coincide con el promedio simple. Usar **TEA**, no las TNA (60% y 40%).

**Ke y WACC (paso a paso):**
- Ke = Rf + β × (Rm − Rf) + RP = 1% + 1,2 × (12% − 1%) + 15% = **29,2%**. Error típico: `0,01 + 1,2 × 0,12 + 0,15` = 30,4% (falta restar Rf a la tasa del mercado).
- Xe = Xd = **50%** (el enunciado lo da en partes iguales).
- WACC = 0,5 × 29,2% + 0,5 × 10% × (1 − 0,35) = **17,85%**.

Las conclusiones (conviene y no apalanca) valen con los dos Kd. Si el enunciado no trae Kd, escribir el supuesto y consultarlo.

## Errores que aparecieron en mi planilla (para no repetirlos)

| Error | Síntoma | Corrección |
|---|---|---|
| **VL del servidor nuevo solo en GND**, sin su ajuste | FF del año 5 con \$800.000 de menos (12.585.235 en vez de 13.385.235) | Agregar "Valor Libro Servidor Nuevo" en **ajustes de GND** (+800.000, año 5) en los dos flujos |
| **FF del flujo puro sin la utilidad neta** | VAN puro de −6,5M (el FF del año 1 daba 2,6M en vez de 6,1M) | FF = UN + ajustes de GND − ENAI + INAI. Revisar que la fórmula tome la fila de UN |

> [!tip] Control rápido
> Todo lo que está en **GND** tiene que aparecer, con el mismo importe, en **ajustes de GND**: depreciaciones **y** valores libro. Si las sumas de los dos bloques no coinciden, falta un ajuste.

Con las dos correcciones, a WACC 34,46%: VAN accionista \$7,86M y VAN puro \$8,30M → **no apalanca**. Con la planilla sin corregir parecía que sí.

## Resultados de referencia (con los supuestos de arriba)

- VAN puro \$17,9M · VAN accionista \$15,7M · TIR 64,9% / 76,3%.
- Precio de equilibrio de largo plazo: \$663 sin IVA (\$802 con IVA) para el flujo del accionista.
