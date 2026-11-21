# Ej 42 · Cervezas: preguntas y respuestas

Consultas hechas mientras se resolvía el ejercicio, con la respuesta concreta de cada una. Los números son los de la planilla [42 - Cervezas.xlsx](42%20-%20Cervezas.xlsx), ya corregida.

**Supuestos a dejar escritos en la hoja:**
- La alternativa B (9%, 8 años) se tomó como **alemán** (capital constante), porque el enunciado no aclara el sistema. Con francés daría otro resultado.
- Las tasas (12%, 10%, 9%) se usan como **efectivas anuales**: el enunciado no indica capitalización.
- Punto 5: se interpretó "premio por riesgo" como Rm − Rf = 8%, y la tasa de 6,57% como Rf.

---

## 1. ¿El royalty / know-how es una inversión?

**No.** Es un pago periódico de $800.000 por año durante 5 años, así que va como **egreso afecto a impuestos (EAI)** en los años 1 a 5, junto con la administración. No se activa ni se deprecia. Del año 6 en adelante desaparece. Solo se activaría si fuera un pago inicial grande o una licencia permanente.

## 2. ¿De qué depende que un ingreso o egreso sea afecto a IIGG?

De si el movimiento **pasa por el estado de resultados** (ganancia o gasto) o es un **movimiento permutativo** (cambia la forma del patrimonio).

| | Afecto (IAI / EAI) | No afecto (INAI / ENAI) |
|---|---|---|
| Ingresos | Ventas netas, venta de activos, ahorros | Préstamo recibido, recupero de capital de trabajo |
| Egresos | Costos, sueldos, comisiones, regalías, **intereses**, indemnizaciones | Inversiones, capital de trabajo, **amortización de capital** |

Los gastos no desembolsables (depreciación) se restan para calcular el impuesto y se suman de vuelta en los ajustes.

## 3. El enunciado dice que la inversión se financia 75% y que el capital de trabajo tiene "condiciones similares". ¿A qué se refiere?

Que el capital de trabajo se financia **100% con deuda**, en las mismas condiciones del préstamo (10%, 6 cuotas de capital desde el año 4). Es un único préstamo:

| | Base | Deuda | Capital propio |
|---|---:|---:|---:|
| Activos fijos | 23.000.000 | 75% = 17.250.000 | 25% = 5.750.000 |
| Capital de trabajo | 900.000 | 100% = 900.000 | 0 |
| **Total** | | **18.150.000** | **5.750.000** |

## 4. ¿Cómo se calcula cada columna de la tabla de préstamo?

| Columna | Cálculo |
|---|---|
| Saldo inicial | Año 1 = P. Después, saldo final del año anterior |
| Interés | Saldo inicial × i (siempre, también en gracia) |
| Amortización | Francés: cuota − interés · Alemán: P / n · Americano: 0 hasta el último año |
| Cuota | Francés: PAGO · Alemán y americano: amortización + interés |
| Saldo final | Saldo inicial − amortización |

El saldo de cada fila es el **saldo inicial** de ese año, y el interés se calcula sobre ese saldo. En el ej 42: interés de 1.815.000 en los años 1 a 3 y amortización de 3.025.000 en los años 4 a 9.

## 5. "Capital de trabajo de 4 meses de costo variable, excluyendo comisiones y gastos financieros": ¿qué son los gastos financieros?

Los **intereses del préstamo**. La base es solo el costo variable de producir: 20.000 × $135 = $2.700.000 por año. Capital de trabajo = 2.700.000 / 12 × 4 = **$900.000**. Se excluyen las comisiones (1,5% de ventas) y los intereses.

## 6. ¿Cómo sé qué alternativa de financiamiento elegir?

Armás el flujo del accionista con cada préstamo, descontás al mismo 12% y elegís el de **mayor VAN**. No se decide solo por la tasa, porque el plazo y la gracia también pesan.

| Alternativa | VAN al 12% |
|---|---:|
| A (10%, gracia 3 años, 6 cuotas de capital) | **$17.822.784** |
| B (9%, 8 cuotas de capital, años 1 a 8) | $17.734.277 |

**Gana A por $88.504.** El enunciado solo define el sistema de A ("cuotas iguales de capital" = alemán). Para B se asumió alemán. Con B en francés (cuota de $3.279.240) ganaría B por unos $93.000.

## 7. ¿Los dos préstamos usan sistema alemán?

A sí lo dice el enunciado. B no, y se asumió alemán por comparabilidad.

## 8. Corrección: el interés se calcula sobre el saldo de ese año

La fórmula es **Interés_t = Saldo inicial_t × i**, con el saldo inicial igual al saldo final del año anterior. Es lo mismo que "saldo de la misma fila" en las tablas. Ya está corregida la notación en el apunte de préstamos.

## 9. ¿La tasa de los inversionistas es TNA? ¿El VAN va con la TEA?

