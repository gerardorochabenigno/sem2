# Tarea 3: Métodos de Gran Escala

En esta etapa del proyecto, este repo solo busca cumplir con la tarea 3 de la materia Métodos de Gran Escala. El objetivo es seguir incorporando material progresivamente para crear un producto de datos más robusto, desde el procesamiento de datos hasta su despliegue.

El repo contiene dos ramas: `main` y `dev`. Para la tarea 3, favor de revisar la rama `dev`

Se propone que se utilice información de [Predict Future Sales](https://www.kaggle.com/competitions/competitive-data-science-predict-future-sales), que contiene información de ventas diarias de la compañía de software rusa **1C Company**.

La estructura del repo es la siguiente

```
Semestre2/
│── notebooks/         # Notebooks del POC
│   ├── tarea2.ipynb
│── data/              # Datos crudos, preprocesados, para realizar inferencia y para realizar 
│   ├── raw/           # Datos para preprocesar y guardar en prep
│   ├── prep/          # Datos para entrenar el modelo
│   ├── inference/     # Datos para realizar inferencia con base en el modelo 
│   ├── predictions/   
│── src/               
│   ├── preprocessing.py  # Funciones para procesar datos
│   ├── training.py       # Funciones para entrenamiento
│   ├── inference.py      # Funciones para inferencia
│── prep.py            # Script principal para preparar datos de la carpeta data/raw
│── train.py           # Script principal para entrenar modelo
│── inference.py       # Script principal para hacer predicciones
│── model.joblib       # Modelo
│── README.md          # Documentación
│── requirements.txt   # Librerías a utilizar (basado en el yaml de de la clase -arquitectura-)
│── .gitignore         # Archivos que estaré trabajando pero que no quiero que sean públicos y datos (si bien los datos de entrenamiento son públicos, seguimos las mejores prácticas). 
│── .pylintrc          # Configuración de Pylint
```
