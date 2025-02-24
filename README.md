# Optimización del Rendimiento de un Equipo de Fútbol mediante Análisis Estadístico

## 📋 Descripción
Este proyecto analiza el rendimiento de jugadores de fútbol en la **Premier League 2023-2024**, con el objetivo de identificar a los jugadores más eficientes para cada posición en el campo. Se utilizaron **métricas avanzadas de rendimiento**, técnicas de **web scraping** desde **FBRef** y un **análisis estadístico profundo** para seleccionar un equipo ideal bajo una formación 4-3-3.

## 🎯 Objetivo
Identificar a los jugadores más efectivos por posición, utilizando un enfoque estadístico basado en métricas clave como **PPDA**, **Goles Esperados (xG)**, **Asistencias Esperadas (xAG)**, **Efectividad de Tiros**, entre otras.

## 🔍 Proceso Metodológico
1. **Web Scraping:** Extracción de datos de rendimiento de jugadores desde **FBRef** mediante `pandas` y `pd.read_html()`.
2. **Preprocesamiento de Datos:**
   - Eliminación de filas nulas y datos inconsistentes.
   - Normalización de métricas por 90 minutos jugados.
   - Agrupación de posiciones en categorías generales (Portero, Defensor, Mediocampista, Delantero).
3. **Transformación de Datos:**
   - Creación de nuevas métricas, como **xOVA** (valor ofensivo agregado) y **PPDA** (pases permitidos por acción defensiva).
   - Generación de **rankings** ofensivos, defensivos, de creación de juego y de pases.
4. **Análisis Estadístico:**
   - Evaluación de rendimiento por posición y selección de los mejores jugadores para una formación 4-3-3.
   - Se realizaron pruebas con **modelos de regresión** y **árboles de decisión**, aunque los resultados de las métricas obtenidas fueron bajos.

## 🛠️ Herramientas Utilizadas
- **Lenguaje:** Python
- **Librerías:** `pandas`, `numpy`, `matplotlib`, `seaborn`
- **Entornos:** `Databricks`, `Google Colab`

## 🏅 Equipo Ideal Seleccionado
- **Portero:** Arijanet Muric
- **Defensas:** Cristian Romero, Levi Colwill, Destiny Udogie, Pedro Porro
- **Mediocampistas:** Alexis Mac Allister, Kevin De Bruyne, Bruno Fernandes
- **Delanteros:** Cole Palmer, Phil Foden, Erling Haaland

## 📂 Estructura del Proyecto
```
📦 football-performance-analysis
 ├── 📁 data            # Datos procesados para la parte de análisis estadístico
 ├── 📁 notebook       # Notebooks trabajados
 ├── 📄 README.md       # Documentación del proyecto
 ├── 📄 requirements.txt # Dependencias del proyecto
 └── 📄 informe_analisis_futbol.pdf # Informe completo del análisis
```

## 📈 Conclusión
El proyecto permitió seleccionar un equipo ideal basado en métricas objetivas de rendimiento, mostrando cómo el análisis estadístico puede optimizar la toma de decisiones en la gestión de un equipo de fútbol.

## 📧 Autores
Juan Torres y Juliana Rubio

