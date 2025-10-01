📞 Predicción de cancelación de clientes – Interconnect

📌 Propósito del proyecto

Desarrollar un modelo predictivo que permita anticipar la cancelación de clientes en la empresa de telecomunicaciones Interconnect, con el fin de activar estrategias de retención como promociones y planes especiales.

📝 Descripción

Interconnect ofrece servicios de telefonía fija, internet (DSL y fibra óptica), seguridad digital, soporte técnico, almacenamiento en la nube y streaming. El equipo de marketing busca identificar clientes en riesgo de cancelar sus contratos, utilizando datos personales, de servicio y de facturación. El proyecto incluye preprocesamiento, análisis exploratorio, entrenamiento de modelos y evaluación con métricas clave.

💻 Funcionalidades

🧹 Preprocesamiento de datos

• 	Codificación de variables categóricas.

• 	Escalado y normalización.

• 	Imputación de valores faltantes.

• 	Control de calidad y trazabilidad.

📊 Análisis exploratorio

• 	Visualización de distribuciones y correlaciones.

• 	Detección y tratamiento de outliers.

• 	Identificación de variables relevantes.

🧠 Entrenamiento de modelos

• 	Comparación de algoritmos: Logistic Regression, Random Forest, CatBoost.

• 	Validación cruzada y ajuste de hiperparámetros.

• 	Encapsulamiento en Pipelines para evitar fuga de información.

📈 Evaluación y visualización

• 	Métricas clave: Accuracy, F1 Score, AUC-ROC.

• 	Gráficos comparativos para facilitar interpretación.

• 	Documentación reflexiva y storytelling técnico.

🔧 Herramientas utilizadas

• 	Python

• 	Pandas

• 	Scikit-learn

• 	CatBoost

• 	Matplotlib

• 	Seaborn

📊 Resultados

• 	Modelo final seleccionado: CatBoost

• 	Accuracy: 0.8055

• 	F1 Score: 0.5848

• 	AUC-ROC: 0.8407

Aunque Logistic Regression obtuvo el mayor AUC-ROC (0.8446), CatBoost mostró mejor balance entre métricas y mayor estabilidad en validación cruzada, convirtiéndose en la solución más robusta.

✅ Conclusiones

El modelo CatBoost permite anticipar cancelaciones con alta precisión, facilitando la activación de estrategias de retención. La trazabilidad del pipeline, la validación rigurosa y la visualización comparativa fueron claves para el éxito del proyecto. Se recomienda implementar el modelo en producción con monitoreo continuo y retroalimentación del equipo de marketing.

🌱 Reflexión personal

Este proyecto consolidó buenas prácticas en ciencia de datos, fortaleció la autocrítica y permitió evolucionar como profesional reflexivo. La gestión emocional, la apertura al feedback y la estructura clara fueron fundamentales para mantener el enfoque y convertir cada revisión en una oportunidad de crecimiento.
