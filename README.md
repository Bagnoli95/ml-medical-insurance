# ml-medical-insurance
El dataset de costos médicos personales contiene información sobre varios factores que afectan los costos de seguros médicos, como la edad, el sexo, el índice de masa corporal, y el hábito de fumar.

# Pasos para correr la aplicación en local
En el local, ubicarse en el directorio donde desee descargar el proyecto.
```
git init
git clone https://github.com/Bagnoli95/ml-medical-insurance.git
cd ml-clasificacion-vinos
```

# Como ejecutar el código:
- Abrir el archivo ml-medical-insurance.ipynb
- Ejecutar el secuencialmente los bloques de código

# Recorrido del código
- Importamos el dataset a utilizar y lo exploramos.
- Imputamos los valores nulos, completamos con las medias de las columnas.
- Exploramos los datos visualemnte para ver la correlatividad de los valores.
- Eliminamos las columnas que tienen mucha correlatividad.
- Cambiamos los valores categoricos por binarios.
- Entrenamos 3 modelos:
    - LogisticRegression
    - KNeighborsClassifier
    - RandomForestClassifier
- Comparamos los resultados de los modelos para quedarnos con el mejor resultado
- Verificamos las estadisticas del modelo ganador.


# Autor:
Arturo Sosa

# Licencia:
(SLCM) Sientase Libre de Clonar y Mejorar el código.