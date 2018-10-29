# ML Michi Studio

Simple michi game studio to test decision tree as machine learning example.

Simple studio para juego de michi, para probar un árbol de decisión como ejemplo de machine learning.

## Idea

- Cada jugada es almacenada en memoria, en forma de un árbol de decisiones.
- Si luego se le pregunta al juego por la siguiente jugada, éste puede revisar en la memoria cuál sería la mejor opción en base a la experiencia adquirida.

## Status

- Registro de jugadas manuales.
- Registro de jugadas al azar (random).
- Intento básico de jugadas AI.
  - Se hace una elección aleatoria entre las opciones disponibles, dando más peso a la memoria.
  - El efecto de esto es que se tiende a repetir una ruta aprendida, incluso las de derrota.

## To Do

- Mejorar el razonamiento para que el juego trate de ganar.
- Entrenamiento automático.
- Portar la idea al juego de Cuatro en Línea.
