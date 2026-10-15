# Ejercicio 05 — SocioGeek

**Objetivo:** ocultar el estado con `private` y proteger un atributo desde el setter.
**Salida esperada:** el socio con 150 puntos, la asignación válida a 250 y el rechazo del valor negativo.

**Conceptos:** `private` · getters · setter con validación defensiva · invariante (puntos ≥ 0)

```bash
javac -d bin src/ejercitacion2_2/ejercicio05/SocioGeek.java
java -cp bin ejercitacion2_2.ejercicio05.SocioGeek
```