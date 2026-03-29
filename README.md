# Tablero-de-Control-Service-Desk

## 📊 Descripción del Proyecto

Este dashboard interactivo en Power BI proporciona un análisis integral del flujo de llamadas de un Service Desk, permitiendo monitorear la operación desde una perspectiva descriptiva (histórica) y predictiva (proyección a futuro).

El análisis se centra en la distribución de la demanda por Queues y el desempeño operativo de los agentes, utilizando datos desde agosto de 2024 hasta enero de 2025.

**Nota sobre Confidencialidad: Toda la información sensible, incluyendo nombres de agentes y colas de servicio, ha sido enmascarada para proteger la privacidad de los datos.**

## 🛠️ Secciones y Funcionalidades

### 1. Análisis Descriptivo de Demanda
- Llamadas por Día: Gráfico de líneas que muestra las variaciones diarias en el volumen de llamadas para detectar patrones de estacionalidad.
- Volumen por Estatus: Desglose crítico de la operación en tres categorías principales:
   - Answered: 20.07K llamadas (62.14%).
   - Voice Mail/Callback: 10.83K llamadas (33.53%).
   - Abandoned: 1.4K llamadas (4.32%).
     
### 2. Mapa de Calor (Heatmap)
 - Average Call Volume by Hour and Day: Matriz térmica que identifica las horas pico de atención (de 00 a 23 hrs) distribuidas por los siete días de la semana.
 - Facilita la identificación de ventanas de tiempo con mayor carga operativa para optimizar el staff.
   
### 3. Matriz de Desempeño por Agente y Queue
- Tabla detallada que cruza el rendimiento de los agentes con las colas asignadas, midiendo tiempos promedio de:
  - Talk Time: Tiempo de conversación efectiva.
  - Handle Time: Tiempo total de gestión.
  - AfterCallWork Time: Tiempo administrativo post-llamada.
  - Queue Wait Time: Tiempo de espera del usuario en cola.
    
### 4. Predictive Assessment (Forecasting)
- Pronóstico de Demanda: Análisis predictivo con un horizonte de 20 días (del 23 de enero al 16 de febrero de 2025).
- Filtros Predictivos: Permite ajustar la visualización de la predicción seleccionando colas específicas o estatus de llamada (Answered, Abandoned, Voice Mail).

## 🧰 Ficha Técnica

- Herramienta: Power BI.
- Resolución de Datos: Diaria y Horaria.
- Alcance Temporal: 6 meses de histórico + 20 días de predicción.
