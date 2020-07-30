# CANTEMIST 

_El objetivo de este proyecto es encontrar términos médicos dentro de un set de documentos de texto médicos, indexarlos y clasificarlos con código ICD-O-3._

## Comenzando 🚀

_Sólo necesitas ejecutar las funciones contenidas en CANTEMIST EDA.ipynb en el orden en que se presentan. Asegurate de que el path al set de entrenamiento y al set de prueba están correctos. El modelo se ha entrenado utilizando datos proveídos por CANTEMIST, se utilizaron los sets de train y dev1 para entrenar al modelo originalmente._

Mira traindf.txt para ver el set de términos médicos que se van a buscar en el texto médico y su respectivo código ICD-O-3 (set de entrenamiento). Esta lista puede ampliarse en cualquier momento para mejorar los resultados de la predicción.


### Pre-requisitos 📋

python3 anaconda distribution ó 
python3 + las librerías pertinentes (numpy, pandas, io, etc.)


## Ejecutando las pruebas ⚙️

_Dentro del archivo CANTEMIST EDA.ipynb se presentan 7 funciones. Las primeras 5 se enfocan en explorar documentos de entrenamiento y crear el set de entrenamiento. La función 6 busca los términos contenidos en el set de entrenamiento dentro de una carpeta con textos médicos, indexa su posición y asigna la clave ICD-O-3 correspondiente. La función 7 guarda los resultados encontrados en los formatos brat requeridos para las tareas de NER y NORM. Función 7 también escribe coding.tsv y traindf.txt _


## Versionado 📌

Versionado en Git+Github. Código disponible en [este repositorio](https://github.com/BigByteMX/CANTEMISTchallenge).

## Autores ✒️

_Menciona a todos aquellos que ayudaron a levantar el proyecto desde sus inicios_

* **Jesús Martínez** - *Trabajo Inicial* - [BigByteMX](https://github.com/BigByteMX)

