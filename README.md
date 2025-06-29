
# Predicción del Precio del Petróleo usando Machine Learning

Este repositorio contiene un proyecto de ciencia de datos que implementa un modelo de Machine Learning para predecir el precio del petróleo a partir de una serie temporal histórica. El modelo ha sido desarrollado en Python utilizando una red neuronal LSTM (Long Short-Term Memory) y RC (Reservoir Computing).

## 📁 Estructura del repositorio

```
├── Code.ipynb           # Notebook principal con el código de entrenamiento y predicción
├── Data Set.csv         # Conjunto de datos históricos (precios del petróleo)
├── README.md            # Documentación del proyecto
```

## 📦 Requisitos

Antes de ejecutar el código, asegúrate de tener instalado Python 3.7 o superior y las siguientes librerías:

```bash
pip install numpy pandas matplotlib scikit-learn keras tensorflow
```

## ▶️ Instrucciones de ejecución

Sigue los pasos a continuación para reproducir los resultados del proyecto:

1. **Carga de datos**:
   Asegúrate de que el archivo `Data Set.csv` esté en la misma carpeta que el notebook. El archivo contiene los precios históricos necesarios para entrenar el modelo.

2. **Entrenamiento y evaluación**:
   El modelo LSTM Y RC será entrenado con los datos cargados, y se generarán gráficos de comparación entre los valores reales y predichos. Además, se calcularán métricas como MAE, RMSE, MAPE y NRMSE.

3. **Visualización de resultados**:
   Al final del notebook se mostrarán visualizaciones que permiten evaluar el desempeño del modelo y comparar resultados.

## 📊 Resultados esperados

El modelo debe producir:
- Gráficos de entrenamiento vs. prueba
- Errores de predicción
- Salida final del modelo con pronósticos del precio del petróleo

## 🧠 Modelos utilizados

- LSTM (Long Short-Term Memory)
- computing (RC)
- [Opcional]  ARIMA para comparación.

## ✍️ Autor

Adrián Vacace  

