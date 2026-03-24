# Optimización de Pozos Petroleros: Análisis de Beneficio y Riesgo

## 🎯 Objetivo del Proyecto
El objetivo principal es identificar la región óptima para la apertura de **200 nuevos pozos petroleros**, maximizando el beneficio esperado y minimizando el riesgo financiero. 

Para lograrlo, el proyecto se divide en tres fases críticas:
1. **Modelado Predictivo:** Entrenamiento de un modelo de **Regresión Lineal** para predecir el volumen de reservas en tres regiones distintas.
2. **Optimización de Selección:** Identificación de los 200 pozos con mayor potencial de producción en cada región.
3. **Análisis de Riesgo (Bootstrapping):** Evaluación de ganancias potenciales y cálculo de la probabilidad de pérdidas mediante simulaciones estadísticas.

## 🛠️ Herramientas y Tecnologías
* **Python**: Lenguaje principal.
* **Pandas & NumPy**: Manipulación y limpieza de datos.
* **Scikit-Learn**: Implementación del modelo de Regresión Lineal.
* **Bootstrapping**: Técnica estadística para la evaluación de incertidumbre y riesgo.

## 📊 Metodología
* **Preparación de datos:** Limpieza y exploración de los datasets regionales.
* **Entrenamiento:** Validación del modelo mediante el error cuadrático medio (RMSE).
* **Cálculo de Ganancias:** Definición de umbrales de rentabilidad y selección de los mejores puntos de extracción.
* **Simulación:** Ejecución de 1,000 iteraciones de bootstrapping para obtener el intervalo de confianza del 95%.

## 📈 Conclusiones Técnicas
*Sección para completar tras ejecutar tu notebook:*
* **Región recomendada:** [Insertar Región]
* **Beneficio promedio estimado:** [Insertar Valor]
* **Riesgo de pérdida:** [Insertar %]
