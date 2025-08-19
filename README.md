# NLP Text Analysis with SpaCy: *White Noise*

## Descripción del proyecto
Este proyecto realiza un análisis completo de texto utilizando Python y SpaCy. El objetivo es normalizar, procesar y visualizar datos textuales del libro *White Noise* de Don DeLillo, con un enfoque en:  

- **Normalización del texto:** limpieza de caracteres especiales, eliminación de números, stopwords y puntuación.  
- **Lematización:** reducción de palabras a su forma base.  
- **Análisis de frecuencia:** identificación de las palabras más comunes.  
- **Reconocimiento de entidades nombradas:** extracción de PERSON y LOC.  
- **Análisis de partes del discurso (POS):** frecuencia de etiquetas gramaticales.  
- **Visualización:** gráficos de barras y pie charts para representar la información de manera clara.

## Tecnologías utilizadas
- Python 3.x  
- [SpaCy](https://spacy.io/) (`en_core_web_md`)  
- Pandas  
- Matplotlib  
- Collections (Counter)  
- Re (expresiones regulares)  

## Uso
1. Clonar el repositorio:  

git clone https://github.com/tu_usuario/nombre_del_repositorio.git

## Instalar las dependencias:
pip install spacy pandas matplotlib
python -m spacy download en_core_web_md

## Ejecutar el script o notebook para generar:
- Texto normalizado y lematizado
- Análisis de frecuencia de palabras
- Extracción de entidades nombradas
- Visualizaciones de frecuencia y POS tags

## Visualizaciones incluidas
- Top 15 palabras más frecuentes (gráfico de barras)
- Frecuencia de entidades nombradas (gráfico de barras y pie chart)
- Distribución de POS tags (gráfico de barras)

## Resultados esperados
- Archivo whitenoise_lemmas.txt con el texto limpio y lematizado.
- CSV entities.csv con las entidades PERSON y LOC identificadas.
- Gráficos generados automáticamente mostrando la distribución de palabras, entidades y POS tags.
