📊 Skill Demand Predictor
Sector de Negocio

Future of Work

Necesidad del Cliente

Instituciones y empresas necesitan anticipar qué habilidades serán más demandadas para planificar formación.

🎯 Objetivo

Desarrollar un modelo de predicción de demanda futura de habilidades laborales, combinando datos de vacantes, tendencias del mercado y evolución tecnológica, con el fin de ayudar a instituciones educativas y empresas a anticipar necesidades de formación y reconversión profesional.

✅ Requerimientos funcionales

1. Recopilación y preparación de datos

Reunir datasets públicos o simulados con información de vacantes laborales, roles, industrias y tecnologías mencionadas.
Normalizar y limpiar textos de descripciones de puestos (eliminar duplicados, caracteres especiales, etc.).
2. Extracción y categorización de habilidades

Identificar habilidades técnicas y blandas mencionadas en las ofertas.
Clasificar habilidades por categoría (ej. programación, diseño, comunicación, liderazgo, etc.).
3. Análisis de tendencias históricas

Calcular la frecuencia de aparición de cada habilidad por trimestre o año.
Visualizar aumentos o caídas en la demanda.
4. Predicción de demanda

Entrenar un modelo de series temporales o regresión que estime la demanda futura de cada habilidad.
Incluir métricas de validación (RMSE, MAPE, etc.).
5. Identificación de habilidades emergentes

Detectar habilidades nuevas con crecimiento acelerado.
Generar alertas o recomendaciones basadas en el comportamiento reciente.
6. Visualización y comunicación de resultados

Dashboard que muestre tendencias de habilidades por industria, nivel y país.
Gráficos comparativos entre habilidades en auge y en declive.
⚙️ Requerimientos técnicos

Dataset simulado o público: por ejemplo, datos de portales de empleo, LinkedIn, o agregadores de vacantes.
Preprocesamiento de texto: tokenización, extracción de n-gramas, lematización o embeddings.
Modelado: uso de algoritmos de predicción de series o análisis de frecuencia temporal.
Evaluación: validación cruzada y comparación de modelos.
Interpretabilidad: explicación clara de qué variables y patrones determinan la demanda.
Exportabilidad: tablas o visualizaciones exportables (CSV/JSON).
📦 Entregables esperados

Documento de entendimiento del problema y fuentes de datos.
Pipeline de preprocesamiento y extracción de habilidades.
Análisis exploratorio con visualizaciones de tendencias históricas.
Modelo predictivo documentado con resultados y métricas.
Dashboard o informe visual de tendencias futuras por industria y tipo de habilidad.
