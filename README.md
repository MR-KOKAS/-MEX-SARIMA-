# -MEX-SARIMA-
🥤- PROJECT - STATISTICS - BASE - TEC -🥤
# Pronóstico del índice IGAE para México

Este proyecto tiene como objetivo diseñar un modelo **ARIMA-SARIMA** para pronosticar el índice **Índice General de Actividad Económica (IGAE)** de México. Este índice es publicado mensualmente por el **INEGI** y representa la actividad económica general para cada industria y para toda la economía.

## Descripción del Proyecto

El índice IGAE se encuentra en la columna `Índice de volumen físico base 2018=100|Total`, que contiene datos desde 1993 hasta 2024. Este proyecto analiza la serie temporal del IGAE y desarrolla un modelo predictivo basado en técnicas avanzadas de modelado de series temporales.

### Contenido del Dataset

- **Fuente de los datos**: INEGI, descargable desde su sitio web mediante la búsqueda “inegi bie igae”.
- **Formato del dataset**: El archivo contiene columnas descriptivas y valores mensuales del índice para diferentes sectores.

## Requerimientos

Este proyecto utiliza Python y requiere las siguientes bibliotecas:

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
from statsmodels.stats.outliers_influence import variance_inflation_factor
import statsmodels.api as sm
from scipy.stats import pearsonr
import scipy.stats as stats
from scipy.stats import mstats
