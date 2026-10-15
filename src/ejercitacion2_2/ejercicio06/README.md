# Ejercicio 06 — Comic

**Objetivo:** preservar la integridad del objeto limitando la modificación a métodos de negocio.
**Salida esperada:** ventas hasta agotar el stock, el intento de venta sin unidades y la reposición.

**Conceptos:** sin setter directo para `stock` · métodos de negocio · invariante (stock y precio ≥ 0) · `Math.max`

```bash
javac -d bin src/ejercitacion2_2/ejercicio06/Comic.java
java -cp bin ejercitacion2_2.ejercicio06.Comic
```