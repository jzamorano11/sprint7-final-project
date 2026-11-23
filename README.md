# sprint7-final-project
Análisis de una empresa de telecomunicaciones 

## Objetivo del proyecto
El objetivo del proyecto es identificar patrones de uso, detectar comportamientos atípicos y comprender qué segmentos de clientes muestran necesidades diferenciadas, con el fin de optimizar la oferta comercial y mejorar la experiencia del usuario.

## Datasets utilizados 
1. plans.csv: Catálogo de planes con sus precios y beneficios.
2. users_latam.csv: Información de cada usuario (datos personales, plan, fecha de registro, churn). 
3. usage.csv: Actividad generada por los usuarios: llamadas, mensajes, duración, longitud.

## Etapas del análisis
1. Cargar y explorar
2. Identificación de problemas de calidad de datos
3. Limpieza básica de datos
4. Summary statistics de uso por usuario
5. Visualización de distribuciones (uso y clientes) y outliers
6. Segmentación de Clientes
7. Insight Ejecutivo para Stakeholders

## Como ejecutar el Notebook
1. Abre Google Colab (colab.research.google.com).
2. Sube el archivo .ipynb de tu notebook (o ábrelo directamente desde GitHub con el botón "Open in Colab").
3. Asegúrate de tener los datasets (plans.csv, users_latam.csv, usage.csv) disponibles, ya sea subiéndolos a Colab o montando tu Google Drive.
4. Ejecuta las celdas en orden, de arriba hacia abajo.

## Guía de reproducción
1. Clona este repositorio: 'https://github.com/jzamorano11/sprint7-final-project.git
2. Importa las librerías: 'pandas','seaborn' y 'matplotlib.pyplot'
3. Coloca los archivos 'plans.csv','users_latam.csv'y 'usage.csv' en la carpeta 'datasets/'
4. Abre 'sprint7-final-project' y ejecuta todas las celdas
