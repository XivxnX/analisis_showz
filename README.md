# 📊 Proyecto de Análisis de Marketing — Showz

Este proyecto analiza el comportamiento de los usuarios y la rentabilidad de las campañas de marketing de **Showz**, una empresa dedicada a la venta de entradas para eventos. El objetivo principal es optimizar el gasto publicitario mediante métricas clave que conectan el uso del servicio con el retorno financiero.

## 🎯 Propósito del Análisis

Mejorar la eficiencia del presupuesto de marketing respondiendo a preguntas como:

- ¿Cómo y cuándo compran los clientes?
- ¿Cuánto aporta cada cliente a la empresa (LTV)?
- ¿Cuándo se recupera la inversión en adquisición (ROMI)?
- ¿Qué fuentes de tráfico son más rentables?

## 📅 Periodo Analizado

Junio 2017 – Mayo 2018 (12 meses)

## 📌 Métricas Evaluadas

### Comportamiento del Usuario

- DAU, WAU, MAU
- Sesiones por día
- Duración promedio de sesión (ASL)
- Tasa de retención

### Conversión y Ventas

- Tiempo entre registro y primera compra
- Número de pedidos por periodo
- Tamaño promedio de compra
- LTV por cohorte

### Inversión y Rentabilidad

- Gasto total por fuente
- CAC por fuente
- ROMI por fuente
- Ratio LTV:CAC

## 📈 Hallazgos Clave

- La **Fuente 4** es la más rentable: bajo CAC, alto LTV y buena conversión. Se recomienda redirigir presupuesto desde la **Fuente 3**, que tiene un CAC más del doble y representa el 43 % del gasto.
- Un modelo proyectado muestra que invertir lo mismo en la Fuente 4 que en la Fuente 3 podría generar ingresos de 8, CAC de 7.88 y un ratio LTV:CAC de 66.7:1.
- Las **Fuentes 9 y 10** tienen bajo rendimiento. Eliminarlas podría ahorrar $11,339.98.
- El punto de equilibrio se alcanzaría en el segundo año si se mantiene el ritmo actual.
- La mayoría de los usuarios acceden desde computadora y sus sesiones duran ~60 segundos. Se recomienda revisar el embudo de producto y el mapa de scroll para mejorar la experiencia.

## 🔍 Recomendaciones Estratégicas

- Reasignar presupuesto de Fuente 3 a Fuente 4 (o Fuente 5 como alternativa).
- Eliminar Fuentes 9 y 10.
- Analizar eventos del último trimestre de 2017 (pico de actividad).
- Investigar promociones para cohortes de marzo, abril y mayo (alta conversión temprana).
- Evaluar beneficios otorgados a la cohorte de septiembre (aumento en LTV).

## 🧪 Herramientas y Tecnología

- Python (pandas, seaborn, matplotlib)
- Jupyter Notebooks
- VS Code
- Modelos simples de proyección financiera
