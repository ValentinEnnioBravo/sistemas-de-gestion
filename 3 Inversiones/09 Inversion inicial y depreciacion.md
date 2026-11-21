---
tags: [sdg, inversiones, depreciacion]
aliases: [Inversión inicial, Depreciación, Amortización, Valor de origen, Instalación, Intangibles, Licencias, Terreno]
---

# 09 · Inversión inicial y depreciación

← [[08 Sueldos, indemnizaciones y ahorros]] · siguiente → [[10 Venta de activos y valor residual]]

## 1. Inversión inicial (ENAI, año 0)

$$\text{Valor amortizable} = \text{Precio de compra (sin IVA)} + \text{Transporte} + \text{Instalación / puesta a punto}$$

- Se pone **por el total**, aunque una parte se financie con préstamo. El préstamo se suma aparte como INAI. [Clase 25/09] → [[16 VAN puro vs VAN del accionista - apalancamiento]]
- Se pone en **ENAI** porque es permutativo: no paga impuesto [Guía ej 20].
- **Sin IVA** → [[05 Ventas, IIBB e IVA]].

> [!warning] Desinstalación: NO va al valor amortizable
> - Criterio de Jorge: la desinstalación es un **EAI en el último año**, cuando la desinstalás. *"¿Por qué carajo pagarías una desinstalación [al inicio]?"* Además, ponerla al final da mayor VAN. [Clase 23/10]
> - En Economía la suman al valor amortizable. *"Está bien que Economía marque eso"*, pero acá no. [Clase 23/10]
> - **Si el enunciado dice que se paga por adelantado** (ej 51: \$100.000 al comprar): se puede poner como **EAI en el año que se paga** (lo menos discutible, porque la lista de capitalizables del PPT es traslado + instalación) o **activarla y depreciarla**. *"Lo podés poner de las dos formas."* [Clase 20/10]

## 2. Depreciación lineal (GND)

$$\text{Depreciación anual} = \frac{\text{Valor amortizable}}{\text{Vida útil}}$$

> [!important] Valor residual = 0 para depreciar
> Siempre depreciá el **100%** (valor residual contable cero). El valor de venta va **aparte**, como IAI en el último año. [Clase 23/10]
> **Por qué** (bielsista): si restás el residual antes de depreciar, quien revisa el flujo *"no se da cuenta qué valor de reventa le estás poniendo al activo"*. Si ve que vendés en el año 5 en 900.000 una máquina de 1.000.000, se le prende una alarma.

- La depreciación arranca el **año siguiente** a la compra: compra en año 0 → depreciación en años 1…n.
- Si la vida útil es **mayor** que el horizonte, al final queda **valor libro** → [[10 Venta de activos y valor residual]].
- Si la vida útil es **menor** que el horizonte, deja de depreciarse cuando termina (y hay que ver si se reemplaza; ej 18B).

### Ejemplo base

Máquina \$10.000.000 + instalación \$1.000.000 + transporte \$500.000 · vida útil 5 años.

| Concepto | Importe |
|---|---:|
| Valor amortizable (ENAI año 0) | 11.500.000 |
| Depreciación anual (GND años 1–5) | 2.300.000 |
| Ajuste GND (años 1–5) | +2.300.000 |

## 3. Activos que no se deprecian (o casi)

| Activo | Tratamiento |
|---|---|
| **Terreno** | **No deprecia** (*"deprecia a tasa cero"*, lo dice la resolución técnica). Su valor libro es siempre el **valor de compra**. [Clase 16/10] [Clase 20/10] |
| **Capital de trabajo** | Tampoco deprecia; se recupera al final. [Clase 16/10] |
| Vidas útiles típicas (resolución técnica) | Auto 5 años · computadora 3 · máquina 10 · edificio 50. [Clase 20/10] |

## 4. ¿Inversión (se deprecia) o egreso (EAI)?

