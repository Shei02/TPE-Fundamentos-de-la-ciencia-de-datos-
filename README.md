# Proyecto de Análisis de Calidad del Agua

## Descripción:
Este proyecto tiene como objetivo analizar diversos factores relacionados con la calidad del agua utilizando datos de mediciones como temperatura, turbidez, coliformes fecales, y otros indicadores de calidad. Se aplican técnicas de análisis de componentes principales (PCA), t-SNE y regresión para explorar las relaciones entre estos factores y su influencia en la calidad del agua, asi como tambien test parametricos y no parametricos que demuestran la validacion o no de las hipotesis que fueron surguiendo durante el recorrido de este proyecto.

## Índice
 1) Tecnologías utilizadas
 2) Instalación
 3) Estructura del proyecto
 4) Uso
 
### 1)Tecnologías utilizadas
Este proyecto se implementa utilizando las tecnologías y bibliotecas:

* Python 3.8+
* Pandas : Para la manipulación y análisis de datos.
* Matplotlib y Seaborn : Para la visualización de datos.
* Scikit-learn : Para el análisis de datos y modelado (PCA, t-SNE, etc.).
* Statsmodels : Para análisis estadístico y regresión.
* Entre otras.

### 2)Instalación
* 0- Instalarse la consola Git para completar los siguientes pasos
   https://git-scm.com/downloads
* 1- Abrir la consola Git y clonar el repositorio en una carpeta creada ya en su pc
   git clone https://github.com/Shei02/calidad_agua.git
   cd calidad_agua
* 2- Crear un entorno virtual y activarlo
  python -m venv env
  source env/bin/activate  # En Windows usa: env\Scripts\activate
* 3- Instale las dependencias necesarias
  pip install -r requirements.txt

### 3)Estructura del proyecto
calidad_agua/
├── data/                # Archivos de datos (CSV, etc.)
├── notebooks/            # Jupyter Notebooks con los análisis
├── src/                 # Código fuente del proyecto
│   ├── data_preprocessing.py  # Preprocesamiento de datos
│   ├── analysis.py      # Funciones de análisis de datos
├── README.md            # Este archivo
├── requirements.txt     # Dependencias del proyecto

### 4)Uso
Comezar con la ejecucion del codigo paso a paso, para ir descargando el archivo.
Luego ver como se realizo la limpiea del mismo.
Y asi hasta ver las hipotesis que fueron presentadas y la demostracion de las mismas.
