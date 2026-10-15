# Ejercicio 07 — CalculadoraPromocion

**Objetivo:** sobrecargar un mismo método y dejar que la JVM elija la firma según los argumentos.
**Salida esperada:** un precio de $10.000 con descuento base 10%, especial 25% y cupón fijo de $3.000.

**Conceptos:** sobrecarga (overloading) · firma del método · resolución estática en compilación

```bash
javac -d bin src/ejercitacion2_2/ejercicio07/CalculadoraPromocion.java
java -cp bin ejercitacion2_2.ejercicio07.CalculadoraPromocion
```