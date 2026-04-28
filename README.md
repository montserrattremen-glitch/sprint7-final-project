# sprint7-final-project
# 📊 ConnectaTel Customer Behavior Analysis

## 🧩 Project Overview
Como analista de datos, el objetivo de este proyecto es evaluar el comportamiento de los clientes de una empresa de telecomunicaciones en Latinoamérica, **ConnectaTel**.

El análisis se basa en datos registrados hasta el año 2024, lo que permite entender patrones de uso, detectar anomalías y generar insights accionables para el negocio.

---

## 🎯 Objective
- Analizar el comportamiento de consumo de los clientes
- Identificar patrones de uso en llamadas, mensajes y datos
- Detectar valores atípicos y posibles problemas en los datos
- Crear segmentos de clientes basados en su comportamiento
- Proponer estrategias de retención y mejoras en los planes

---

## 📁 Datasets Used

Se utilizaron tres conjuntos de datos:

### plans.csv
- Información de los planes disponibles
- Variables: precio, minutos incluidos, GB incluidos, costo por excedente

### users.csv
- Información de los clientes
- Variables: edad, ciudad, fecha de registro, plan, churn

### usage.csv
- Registro del uso real de servicios
- Variables: llamadas (`duration`), mensajes (`length`), tipo de evento

---

## 🔍 Analysis Stages

### 1. Data Exploration
- Revisión de estructura de datasets
- Identificación de tipos de datos
- Detección de valores nulos

### 2. Data Cleaning
- Tratamiento de valores nulos estructurales (ej. `duration` vs `length`)
- Corrección de tipos de datos (fechas, numéricos)
- Eliminación o tratamiento de valores atípicos

### 3. Data Analysis
- Análisis descriptivo (media, mediana, distribución)
- Segmentación por edad
- Segmentación por nivel de uso
- Análisis de churn
- Identificación de patrones de consumo

### 4. Data Visualization
- Gráficas de distribución
- Boxplots para detectar outliers
- Comparaciones entre segmentos

### 5. Insights & Recommendations
- Interpretación de resultados
- Identificación de oportunidades de negocio
- Propuestas de mejora en planes y retención
