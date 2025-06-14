# Predicción de Ataques Cardíacos en India

# Resumen Ejecutivo
Este informe presenta un análisis detallado del riesgo de ataques cardíacos en una población en India, basado en un conjunto de datos médicos. Se utilizan técnicas de análisis exploratorio y modelos de Machine Learning para entender los factores de riesgo y predecir eventos cardíacos. 

# Análisis de Datos
El objetivo de este análisis es comprender los factores que influyen en el riesgo de ataques cardíacos en India mediante el estudio de una base de datos médica. La audiencia beneficiada incluye profesionales de la salud, investigadores en epidemiología, aseguradoras médicas y responsables de políticas públicas en salud.

## Resumen de Metadata  
Se procesaron 5000 registros con 12 variables clínicas. Se eliminaron duplicados, se imputaron valores nulos y se categorizaron edades en grupos. También se creó una variable binaria llamada Heart_Risk que representa la presencia de factores críticos como colesterol alto y presión elevada.

## Preguntas/Hipótesis  
1. ¿Cuáles son las variables con mayor correlación con el riesgo de ataque cardíaco?
2.	¿Existe una relación entre la edad y el colesterol?
3.	¿Los niveles de presión arterial afectan significativamente el riesgo de enfermedad cardíaca?
4.	¿Cómo se distribuye el riesgo cardíaco según el género y otras condiciones médicas?
5.	¿Se puede predecir el riesgo cardíaco utilizando un modelo de regresión logística?

 
## Insights  
Los hallazgos clave incluyen:  
- **Se identificó una correlación significativa entre la presión arterial y el riesgo de ataque cardíaco.**
- **La edad es un factor determinante del colesterol ni del riesgo de ataque cardíaco ( Mayor frecuencia entre los 30 y 50 años).**
- **Se recomienda analizar factores como presión arterial, índice de masa corporal (IMC), por el consumo de cigarro.**
- **Los hombres presentan una incidencia ligeramente mayor de ataques cardíacos en comparación con las mujeres según los datos analizados.**
- **El modelo de regresión logística logró una precisión del 90% en la predicción del riesgo cardíaco.**

Este análisis proporciona información valiosa para la prevención y diagnóstico temprano de enfermedades cardíacas en la población.

## Análisis Exploratorio de Datos (EDA)
Se realizaron diversos gráficos como matriz de correlación, histogramas, gráficos de caja, dispersión y tortas para entender mejor la distribución y relaciones entre variables. Las observaciones clave incluyen:
- El colesterol alto se presenta en todas las edades.
- La presión sistólica muestra cierta asociación con el riesgo cardíaco.
- El tabaquismo, la edad y el género también tienen peso en el riesgo estimado.

## Entrenamiento y Evaluación de Modelos
Se entrenaron tres modelos de clasificación supervisada:
- Regresión Logística
- Random Forest
- XGBoost

Todos los modelos fueron evaluados usando métricas como Accuracy, Precision, Recall, F1 Score y AUC ROC.
La curva ROC múltiple mostró que XGBoost tuvo el mejor rendimiento con un AUC de 95.21%, seguido de Random Forest y Regresión Logística.

## Predicción de Nuevos Pacientes
Se evaluó un nuevo paciente con los siguientes datos (Edad: 55, Presión Sistólica: 145, Colesterol: 230):
- El modelo XGBoost predijo un riesgo cardíaco con una probabilidad de 99.99%.
- El modelo Random Forest también indicó riesgo con una probabilidad de 100%.

##Conclusiones Finales
Este análisis permitió identificar patrones de riesgo cardíaco y construir modelos predictivos confiables.
- XGBoost fue el modelo con mejor desempeño.
- La presión arterial y el colesterol son los factores más relevantes.
- El análisis puede utilizarse como herramienta de apoyo para la detección temprana de enfermedades cardíacas.
Se recomienda aplicar esta metodología a otros contextos regionales para ampliar su alcance predictivo.


## Herramientas utilizadas  
- Python Colab
- Pandas  
- Seaborn  
- Matplotlib  
- Scikit-Learn  

## Cómo ejecutar el código  
Google Colab:
[actividad_práctica_AlgoritmoML_MVP_Luida_Medina](https://drive.google.com/drive/folders/1JQbzJ8VsTD99xv1vQptUwu8pQ739BvMR?usp=drive_link)
