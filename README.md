# 🧠 Análisis y Predicción de Salud Mental con Machine Learning

Este es mi primer proyecto práctico de análisis de datos e Inteligencia Artificial en Python. Como estudiante en mis primeros meses de programación, el objetivo de este repositorio es aplicar herramientas de código abierto a un caso de uso clínico simulado.

## 📋 Descripción del Proyecto
El cuaderno de Jupyter (`Codigo_S4_IA.ipynb`) analiza un conjunto de datos médicos de pacientes con diferentes síntomas (anamnesis). A partir de estos datos, entrena un modelo de Machine Learning para intentar predecir diagnósticos como Depresión, Trastorno Bipolar (Tipo 1 y 2) o un estado Normal.

## 🚀 ¿Qué hace el código?
- **Exploración de datos (EDA):** Lee el historial médico en un archivo `.csv` usando la librería `pandas`.
- **Análisis visual:** Genera gráficos y mapas de calor con `matplotlib` y `seaborn` para descubrir qué síntomas suelen aparecer juntos.
- **Entrenamiento de la IA:** Implementa un modelo predictivo "Random Forest" con `scikit-learn` (logrando un 58% de precisión en este primer intento).
- **Sistema de Alerta:** Incluye un algoritmo básico para clasificar a los pacientes según su nivel de riesgo clínico basado en síntomas críticos.

## 🛠️ Herramientas Utilizadas
- Anaconda
- Jupyter Notebook
- Python 3 
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib 
- Seaborn
- Networkx
- Github
- Scipy

## ⚠️ Aviso Ético
*Este proyecto tiene fines estrictamente académicos e introductorios.* El modelo desarrollado aquí tiene límites técnicos y **no debe utilizarse** para tomar decisiones clínicas en el mundo real. Los diagnósticos de salud mental requieren siempre la intervención, empatía y evaluación de un profesional médico calificado.
