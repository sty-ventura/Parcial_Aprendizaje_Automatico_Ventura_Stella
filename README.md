# Tecnicatura Superior en Ciencia de Datos e IA- Politénico Malvinas Argentinas- 2025
## Aprendizaje Automático
Profesor: Martin Mirabete- 
Alumna: Ventura Stella Maris
# Predicción de la evolución de los ingresos del sector privado registrado en Tierra del Fuego  

## Descripción del Proyecto  
Este proyecto aplica **Aprendizaje Automático** para analizar la evolución de los ingresos del sector privado registrado en **Tierra del Fuego**, una provincia con características económicas particulares.  

Dada la alta inflación y el impacto del costo de vida en la región, el objetivo es desarrollar un modelo predictivo que permita **estimar la remuneración promedio** y su relación con la **Canasta Básica Total (CBT) y el endeudamiento de los hogares**.

## 🎯 Objetivo del Análisis  
Desarrollar un **modelo de regresión supervisada** para predecir la evolución mensual de los ingresos del sector privado en Tierra del Fuego, evaluando su relación con el costo de vida y el nivel de endeudamiento.  

### **Objetivos específicos**  
✅ **Limpieza y transformación** de la serie histórica de ingresos según rama de actividad.  
✅ **Integración de datos complementarios** como CBT y deuda doméstica.  
✅ **Aplicación de modelos de regresión** (Regresión Lineal, Árboles de Decisión, Random Forest, XGBoost, MLPRegressor).  
✅ **Evaluación del modelo** con métricas como MAE, RMSE y R².  
✅ **Comparación entre ingresos y crecimiento de la CBT** para estimar la variación del poder adquisitivo.  

## 📂 Origen y Acceso al Dataset  
El dataset utilizado proviene de **fuentes públicas** como:  
- **Banco Central de la República Argentina (BCRA)** → Datos de pagos minoristas y crédito.  
- **IPIEC** → Información sobre ingresos del sector privado registrado.  
- **IPIEC** →  sobre inflación y evolución de precios.  

Se han realizado procesos de **limpieza y normalización** para estructurar las variables y facilitar su integración en el modelo de predicción.

## 🛠️ Tecnologías Utilizadas  
Este proyecto se desarrolla **exclusivamente en Python**, utilizando herramientas como:  
- **Pandas** para manipulación de datos.  
- **Matplotlib y Seaborn** para visualización de tendencias.  
- **Scikit-learn** para entrenamiento de modelos de Machine Learning.  
- **Git/GitHub** para gestión de versiones y documentación.  

## 📑 Estructura del Repositorio  
📁 datasets/               → Archivos de datos originales y versiones preprocesadas en .csv.
📁 notebooks/              → Código para análisis exploratorio y modelos en Python.
📁 reports/                → Documentos con hallazgos y visualizaciones.
📄 README.md               → Documentación del proyecto.

├── data/                  # Datos en distintos niveles de procesamiento  
│   ├── raw/               # Datos originales sin procesar  
│   ├── processed/         # Datos listos para entrenar  
│   └── interim/           # Datos intermedios  
│
├── docs/                  # Documentación del proyecto  
├── models/                # Modelos entrenados y serializados  
├── notebooks/             # Jupyter notebooks para análisis y entrenamiento  
├── references/            # Fuentes y artículos relacionados  
├── reports/               # Documentos y gráficos generados automáticamente  
├── src/                   # Código fuente del proyecto  
│   ├── data/              # Scripts para carga y limpieza de datos  
│   ├── features/          # Scripts de ingeniería de características  
│   ├── models/            # Entrenamiento y evaluación de modelos  
│   └── visualization/     # Funciones de gráficos y visualización  
│
├── .gitignore             # Archivos a excluir en Git  
├── LICENSE                # Licencia del proyecto  
├── README.md              # Documentación del proyecto  
└── requirements.txt       # Dependencias necesarias  
