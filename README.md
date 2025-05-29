# breast-cancer-classifier
# Clasificador de Cáncer de Mama

Este proyecto utiliza un modelo de Random Forest para clasificar tumores de mama como benignos o malignos utilizando el conjunto de datos `load_breast_cancer` de scikit-learn.

## Contenido

- Exploración de datos
- Comparación de modelos con LazyPredict
- Selección de características con SelectKBest
- Optimización de hiperparámetros con GridSearchCV
- Evaluación del modelo (precisión, matriz de confusión, reporte de clasificación, curva ROC)

## Cómo ejecutar

1. Clona el repositorio:
   ```bash
   git clone https://github.com/Ifom5845/breast-cancer-classifier.git
   ```

2. Instala las dependencias:
   ```bash
   pip install -r requirements.txt
   ```

3. Ejecuta el notebook:
   Abre `breast-cancer-classifier.ipynb` en Jupyter Notebook y ejecuta las celdas.

## Resultados

- Precisión en el conjunto de prueba: 0.98
- AUC: 0.99
