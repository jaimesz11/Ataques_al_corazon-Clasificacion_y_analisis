# Ataques al corazón: Predicciones y análisis

Predicciones de ataques al corazón según ciertas variables, las cuales se enumeran a continuación:

### 1. Diccionario de campos

- age - Edad del paciente
- sex - Sexo del paciente
- cp - Tipo de dolor en el pecho ~

  - 0 = Angina de pecho típica
  - 1 = Angina de pecho atípica
  - 2 = Otros dolores
  - 3 = Asintomático
- trtbps - Presión arterial en reposo (en mmHg)
- chol - Colesterol en mg/dl obtenido a través del sensor BMI
- fbs - (Azúcar en sangre en ayunas > 120 mg/dl) ~

  - 1 = Verdadero
  - 0 = Falso
- restecg - Resultados electrocardiográficos en reposo ~

  - 0 = Normal
  - 1 = Normalidad de onda ST-T
  - 2 = Hipertrofia ventricular izquierda
- thalachh - Frecuencia cardíaca máxima alcanzada
- oldpeak - Pico anterior
- slp - Inclinación
- caa - Número de principales vasos
- thall - Resultado de la prueba de esfuerzo con talio ~ (0,3)
- exng - Angina inducida por ejercicio ~

  - 1 = Sí
  - 0 = No
- output - Variable objetivo ~

  - 0 = Menos propensión de sufrir un ataque al corazón
  - 1 = Más propensión de sufrir un ataque al corazón

### 2. Objetivo

Realizar un análisis del dataset y predecir si las personas, según sus características, son propensas a un ataque cardíaco o no.

### 3. Fuente de datos

El dataset procede a kaggle: [Enlace](https://https://www.kaggle.com/rashikrahmanpritom/heart-attack-analysis-prediction-dataset)
