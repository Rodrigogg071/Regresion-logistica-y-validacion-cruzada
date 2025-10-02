# Regresión Logística y Validación Cruzada

**Nombre:** Juan Rodrigo Guerrero De la Garza  
**Matrícula:** 611471  

**Objetivo:** Ser capaz de generar un modelo para resolver un problema de clasificación y evaluarlo usando una metodología de validación cruzada.

---

Los datos utilizados en esta actividad provienen del **UCI Machine Learning Repository**, 
en particular del conjunto de datos **Auto MPG**, disponible en:  
[https://archive.ics.uci.edu/ml/datasets/auto+mpg](https://archive.ics.uci.edu/ml/datasets/auto+mpg)

El archivo de datos original se puede descargar directamente desde:  
[http://archive.ics.uci.edu/ml/machine-learning-databases/auto-mpg/auto-mpg.data](http://archive.ics.uci.edu/ml/machine-learning-databases/auto-mpg/auto-mpg.data)

Este dataset contiene información sobre automóviles de distintos modelos fabricados entre 
1970 y 1982, con variables técnicas y de rendimiento.

---

## Diccionario de variables
A continuación, se describen las variables incluidas en el dataset:

| Variable       | Tipo         | Descripción                                                    |
|----------------|-------------|----------------------------------------------------------------|
| **mpg**        | Continua     | Millas por galón (rendimiento de combustible) – *Variable dependiente (Y)* |
| **cylinders**  | Entera       | Número de cilindros del motor                                  |
| **displacement** | Continua   | Desplazamiento del motor (pulgadas cúbicas)                    |
| **horsepower** | Continua     | Potencia del motor (caballos de fuerza) *(contiene valores faltantes)* |
| **weight**     | Continua     | Peso del automóvil (libras)                                    |
| **acceleration** | Continua   | Tiempo en segundos para acelerar de 0 a 60 mph                 |
| **model_year** | Entera       | Año del modelo (70 = 1970, etc.)                              |
| **origin_1**     | Binaria       | Procedencia del automóvil (1 = EE.UU., 0 = otro)   |

---


<a href="././A2.2%20611471.ipynb" download>Reporte en formato ipynb</a>  

[Reporte en formato html](./A2.2%20611471.html) 

<a href="auto_mpg_2.csv" download>Base de datos</a>  
