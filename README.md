<div align="center">

# Telco Customer Churn Analysis
### Estrategia de Retención basada en Datos

![MySQL](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)
![Power Bi](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

</div>

---

##  Business Case

Una empresa de telecomunicaciones enfrenta una tasa de deserción (Churn) crítica del **26.5%**, impactando directamente en el *Revenue*. El objetivo de este proyecto no es solo predecir quién se va, sino diagnosticar la causa raíz técnica y comercial para frenar la fuga de capital.

**Rol:** Analista de Datos & Estrategia  
**Alcance:** Auditoría de Datos, Análisis SQL, Dashboard Ejecutivo.

---

##  Tech Stack & Metodología

* **MySQL Workbench:** Ingesta de datos, validación de integridad (Data Quality) y segmentación avanzada con lógica de negocio.
* **Power BI:** Modelado de datos (DAX Measures) y diseño de Dashboard interactivo para Storytelling.
* **Microsoft Excel:** Limpieza preliminar y tratamiento de valores nulos (Data Cleaning).

---

## Executive Summary
Tras analizar +7,000 registros de clientes, se identificaron 3 patrones críticos que explican la fuga:
1. El "Pain Point" Tecnológico
Insight: La tecnología no garantiza fidelidad. Los usuarios de Fibra Óptica presentan una tasa de deserción del 41.9%, duplicando la tasa de los usuarios de DSL (19%). Esto rompe la hipótesis de que "mejor tecnología = cliente más feliz" y apunta a fallas en el servicio técnico o estabilidad de la red.

2. La Trampa Contractual
Insight: Riesgo masivo en el corto plazo. El 42.7% de los usuarios con contratos mensuales (Month-to-month) abandonan el servicio. En contraste, los contratos de 2 años tienen una retención del 97.2%.

3. Análisis de Sensibilidad al Precio
Insight: El precio NO es la causa raíz. Un análisis financiero reveló que los clientes de Fibra que cancelaron el servicio pagaban en promedio $5.81 USD menos que los que se quedaron.

Conclusión: Los clientes se van insatisfechos con el producto, no con el precio. Bajar precios no solucionará el problema.
<img width="1256" height="746" alt="image" src="https://github.com/user-attachments/assets/36fe1ad6-11c7-4bfb-bd5b-5923652de08c" />

## Recomendaciones Estratégicas
1. Auditoría Técnica: Iniciar revisión de tickets de soporte en el segmento de Fibra Óptica para aislar fallas de red recurrentes.

2. Campaña de Migración: Crear incentivos agresivos (no descuentos, sino upgrades de velocidad) para mover clientes "Month-to-month" a contratos anuales.

3. Programa de Onboarding: Implementar seguimiento proactivo en los primeros 3 meses para nuevos usuarios de Fibra, periodo donde ocurre la mayor deserción.