| Concepto | ¿Qué es? | Criterio |
|---|---|---|
| Máquina, equipo, vehículo del proyecto | Inversión | Activo fijo |
| **Licencia comprada "para siempre"** (SAP, licencias ERP del ej 36) | Inversión → se deprecia | La usás varios años [Clase 20/10] |
| **Licencia / suscripción periódica** (Office anual, licencia de marca del ej 51, copyright anual) | **EAI** en el año en que **se paga** | Pago por uso [Clase 20/10] [Clase 23/10] |
| **Royalty / know-how anual** (ej 42: \$800.000/año durante 5 años) | **EAI** (lo dice como costo fijo) | [Clase 20/10] |
| **Down payment** (pago inicial grande por una licencia o representación) | Puede activarse y depreciarse | [Clase 20/10] |
| **Mantenimiento anual de licencias** (ej 36: 20% del valor) | EAI | |
| **Capacitación** puntual (Toldo: \$4,5M en el año 3) | **EAI** | [Consulta 02/10] |
| **Capacitación de transformación** (cambiar toda la empresa a Agile) | Puede activarse y depreciarse | *Cambio cultural que se reparte en varios años* [Clase 20/10] |
| **Consultoría** de implementación (ej. SAP, con viáticos y comidas) | Se activa con la implementación | [Clase 20/10] |
| Consultoría puntual (ej 36: 3 meses de \$500) | EAI | |
| **Campaña de lanzamiento** grande, única, que posiciona el producto | Inversión → se deprecia | [Clase 23/10] |
| "Inversión en marketing del 25% de la venta" | **EAI**, aunque se llame "inversión" | [Clase 23/10] |
| Desarrollo de software con horas hombre (ej 47, 37) | Inversión → se deprecia | Lo dice el enunciado |

> [!tip] Cuidado con la palabra "inversión"
> *"Recursos humanos dice 'vamos a invertir en nuestra gente': capacitación, las tortas de cumpleaños, la caja navideña… En verdad es egreso afecto a impuestos."* [Clase 23/10]

### Licencias con calendario de pago (ej 51)

| Licencia del año | Monto | Se abona en el año |
|---|---:|---:|
| 1 | 400.000 | 0 |
| 2 | 400.000 | 2 |
| 3 | 500.000 | 5 |
| 4 | 550.000 | 4 |
| 5 | 550.000 | 4 |

→ **EAI** según la columna **"se abona"**: año 0 = 400.000 · año 2 = 400.000 · año 4 = **1.100.000** (se suman) · año 5 = 500.000 · años 1 y 3 = en blanco. *"Hago de cuenta que firmé el contrato y hice esto."* [Clase 23/10]

## 5. Activos que ya tenía la empresa y se traen al proyecto

Se pone su **depreciación pendiente** como GND (con su ajuste). No hay salida de caja: es costo hundido. [Clase 20/10] [Clase 23/10]

| Ejercicio | Dato | Lectura |
|---|---|---|
| 45 Toldo · estantería | Compra \$500.000, VR al inicio \$200.000 | Si deprecia en **5 años**: ya pasaron 3 → quedan **2 cuotas de \$100.000**. Si fuese en 10: \$50.000/año → quedan 4. *"O es 5 o es 10, no me compliques."* [Clase 16/10] [Consulta 02/10] |
| 46 Bielsa · estructura metálica | Comprada hace 3 años por \$50.000 | A 5 años: \$10.000/año → quedan 2 cuotas |
| 50 Piletazo · estibador | Cuota \$200.000, VL al inicio \$1.200.000, todo a 10 años | VO = 200k × 10 = \$2M · quedan 6 cuotas |
| 51 Scaloni · mobiliario | Cuotas de \$50.000, "valor residual" \$150.000 | Quedan **3 cuotas** de \$50.000. El "valor residual" es en realidad el **valor libro** [Clase 23/10] |

> [!note] Regla para leerlos
> Si te dan el **VR / VL al inicio** y la cuota → cuotas restantes = VL / cuota.
> Si te dan **VO y VL** sin años → suponé la vida útil de los otros activos del ejercicio (5 o 10). [Clase 23/10]

## Fuentes
[Clase 16/10] · [Clase 20/10] · [Clase 23/10] · [Clase 25/09] · [Consulta 02/10] · [Guía ej 18, 20, 36, 42, 45, 46, 47, 50, 51] · [Resumen amigo: Inversiones, Licencias] · [Planilla amigo: Toldo v2, Bielsa v2, 36, 50]