El enunciado dice "12% anual" sin capitalización, así que es una **tasa efectiva anual** y se usa tal cual (con capitalización anual TNA = TEA). Convertir TNA → TEA solo hace falta cuando el enunciado dice "capitalizable mensual / bimestral…".

## 10. Un compañero usa 12,68%. ¿Por qué?

Sale de tratar el 12% como TNA capitalizable mensual: (1 + 0,12/12)¹² − 1 = 12,68%. El enunciado no dice eso. No encontré nada en el apunte que lo respalde. Conviene confirmarlo con el docente; si no se puede, usar 12% y escribir el supuesto.

## 11. Revisión de la planilla: errores encontrados

1. **Alternativa A, interés del año 5 (H10):** tenía 1.815.000, debía ser **1.512.500**. El FF del año 5 pasa de 3.596.260 a **3.868.510**.
2. **Alternativa B, fila FF:** la fórmula no sumaba la utilidad neta. Debe ser `=D66+SUM(D68:D70)-SUM(D72:D76)+SUM(D78:D79)`.
3. **TIR (C97 y C143):** apuntaba al flujo del accionista (58,7%). Debe ser la del flujo **puro**: `=TIR(C127:M127)` = **23,9%**.

## 12. ¿Cómo calculo la rentabilidad del proyecto?

Con la **TIR** del flujo puro: la tasa que hace VAN = 0. Conviene si TIR > tasa de descuento. En Excel: `=TIR(rango)`. En el apunte, la TIR no se toma en papel.

## 13. "VAN del FF puro" ¿es sin préstamo?

Sí. Se sacan el préstamo (INAI), los intereses (EAI) y la amortización (ENAI). La inversión va por el **total**: año 0 = −23.000.000 − 900.000 = **−23.900.000**. **VAN puro al 12% = $15.498.385.** Si te da 33.648.385, el año 0 quedó en −5.750.000 (diferencia de 18.150.000 = el préstamo).

## 14. ¿Qué es el VAN de los inversionistas?

Es el VAN del **flujo del accionista** con el préstamo elegido (A) y descontado al 12%: **$17.822.784**. Los inversionistas son los dueños: ponen el capital propio ($5.750.000 en el año 0) y pagan los intereses y amortizaciones al banco. El banco, no ellos, es quien recibe esos pagos. La diferencia con el VAN puro (unos $2,3M) muestra el apalancamiento.

## 15. Punto 5: ¿qué hago con los datos?

Rf = 6,57%, β = 1,27, premio por riesgo (Rm − Rf) = 8%:

$$K_e = R_f + \beta \cdot (R_m - R_f) = 0{,}0657 + 1{,}27 \times 0{,}08 = \mathbf{16{,}73\%}$$

La β **multiplica** al premio, no se suma. No hay riesgo país porque el enunciado no lo da (en la fórmula es opcional). Sin deuda previa de la empresa, Kd = 0 y WACC = Ke, así que 16,73% pasa a ser la tasa de descuento. Los flujos no cambian.

| | 12% | 16,73% |
|---|---:|---:|
| VAN puro | $15.498.385 | $7.896.313 |
| VAN inversionistas (A) | $17.822.784 | $13.106.129 |
| VAN con B | $17.734.277 | $12.292.816 |
| Ventaja de A sobre B | $88.504 | $813.313 |

**Justificación:**
- Todos los VAN bajan porque se descuenta a una tasa mayor.
- El proyecto sigue siendo rentable (VAN > 0 y TIR 23,9% > 16,73%).
- Sigue ganando A, con más margen: con tasa alta vale más postergar el pago del capital.
- El préstamo apalanca más, porque su costo (9% o 10%) está muy por debajo de la tasa exigida.
- El monto de la deuda ($18.150.000) y la TIR no cambian, porque no dependen de la tasa de descuento.

## 16. ¿La TIR es la misma con las dos tasas?

Sí: la TIR del flujo puro es **23,9%** con 12% y con 16,73%. Lo que cambia es el margen: unos 12 puntos sobre el 12%, unos 7 sobre el 16,73%. La TIR del flujo del accionista es otra (58,7%) y no es la rentabilidad del proyecto.

## 17. Glosario del CAPM

- **Rf:** tasa libre de riesgo (inversión sin riesgo, como un bono del tesoro).
- **Rm:** rendimiento esperado del mercado.
- **β:** riesgo no diversificable (cuánto se mueve respecto del mercado).
- **Prima de riesgo de mercado = premio por riesgo = Rm − Rf.**

---

## Respuestas finales del ejercicio

| Punto | Respuesta |
|---|---|
| 1. Monto de la deuda | $18.150.000 |
| 2. Alternativa elegida | A (gana por $88.504) |
| 3. Rentabilidad / VAN puro | TIR 23,9% · VAN $15.498.385 |
| 4. VAN inversionistas | $17.822.784 |
| 5. Con Ke = 16,73% | VAN puro $7.896.313 · VAN inversionistas $13.106.129 · sigue ganando A |
