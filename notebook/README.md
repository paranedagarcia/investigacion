# PREDICCIÓN TEMPRANA DE DIABETES MELLITUS TIPO 2

## 1. Introducción al Área de Investigación
La diabetes mellitus tipo 2 se ha convertido en una epidemia global, afectando a más de 463 millones de personas en todo el mundo según la Federación Internacional de Diabetes. Esta enfermedad metabólica crónica se caracteriza por niveles elevados de glucosa en sangre, resultando en resistencia a la insulina o producción insuficiente de esta hormona.

La detección temprana es crucial para:

- Prevenir complicaciones graves (nefropatía, retinopatía, neuropatía)

- Reducir costos de atención médica

- Mejorar la calidad de vida de los pacientes

Los modelos predictivos basados en machine learning ofrecen una oportunidad única para identificar pacientes en riesgo antes de que desarrollen síntomas clínicos evidentes, permitiendo intervenciones preventivas oportunas.

## 2. Planteamiento del Problema
Actualmente, el diagnóstico de diabetes tipo 2 suele realizarse cuando los pacientes ya presentan síntomas avanzados o complicaciones. Las pruebas tradicionales como la glucosa en ayunas o la hemoglobina glicosilada (**HbA1c**) requieren intervención médica y pueden no estar disponibles en poblaciones con acceso limitado a servicios de salud.

**Pregunta de investigación**: ¿Es posible desarrollar un modelo predictivo preciso que, utilizando variables clínicas y demográficas de fácil obtención, pueda identificar individuos con alto riesgo de desarrollar diabetes tipo 2?

## 3. Hipótesis
**Hipótesis nula (H0)**: No existe una combinación significativa de variables clínicas y demográficas que permita predecir la presencia de diabetes con una precisión superior al 75%.

**Hipótesis alternativa (H1)**: Las variables como edad, índice de masa corporal (IMC), antecedentes familiares, presión arterial y niveles de actividad física tienen poder predictivo significativo para identificar individuos con diabetes, logrando una precisión superior al 85%.

## 4. Objetivos
### Objetivo General
Desarrollar e implementar un modelo de machine learning para la predicción temprana de diabetes tipo 2 utilizando variables clínicas y demográficas.

### Objetivos Específicos
- Generar un dataset sintético que represente fielmente las características de pacientes con y sin diabetes

- Realizar un análisis exploratorio de datos (EDA) para identificar patrones y correlaciones

- Implementar y comparar diferentes algoritmos de clasificación

- Evaluar el rendimiento de los modelos mediante métricas apropiadas

- Seleccionar el modelo óptimo para la predicción de diabetes

## Variables

La hemoglobina glicosilada (**HbA1c**) es un examen de sangre crucial que mide el nivel promedio de glucosa en sangre de los últimos 2 a 3 meses. Se utiliza para diagnosticar la prediabetes (5,7%-6,4%) y la diabetes (6,5% o más), siendo la meta para la mayoría de diabéticos un valor inferior al 7%.

Detalles clave sobre la prueba HbA1c:
- Funcionamiento: Mide qué porcentaje de hemoglobina (proteína en los glóbulos rojos) está recubierto de azúcar (glucosa).
- Rango Normal: Menor al 5,7%.
- Prediabetes: 5,7% a 6,4%.
- Diabetes: 6,5% o superior.
- Monitoreo: Se recomienda realizarla cada 3 a 4 meses si no se han alcanzado los niveles de glucosa óptimos o se ha cambiado el tratamiento, o al menos dos veces al año.
- Preparación: Generalmente no requiere ayuno, aunque puede variar según las indicaciones médicas. 

Interpretación de resultados:
- < 5,7%: Saludable.
- 5,7% - 6,4%: Riesgo de prediabetes.

- = 6,5% o superior: Diagnóstico de diabetes tipo 2. 

La prueba es superior a la medición diaria de glucosa para evaluar el riesgo de complicaciones crónicas de la diabetes.

> Por regla general se utilizan conjuntos de datos (dataset) obtenidos desde las fuentes. En este caso se crearon datos artificiales (sintéticos) para analizar.