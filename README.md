# Cálculo de Dimensión Fractal en Variables Urbanas

Este repositorio contiene un conjunto de scripts en Python para calcular la dimensión fractal de variables urbanas a partir de imágenes binarizadas. Se implementan versiones secuencial y paralela del método de box-counting.

## Requisitos

- Python 3.8 o superior
- Bibliotecas necesarias:
  - numpy
  - matplotlib
  - pillow

Puedes instalarlas con:

```bash
pip install -r requirements.txt

## Uso

python main.py ruta/a/tu/imagen.png

## Estructura del repositorio

main.py: Script principal para ejecutar el análisis.

src/fractal_dimension.py: Implementación secuencial del cálculo.

src/parallel_version.py: Implementación paralela con multiprocessing.

images/: Carpeta sugerida para guardar las imágenes de entrada.
