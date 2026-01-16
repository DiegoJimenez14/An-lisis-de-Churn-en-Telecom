# Análisis de Retención de Clientes (Telco Churn)

## 📌 Contexto del Proyecto
En el competitivo sector de las telecomunicaciones, la retención de clientes es más rentable que la adquisición. Este proyecto analiza el comportamiento de los clientes para identificar patrones de deserción (Churn) y proponer estrategias de retención.

## 🎯 Objetivos
1. Identificar los factores clave que provocan la cancelación del servicio.
2. Crear un dashboard interactivo para visualizar el riesgo de fuga.
3. Proponer recomendaciones basadas en datos para reducir la tasa de churn.

## 🛠 Herramientas Utilizadas
* **Excel:** Limpieza de datos y análisis exploratorio inicial.
* **SQL:** Consultas para segmentación y validación de hipótesis.
* **Power BI:** Visualización y Storytelling.

## 🔍 Hallazgos Clave del Análisis SQL

Tras auditar la base de datos de clientes, se detectaron los siguientes patrones críticos:

1. **Tasa de Fuga General:** El 26.5% de la base de clientes ha abandonado la compañía.
2. **Foco Rojo en Fibra Óptica:** Los usuarios de Fibra Óptica presentan una tasa de deserción del **41.9%**, mucho mayor que la de DSL (19%).
3. **Modalidad de Contrato:** El problema se concentra en contratos mensuales ("Month-to-month") con una fuga del **42.7%**.
4. **Descarte de Precio:** El análisis financiero reveló que los clientes fugados de fibra pagaban en promedio **$5.81 USD menos** que los clientes leales. Esto sugiere que la fuga no es por sensibilidad al precio, sino por insatisfacción con la calidad del servicio.

**Recomendación Preliminar:** Investigar urgentemente los tickets de soporte técnico en el segmento de Fibra Óptica para identificar fallas recurrentes.
