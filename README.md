# Megaline Tariff Analysis

Este proyecto analiza los datos de uso de los clientes de Megaline con el propósito de determinar qué tarifa de prepago (Surf o Ultimate) genera mayores ingresos para la compañía. El análisis incluye limpieza, enriquecimiento de datos, cálculo de métricas claves y comparación estadística entre ambas tarifas para respaldar la recomendación final.

---

## 📌 Objetivo
- Evaluar el desempeño de dos tarifas de prepago.
- Determinar cuál genera mayores ingresos para Megaline.
- Analizar patrones de uso de llamadas, mensajes y datos.
- Preparar, limpiar y enriquecer el dataset para un análisis confiable.
- Realizar pruebas estadísticas para validar diferencias significativas.

---

## 🧹 Limpieza y Preparación de Datos
El preprocesamiento incluyó:
- Corrección de datos inconsistentes.
- Conversión de minutos, mensajes y megabytes utilizados.
- Cálculo de ingresos mensuales por cliente.
- Creación de nuevas variables (mes, duración de llamadas, consumo de datos en GB, etc.).
- Integración de información de usuarios, planes y comportamiento.

---

## 📊 Análisis Realizado
- Exploración del comportamiento de los usuarios según su tarifa.
- Distribución de minutos, mensajes y datos utilizados.
- Comparación del consumo mensual entre clientes Surf y Ultimate.
- Análisis de ingresos por cliente y por mes.
- Prueba de hipótesis para determinar si los ingresos difieren significativamente entre ambas tarifas.

---

## 📈 Resultados Principales
- La tarifa **Ultimate** tiende a generar mayores ingresos debido a su costo base y al consumo de datos de ciertos usuarios.
- Los usuarios del plan **Surf** con frecuencia superan los límites de su tarifa, generando cargos adicionales importantes.
- La prueba estadística indica que las diferencias en ingresos **son significativas**, permitiendo respaldar la recomendación sobre la tarifa más rentable.

---

## 🛠 Tecnologías Utilizadas
- **Python**
- **Pandas**
- **Matplotlib / Plotly**
- **Estadística (prueba de hipótesis)**

---

## 📁 Archivos del Proyecto
- `megaline-tariff-analysis.ipynb` — Notebook principal del análisis.
- Dataset original (usuarios, planes, comportamiento mensual).

---

## 📬 Contacto
Proyecto desarrollado como parte del portafolio analítico de **Monica Baca**.
