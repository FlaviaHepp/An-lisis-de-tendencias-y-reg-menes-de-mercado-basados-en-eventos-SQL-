# 📊Análisis de tendencias y regímenes de mercado basados ​​en eventos (SQL)

## 📌Descripción

Este proyecto presenta una colección de análisis cuantitativos de mercados financieros, desarrollados íntegramente en SQL, enfocados en la detección, confirmación y validación de tendencias, así como en el impacto de eventos y noticias sobre la dinámica del mercado.

El repositorio integra indicadores técnicos, métricas de volatilidad y eventos exógenos para identificar regímenes de mercado, tendencias fuertes y confiables, y zonas de riesgo o inflexión.

## 🎯Objetivos del Proyecto

- Detectar tendencias fuertes y sostenibles
- Confirmar tendencias mediante confluencia de señales
- Analizar el impacto de eventos, noticias y acciones corporativas
- Medir cambios de volatilidad y régimen
- Identificar contextos de riesgo sistémico
- Demostrar aplicación avanzada de SQL en finanzas

## 🧠Enfoque Analítico

El proyecto combina:
- Indicadores técnicos (ADX, métricas de tendencia)
- Confirmación de tendencia vía filtros adicionales
- Análisis pre-evento vs. post-evento
- Volatilidad histórica e implícita
- Coincidencia de señales técnicas y eventos
- Agregación a nivel activo, industria y sector

Preguntas que guía el análisis:
- ¿Cuándo una tendencia es realmente confiable?
- ¿Qué señales confirman o invalidan una tendencia?
- ¿Cómo influyen los eventos en su continuidad o ruptura?
- ¿Cuándo el mercado entra en un nuevo régimen?

## 🗂️Contenido del Repositorio

📁 Insights Principales

- Clasificación de Tickers por Robustez de la Tendencia (ADX)
- Confirmación de Tendencia Fuerte
- Clasificación de Eventos por Volatilidad Post-Evento
- Cobertura de la Volatilidad Sectorial por Eventos
- Cobertura de Noticias y Volatilidad Implícita (Kurtosis)
- Coincidencia de Eventos Negativos en la Industria
- Coincidencia de Extremos Técnicos y Noticias
- Compresión de Volatilidad previa a M&A

Cada insight está implementado como un query SQL independiente, diseñado para validar o contextualizar señales de mercado.

## 🧮Tecnologías Utilizadas

- SQL
- Bases de datos relacionales
- Compatible con PostgreSQL / MySQL / BigQuery

## 🗃️Modelo de Datos (conceptual)

- tickers
- ticker_id
- nombre_empresa
- sector
- industria
- indicadores_tecnicos
- ticker_id
- fecha
- ADX, métricas de tendencia y volatilidad
- eventos / noticias / corporativos
- ticker_id
- fecha_evento
- tipo_evento
- volatilidad_implicita
- ticker_id
- fecha
- métricas implícitas

## 📈Casos de Uso

- Screening de activos con tendencia confirmada
- Identificación de regímenes de mercado
- Research event-driven
- Apoyo a estrategias de trend following
- Evaluación de riesgo y contexto macro-sectorial

## ⚠️Consideraciones

- Las señales técnicas no son predictivas por sí solas
- La confirmación reduce ruido, no elimina riesgo
- Recomendado complementar con:
- gestión de riesgo
- backtesting
- análisis macroeconómico

## 🚀Posibles Extensiones

- Score de fuerza de tendencia
- Backtesting de señales confirmadas
- Integración con Python / BI
- Visualización de cambios de régimen

## 👤Autor

Flavia Hepp
Trend & Event-Driven Market Analytics · SQL
