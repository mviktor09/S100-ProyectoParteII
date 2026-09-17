# S100-ProyectoParteII
Predicción de Readmisión Hospitalaria en Pacientes Diabéticos

Proyecto final de S100 - Introducción a la Ciencia de Datos, Maestría en Analítica de Datos, Universidad Tecnológica de Panamá.

Objetivo

Analizar datos de pacientes diabéticos y desarrollar modelos de clasificación que permitan identificar encuentros hospitalarios con riesgo de readmisión dentro de los 30 días posteriores al alta.

Datos

Se utiliza el conjunto Diabetes 130-US Hospitals for Years 1999-2008 del UCI Machine Learning Repository, que contiene 101,766 encuentros hospitalarios correspondientes a 71,518 pacientes.

La variable objetivo utilizada es readmit_30:

1: readmisión en menos de 30 días.
0: no hubo readmisión temprana.
Metodología

El proyecto incluye:

Análisis exploratorio de datos (EDA).
Limpieza y preparación de los datos.
Ingeniería de características.
Separación de entrenamiento y prueba agrupada por paciente.
Construcción de un modelo baseline.
Entrenamiento y comparación de modelos supervisados.
Evaluación mediante accuracy, precision, recall y F1-score.
Ejecución

El análisis y modelado se encuentran en el notebook del repositorio. Las dependencias utilizadas pueden instalarse con:

pip install pandas numpy matplotlib scikit-learn ucimlrepo

Luego, ejecutar el notebook de principio a fin.

Equipo 3

Darío Anguizola · Karina Correa · Ignacio Jiménez · Víctor Mendieta
