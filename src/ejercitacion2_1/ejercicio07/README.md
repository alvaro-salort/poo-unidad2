# Ejercicio 07 — CuentaBancaria

**Objetivo:** aplicar encapsulamiento con `private` y accesos controlados.
**Salida esperada:** depósitos, retiros válidos, saldo insuficiente y cuenta abierta con saldo negativo (corregido a 0).

**Conceptos:** `private` · getters/setters · validación de negocio · saldo inicial saneado con `Math.max`

```bash
javac -d bin src/ejercitacion2_1/ejercicio07/CuentaBancaria.java
java -cp bin ejercitacion2_1.ejercicio07.CuentaBancaria
```