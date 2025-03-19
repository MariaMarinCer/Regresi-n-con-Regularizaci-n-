# Regresión-con-Regularización-
Este repositorio contiene el trabajo de evaluación sobre regresión con regularización incluyendo el análisis de multicolinealidad y la aplicación de técnicas de regularización como Ridge y Elastic Net.

# Contenido

 1.Carga de Datos: Lectura y procesamiento de los datos desde un archivo CSV.

2.Análisis de Multicolinealidad: Construcción de un modelo de regresión múltiple y cálculo de la matriz de correlación y el factor de inflación de la varianza (VIF).

3.Regularización: Implementación de Ridge y Elastic Net para mejorar la interpretabilidad del modelo.

4.Comparación de Modelos: Evaluación de los resultados obtenidos con los diferentes modelos.

# Requisitos

Para ejecutar el código en R, se necesitan las siguientes librerías:

```
install.packages("readr")
install.packages("usdm")
install.packages("glmnet")
install.packages("corrplot")
```
# Uso

Cargar los datos en R usando `read.csv.`

Ejecutar el análisis de regresión múltiple y evaluar la multicolinealidad.

Aplicar la técnica de regularización Elastic Net y seleccionar los mejores hiperparámetros.

Comparar los resultados y seleccionar el mejor modelo.

# Autor

María Marín Cerdá
