# Análisis Exploratorio de Datos (EDA) sobre la Incidencia de Cáncer de Pulmón

Este proyecto realiza un Análisis Exploratorio de Datos (EDA) en un conjunto de datos que incluye información sobre la incidencia de cáncer de pulmón, así como varios factores de riesgo asociados.

El dataset se obtuvo de Kaggle: [Lung Cancer Data](https://www.kaggle.com/datasets/iamtanmayshukla/lung-cancer-data).

## Descripción del Dataset

El dataset contiene 16 columnas y 309 filas, que representan lo siguiente:

- `GENDER`: Género del paciente (categoría).
- `AGE`: Edad del paciente (int).
- `SMOKING`: Indica si el paciente fuma (int, 1: Sí, 0: No).
- `YELLOW_FINGERS`: Indica si el paciente tiene dedos amarillos (int, 1: Sí, 0: No).
- `ANXIETY`: Indica si el paciente tiene ansiedad (int, 1: Sí, 0: No).
- `PEER_PRESSURE`: Indica si el paciente está bajo presión de sus pares (int, 1: Sí, 0: No).
- `CHRONIC DISEASE`: Indica si el paciente tiene enfermedades crónicas (int, 1: Sí, 0: No).
- `FATIGUE`: Indica si el paciente experimenta fatiga (int, 1: Sí, 0: No).
- `ALLERGY`: Indica si el paciente tiene alergias (int, 1: Sí, 0: No).
- `WHEEZING`: Indica si el paciente tiene silbido al respirar (int, 1: Sí, 0: No).
- `ALCOHOL CONSUMING`: Indica si el paciente consume alcohol (int, 1: Sí, 0: No).
- `COUGHING`: Indica si el paciente tiene tos (int, 1: Sí, 0: No).
- `SHORTNESS OF BREATH`: Indica si el paciente tiene falta de aliento (int, 1: Sí, 0: No).
- `SWALLOWING DIFFICULTY`: Indica si el paciente tiene dificultad para tragar (int, 1: Sí, 0: No).
- `CHEST PAIN`: Indica si el paciente tiene dolor en el pecho (int, 1: Sí, 0: No).
- `LUNG_CANCER`: Indica si el paciente tiene cáncer de pulmón (categoría, 1: Sí, 0: No).

## Instalación

Para ejecutar este proyecto, asegúrate de tener Python 3.9 instalado en tu sistema. Luego, puedes instalar las bibliotecas necesarias utilizando pip:

```bash
pip install -r requirements.txt
