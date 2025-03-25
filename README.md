# Teoría Cuántica Básica, Observables y Medidas

Este proyecto investiga la dinámica de sistemas cuánticos a través del uso de matrices unitarias y el principio de superposición. Se examinan propiedades fundamentales, como la unitariedad de las matrices, la capacidad de descomponer estados y la evolución temporal de dichos sistemas. Asimismo, estos conceptos se aplican a registros cuánticos, elementos esenciales en la computación cuántica.


## Requisitos previos

Para ejecutar este proyecto en un Jupyter Notebook con Python, necesitas:

- **Python**
- **Jupyter Notebook**
- **Bibliotecas necesarias** (Si no están instaladas, ejecuta el siguiente comando):

```sh
%pip install numpy matplotlib
import numpy as np
import matplotlib.pyplot as plt
```

## Contenido

Este proyecto desarrolla una simulación en Python de un sistema cuántico en el que una partícula está restringida a posiciones discretas. Se aplican los principios fundamentales del capítulo 4 para abordar distintos desafíos, como la representación del estado mediante un vector ket, el cálculo de probabilidades de ubicación, la manipulación de amplitudes de transición y la acción de observables. Además, se verifica la hermiticidad de matrices, se calculan la media y la varianza de un observable, se analizan sus valores propios y se determina la probabilidad de transición a sus vectores propios. Finalmente, se modela la evolución temporal del sistema empleando matrices unitarias.

Se incluyen soluciones a los problemas del libro 4.3.1, 4.3.2, 4.4.1 y 4.4.2. Además, se analiza la separabilidad de estados en los ejercicios 4.5.2 y 4.5.3.

## Instrucciones de uso

1. Clonar el repositorio desde GitHub en tu máquina local.
2. Abrir Jupyter Notebook y cargar el archivo principal.
3. Ejecutar las celdas en orden, asegurándote de que todas las dependencias estén instaladas.

## Pruebas

Para validar los cálculos realizados, se han diseñado pruebas automatizadas utilizando `unittest` en Python:

- **Validación de parámetros**: Verifica que los valores de entrada sean coherentes.
- **Cálculo de interferencia**: Compara patrones de interferencia con valores teóricos.
- **Generación de gráficos**: Inspecciona la correcta visualización de diagramas de barras.

## Construido con

- **Python** - Lenguaje de programación principal.
- **NumPy** - Manipulación de matrices y cálculos matemáticos.
- **Matplotlib** - Visualización de datos y gráficos.

## Autor

**Oscar Santiago Merino Suarez**

## Licencia

Este proyecto está bajo la licencia MIT - consulta el archivo LICENSE.md para más detalles.

## Agradecimientos

- A herramientas como Visual Studio Code, NumPy y Matplotlib por facilitar la implementación y visualización.
- A los recursos educativos que ayudaron a comprender y aplicar los conceptos del proyecto.


