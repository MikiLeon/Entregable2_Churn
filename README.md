# Entregable 2 — Churn Prediction (Máster en Data Science & AI)

## 📌 Descripción del proyecto
Este proyecto aborda la **predicción de churn** (baja o abandono de clientes) usando un dataset de clientes de MobileNOW.  
El objetivo es preparar los datos, explorar patrones relevantes, construir y evaluar **modelos de clasificación** capaces de predecir la probabilidad de churn, y generar todos los artefactos necesarios para su análisis o despliegue.

El flujo principal implementado en el notebook incluye:

- Análisis exploratorio de datos (EDA)  
- Limpieza y preprocesado de datos  
- Ingeniería de variables y codificación de categóricas  
- División train/test y creación de pipelines  
- Entrenamiento y evaluación de modelos de clasificación  
- Exportación de resultados y artefactos de modelo  

---

## 📁 Estructura del repositorio
 Entregable_2:_Churn

```python
 
├── Entregable_2_Churn.ipynb # Notebook principal

├── data/

│ ├── bmw_pricing.csv/ # Datos originales sin modificar

│ └── data_sample_50.xlsx/ # Sample del dataset limpio con 50 predicciones.

├── outputs/

│ ├── data # Datasets de la predicción exportados en .csv y .xlsx

  │ ├── df_prediction_export.csv
              
  │ └── df_prediction_export.xlsx

│ └── pipeline

   │ ├── CatBoostClassifier.pkl

   │ ├── Column_Transformers.pkl

   │ ├── OrdinalEncoder.pkl

   │ └── StandarScaler.pkl
     
├── README.md 

└── requirements.txt # Librerías necesarias.

```


---

## ⚙️ Requisitos e instalación

Recomendado:
- Python 3.8+ (preferible 3.9)  
- Entorno virtual (venv / conda)

Instalación con pip:

```python
git clone https://github.com/MikiLeon/Entregable2_Churn.git
cd Entregable2_Churn
python -m venv .venv
source .venv/bin/activate   # Linux/Mac
.venv\Scripts\activate      # Windows
pip install -r requirements.txt
```
3. Ejecutar notebook
   
El notebook está documentado para reproducir todo el flujo de limpieza y preprocesado,
desde la carga de datos hasta la exportación del dataset final.

``` python 
   jupyter notebook Entregable_2_Churn.ipynb
```
---
## Licencia

Este proyecto está licenciado bajo la [Licencia Apache-2.0](LICENSE).  
Consulta el archivo LICENSE para más detalles o visita la [descripción oficial de la licencia Apache]( http://www.apache.org/licenses/).

---
  ## 👤 **Autoría**
  
  Miguel Ángel García León
  
  📧 miiguelleon@gmail.com
  
  🔗 [LinkedIn](https://www.linkedin.com/in/miguel-%C3%A1ngel-garc%C3%ADa-le%C3%B3n/)


