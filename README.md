# Predicción de tasas de interés y segmentación de clientes

## Descripción
Este proyecto tiene como objetivo predecir la tasa de interés asignada a cada cliente en función de características individuales, así como segmentar a los clientes para apoyar decisiones estratégicas en campañas de marketing y evaluación de riesgo crediticio.
Se trabajó con un conjunto de datos que incluye información financiera y de comportamiento de los clientes. Para la predicción de la tasa de interés, se aplicaron modelos de regresión. Paralelamente, se implementó un proceso de segmentación con técnicas de clustering, específicamente K-Means, con el objetivo de identificar grupos de clientes con características similares.
El análisis de los segmentos facilitó la justificación estratégica de acciones diferenciadas para cada grupo, tanto en términos de campañas dirigidas como de políticas de riesgo. Las visualizaciones generadas ayudaron a interpretar patrones clave y a proponer recomendaciones orientadas a maximizar la rentabilidad y minimizar la exposición al riesgo financiero.

## Dataset
El dataset utilizado contiene información financiera y de comportamiento de clientes. Incluye variables como ingresos, historial de crédito, frecuencia de pagos, entre otras.

- **Origen:** 
- **Número de registros:** 
- **Variables principales:** Ingresos, pagos, tasas de interés, frecuencia de compra, etc.

## Metodología

1. **Análisis exploratorio de datos (EDA)**  
   Se identificaron patrones clave y relaciones entre variables.  

2. **Limpieza y transformación de datos**  
   Se manejaron valores nulos, se escalaron variables y se transformaron características relevantes.

3. **Modelado**  
   - **Regresión:**  
     - SVR  
     - Árboles de decisión  
     - Regresión lineal múltiple  


4. **Evaluación del modelo**  
   Se evaluaron las predicciones de la tasa de interés y la coherencia de los clusters.  

## Resultados
- Se logró modelar la tasa de interés con tres enfoques: SVR, árboles de decisión y regresión lineal múltiple.
- El análisis de clusters permitió segmentar a los clientes con base en patrones comunes, facilitando decisiones estratégicas en marketing y gestión de riesgo.
- Se obtuvo una estimación de la probabilidad de cumplimiento de cada cliente.

## Lecciones aprendidas
- La combinación de técnicas supervisadas y no supervisadas puede aportar valor estratégico a los negocios.
- La visualización adecuada facilita la interpretación de patrones y la toma de decisiones.
- La elección del modelo debe balancear precisión y capacidad de interpretación.

## Tecnologías
Scikit-learn, Pandas, Numpy, Matplotlib, Seaborn

## Mejoras futuras
- Profundizar en los datos para reformular el problema como clasificación: predecir si un cliente pagará o no.
- Comparar el rendimiento de la regresión lineal múltiple con descenso del gradiente.
- Implementar validación cruzada para robustecer las evaluaciones.
- Organizar el flujo de trabajo con pipelines.
