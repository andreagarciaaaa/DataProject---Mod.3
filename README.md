# DataProject---Mod.3
# Descripción del proyecto 
Este proyecto se basa en el análisis de datos clínicos relacionados con la diabetes. El objetivo del mismo es realizar un dashboard interactivo que permita identificar un perfil diabético con variables demográficas y determinar los puntos de riesgo de la aparición de diabetes en los pacientes de la muestra extraída. 
# Estructura del Excel para entender el proyecto
- **Datos originales (Raw_Data)** Esta hoja del excel incluye los datos importados del archivo .csv con información demográfica y clínica (edad, género, raza, hipertensión, enfermedades cardíacas...) junto con notas realizadas por los médicos que han atendido a los pacientes de la muestra.
- **Transformación y Limpieza** Esta hoja del excel está dedicada al tratamiento de los datos. En ella he etandarizado las categorías, he convertido las variables dicotómicas en texto legible y he creado nuevas columnas que fusionan la información de raza mediante PowerQuery (Despivotando)
- **Análisis descriptivo** Mediante el uso de las tablas dinámicas del excel se pueden identificar:
   - Número de pacientes con y sin pacientes
   - Distribución de los factores de riesgo
   - Correlación entre las variables de riesgo y la aparición de diabetes
   - Comparaciones entre grupos demográficos
- **Dashboard** Se ha realizado un Dashboard Visual para la presentación de los resultados obtenidos en el Analisis descriptivo.
# Instalación y requisitos
Este proyecto ha sido desarrollado en Excel y puede ser visualizado con una versión de Excel 2016 o superior. 
# Resultados y Conclusiones
En la muestra analizada se han identificado un total de 8500 pacientes diagnosticados con diabetes. Los resultados han sido organizados de forma demográfica y clínica o médica. De esta forma, se pueden identificar los factores clínicos de riesgo para el desarrollo de la diabetes y el perfil de aquellos pacientes que han sido diagnosticado con ella. 

-  **Demográficas**
  
 - La edad media de los pacientes con diabetes es de 61 años
 - El sexo más afectado por la diabetes en la muestra es el masculino. Se presenta un 52.4% de hombres con diabetes frente a un 47.5% en mujeres.
 - El área o estado donde se encuentran mayor número de diabeticos es Delaware (200 pacientes afectados)
 - La raza más afectada con mayor número de diabéticos es la Afroamericana. 
 
 - **Clínicas/Médicas**
   
 De forma general, los pacientes con diabetes de media presentaban las siguientes métricas:
 - El nivel medio de glucosa en sangre era de 194.1mg/dl. Este nivel es considerado alto en términos médicos. 
 - El nivel medio de hbA1c (hemoglobina) es de 6.93%. A partir del 6.5% de hemoglobina el nivel es considerado peligroso. 
 - La puntuación media del índice de masa corporal es de 31.99. En la escala del IMC esto es condierado Obesidad. 
Estas tres variables presentan altos niveles medios por lo que se puede interpretar que mantener estas condiciones médicas favorece a la aparición de diabetes, considerandose éstas como factores de riesgo. 
Ante estos números, se ha estudiado la correlación que existe entre estos tres factores y la diabetes. La correlación entre el peso y la diabetes era del 20%, siento este poco significativo para determinarla como factor de riesgo. Sin embargo, al estudiar la correlación entre los niveles de glucosa en sangre y la hemoglobina (hbA1c) presenta un 42% y un 40% respectivamente. Es decir, podemos establecer que tener altos niveles de estas dos variables en pacientes de la muestra pueden resultar en diagnosticos con diabetes. 
Por último, se ha estudiado otras variables clínicas y de estilo de vida como el historial fumador y de enfermedades cardiacas. Sin embargo, los resultados no han sido significativos:
- Sólo el 11% del total de diabeticos de la muestra es fumador o lo ha sido a lo largo de su vida
- Sólo el 14.91% del total de diabeticos de la muestra presenta problemas cardíacos. 
Con estos datos se puede interpretar que estas variables influirán poco a la hora de desarrollar diabetes. Por tanto, no las consideraría factores de alto riesgo en comparación con los niveles de glucosa y hemoglobina. 
# Próximos pasos 
Con el análisis actual se puede extraer una buena base para la comprensión de los datos clínicos. No obstante, siempre se pueden implementar mejoras o proponer ampliaciones en el análisis de este proyecto:

- Desarrollar modelos predictivos básicos para estimar la probabilidad de la aparición de diabetes
- Estudiar la evolución de los pacientes con y sin diabetes en el tiempo
- Incorporar más variables adicionales de estilo de vida (actividad física, dieta..), geograficas y socioeconomicas para poder realizar un análisis más contextualizado. 
- Configurar actualizaciones automáticas para incorporar nuevas fuentes de datos.
# Contribuciones
Toda contribución es bienvenida y agradecida. Si deseas mejorar el proyecto, puedes desarrollar cambios en una nueva rama o abrir un pull request con tus mejoras.
# Autores 
- Andrea García
- https://github.com/andreagarciaaaa 
