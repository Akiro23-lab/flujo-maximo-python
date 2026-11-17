# Flujo Máximo · Ford-Fulkerson

Programa de escritorio que calcula el flujo máximo de una red con el método de Ford-Fulkerson y muestra cada iteración paso a paso.

Matemática Computacional (1AMA0726) · Sección 15402 · Grupo 6
Integrantes: Aguirre, Bañez, Campos, Ccanto, Portales

## Qué hace

- Crea redes de 7 a 16 nodos: a mano, con la matriz de capacidades o de forma aleatoria.
- Ejemplos incluidos: red de 7 nodos y red con varias fuentes y sumideros (superfuente S y supersumidero T).
- Muestra el camino aumentante, las etiquetas (anterior, Δ), la red residual y el flujo total en cada iteración.
- Usa flujo negativo (arcos inversos) solo cuando ya no queda un camino directo, y compara con la solución sin flujo negativo.
- Calcula el corte mínimo, la tabla de todos los cortes y un reporte de la solución.
- Modo práctica: el estudiante arma cada camino, calcula Δ y el programa lo corrige.
- Tutorial y sección de conceptos dentro del programa.

## Cómo ejecutarlo

### Opción 1: el ejecutable (Windows)

Descarga **FlujoMaximo.exe** desde [Releases](../../releases) y ábrelo con doble clic. No necesita instalar Python.
Si Windows muestra el aviso de SmartScreen: **Más información → Ejecutar de todas formas**.

### Opción 2: el código en Python (Windows, Mac o Linux)

Necesita Python 3.10 o superior. Solo usa la biblioteca estándar (Tkinter), así que no hay que instalar nada más.

```
python FlujoMaximo.py
```

En Mac o Linux: `python3 FlujoMaximo.py`

### Crear el .exe

En Windows, con Python instalado, ejecuta **crear_exe.bat**. Instala PyInstaller y deja el ejecutable en la carpeta `dist`.
