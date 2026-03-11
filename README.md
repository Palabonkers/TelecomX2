# TelecomX Analysis - Latam Phase 2

Este repositorio contiene la implementación y el análisis de datos para la fase 2 del proyecto **TelecomX**, centrado en la retención de clientes y análisis de bajas (churn) en el mercado latinoamericano.

## 👤 Autor
* **Pablo Paladino**

## 📋 Descripción del Proyecto
El objetivo de este desarrollo es transformar datos crudos de telecomunicaciones (en formato JSON) en un conjunto de datos estructurado y limpio, listo para ser procesado por modelos de Machine Learning. 

A diferencia de scripts lineales convencionales, este proyecto implementa una arquitectura basada en **Programación Orientada a Objetos (POO)**. Esto permite una mayor modularidad, facilita las pruebas unitarias y asegura que el pipeline de limpieza sea escalable para diferentes regiones de Latam.

## 🛠️ Funcionalidades Principales
El sistema se divide en cuatro procesos críticos:
1. **Ingesta Automatizada**: Carga y normalización de estructuras JSON anidadas a DataFrames de Pandas.
2. **Depuración de Target**: Identificación y eliminación de registros inconsistentes o vacíos en la variable objetivo (`Churn`).
3. **Encoding de Variables**: Transformación de etiquetas categóricas y binarias (género, servicios, facturación electrónica) a formato numérico eficiente.
4. **Sanitización Financiera**: Conversión de métricas de facturación (`Charges.Total`) a tipos de datos flotantes, gestionando automáticamente valores nulos o erróneos.

## 🚀 Tecnologías Utilizadas
* **Python 3.x**
* **Pandas**: Para la manipulación de estructuras de datos masivas.
* **NumPy**: Operaciones matemáticas y gestión de valores nulos.
* **Matplotlib & Seaborn**: Generación de insights visuales.

---
*Nota: Este proyecto fue desarrollado bajo estándares de código limpio (Clean Code) y principios de análisis de datos profesional.*
