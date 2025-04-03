# Predicción de Ataques Cardíacos en India
# Análisis de Datos

## Abstracto con motivación y audiencia  
El objetivo de este análisis es comprender los factores que influyen en el riesgo de ataques cardíacos en India mediante el estudio de una base de datos médica. La audiencia beneficiada incluye profesionales de la salud, investigadores en epidemiología, aseguradoras médicas y responsables de políticas públicas en salud.

## Resumen de Metadata  
El dataset contiene:  
- **Cantidad de filas**: 5000 registros
- **Cantidad de columnas**: 12 variables
- **Variables principales**: Edad, Presión Arterial Sistólica, Colesterol, Nivel de Triglicéridos, Estado de Diabetes, Género, entre otras.
- **Tipo de variables**: Numéricas y categóricas.

## Preguntas/Hipótesis  
1. ¿Cuáles son las variables con mayor correlación con el riesgo de ataque cardíaco?
2.	¿Existe una relación entre la edad y el colesterol?
3.	¿Los niveles de presión arterial afectan significativamente el riesgo de enfermedad cardíaca?
4.	¿Cómo se distribuye el riesgo cardíaco según el género y otras condiciones médicas?
5.	¿Se puede predecir el riesgo cardíaco utilizando un modelo de regresión logística?


## Visualizaciones ejecutivas  
A continuación, se presentan algunos gráficos clave generados durante el análisis:
1.	Matriz de Correlación
Se presenta una matriz de calor que muestra la relación entre las variables clave como edad, colesterol y presión arterial sistólica con el riesgo de ataque cardíaco.
### Matriz de Correlación  
![Matriz de Correlación](ruta/del/archivo.png)

3.	Distribución del Colesterol por Edad
Se muestran gráficos de cajas y violines para visualizar la distribución del colesterol en diferentes rangos de edad.
### Distribución de [Variable]  
![Distribución de Variable](ruta/del/archivo.png)  

4.	Comparación de Medias
Una tabla comparativa muestra el promedio de colesterol por categoría de edad.
5.	Modelo de Regresión Logística
Se presentan los coeficientes del modelo de regresión logística y su reporte de clasificación con medidas de precisión, recall y F1-score.
 
## Insights  
Los hallazgos clave incluyen:  
- **Se identificó una correlación significativa entre la presión arterial y el riesgo de ataque cardíaco.
-	**Los niveles elevados de colesterol están asociados con un mayor riesgo, especialmente en adultos mayores de 50 años.
- **Los hombres presentan una incidencia ligeramente mayor de ataques cardíacos en comparación con las mujeres según los datos analizados.
-	**El modelo de regresión logística logró una precisión del 85% en la predicción del riesgo cardíaco.


## Herramientas utilizadas  
- Python  Colab
- Pandas  
- Seaborn  
- Matplotlib  
- Scikit-Learn  

## Cómo ejecutar el código  
1. Ubicación del código:  
   ```bash
   Google Colab https://colab.research.google.com/drive/1fhtPpfYOmMrXAjBOt_-C7x5lZnPyjzZA?usp=sharing
