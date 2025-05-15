# TFG – Modelado del S&P 500 con Markov y LSTM

Este repositorio contiene el desarrollo completo del Trabajo de Fin de Grado, enfocado en el análisis y modelado de series temporales del índice S&P 500 mediante un enfoque híbrido que combina Cadenas de Markov Ocultas (HMM) y redes neuronales LSTM.


## 📁 Estructura del repositorio

```
TFG-Markov-LSTM-SP500/
├── scrapper/                     # Código para extracción de datos desde Yahoo Finance
├── datos/                        # Archivos de datos históricos del S&P 500
├── ingenieria_dato/             # Limpieza, transformación y preparación de los datos
├── analisis_dato/
│   ├── modelos/                 # Notebooks con implementación de HMM, LSTM e híbrido
│   └── scripts/                # Funciones y módulos reutilizables del análisis
├── README.md
```

## 🧠 Descripción del proyecto

El objetivo del proyecto es construir un modelo predictivo de series financieras que incorpore información estructural del mercado, extraída a través de un modelo de Markov oculto, como entrada para una red neuronal LSTM. Se evalúa si este enfoque híbrido mejora la capacidad predictiva frente a un modelo LSTM tradicional.

## 🛠️ Herramientas utilizadas

- **Python** (entorno Google Colab)
- **Yahoo Finance**: extracción de datos históricos
- **Pandas, NumPy**: procesamiento y análisis de datos
- **hmmlearn**: implementación del modelo de Markov oculto
- **TensorFlow, Keras**: construcción y entrenamiento de redes LSTM
- **Keras Tuner**: ajuste de hiperparámetros
- **scikit-learn**: escalado de variables y métricas
- **Matplotlib, Seaborn**: visualización de resultados

## 🎯 Objetivo del trabajo

Comparar el rendimiento de una LSTM tradicional frente a un modelo híbrido Markov-LSTM, evaluando la utilidad de los estados ocultos como entrada adicional para la predicción del índice S&P 500.

## 📌 Autor

**[Ismael Castuera Martín]**  
Estudiante de [Business Analytics]  
[Universidad Francisco de Vitoria] – Curso 2024/2025
