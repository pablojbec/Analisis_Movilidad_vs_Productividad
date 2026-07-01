# Análisis Movilidad Urbana vs Productividad
Este repositorio contiene el análisis realizado para entender la manera en que la movilidad urbana (niveles de congestión, tiempos de viaje, retrasos) se relaciona con la productividad económica (PIB per capita, desempleo) en las principales ciudades latinoamericanas del mundo durante el año 2024.

El dataset `tomtom_traffic` contiene datos de tráfico en tiempo real.

El dataset `oecd_city_economy` contiene la Indicadores económicos y ambientales por ciudad, recopilados por la Organización para la Cooperación y el Desarrollo Económico (OECD).



## 📂 Contenido del repositorio

- `/Analysis_TomTom.ipynb`
  → Notebook principal con limpieza, análisis de relaciones para visualizar patrones y conclusiones.
- →Links a datasets trabajados

## ▶️ Cómo ejecutar el notebook

Puedes ejecutar este notebook de las siguientes formas:

### Opción 1: Abrir en Google Colab
- Ve a Google Colab
- Haz clic en “File” > “Open notebook”
- Selecciona la pestaña “GitHub”
- Pega el enlace de este repositorio
- Abre el archivo .ipynb

### Opción 2: Ejecutar en local

- Clona este repositorio:
git clone [https://github.com/pablojbec/Analisis_Movilidad_vs_Productividad]
- Accede a la carpeta del proyecto:
- cd repositorio

- Abre Jupyter Notebook:
  - jupyter notebook
  - Selecciona el archivo .ipynb y ejecútalo

## 🔁 Guía de reproducción
Para reproducir los resultados:

- Instala las dependencias necesarias (recomendado usar entorno virtual o Anaconda):
pip install -r requirements.txt
- Asegúrate de tener los datos en la ruta correcta (ver carpeta /data si aplica)
- Ejecuta las celdas del notebook en orden, desde el inicio
- Verifica que no haya errores y que los outputs coincidan con los esperados

## 🧠 Objetivo del análisis

- Identificar problemas de calidad de datos
- Realizar la limpieza del datasets
- Analizar las relaciones entre la movilidad urbana y la productividad de las ciudades. 
- Identificar patrones que reflejen un régimen de productividad relacionado con retrasos en la movilidad urbana de ciudades de Latinoamérica.
- Generar insights para ayudar al American Development Bank a decidir en cuales ciudades se debería invertir en infraestructura de transporte.
-Proporcionar recomendaciones de acuerdo con el análisis realizado 

## 🧩Etapas de análisis realizadas

- Se realizó la limpieza y validación de los datos
- Se graficaron variables relevantes de los datasets para identificar una relación entre movilidad urbana y productividad (boxplots y diagramas de barras comparativos)
