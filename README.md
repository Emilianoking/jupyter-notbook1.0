# 📊 Exploratory Data Analysis (EDA) - Sales Performance Colombia

Este repositorio contiene un script de Python diseñado para realizar un **Análisis Exploratorio de Datos (EDA)** sobre un dataset sintético de ventas mensuales. El proyecto demuestra la capacidad de procesar grandes volúmenes de datos y transformarlos en información estadística accionable.

## 🎯 Objetivos del Proyecto
* **Simulación de Datos:** Generación de datasets estructurados utilizando `NumPy` para representar ciclos comerciales anuales.
* **Análisis Estadístico:** Aplicación de funciones de agregación para determinar tendencias de mercado por ubicación geográfica.
* **Data Wrangling:** Limpieza, filtrado y transformación de datos mediante `Pandas`.
* **Visualización:** Representación gráfica de resultados para facilitar la toma de decisiones.

## 🛠️ Stack Tecnológico
* **Python 3.x**
* **Pandas:** Para la manipulación de estructuras de datos (DataFrames).
* **NumPy:** Para cálculos matemáticos avanzados y generación de datos aleatorios.
* **Matplotlib:** Para la creación de reportes visuales dinámicos.

## 📋 Metodología de Análisis
El flujo de trabajo implementado en el código sigue estos pasos:

1.  **Ingesta de Datos:** Creación de un DataFrame con registros de ventas para 5 ciudades principales de Colombia (Bogotá, Medellín, Cali, Barranquilla, Cartagena).
2.  **Cálculo de Métricas:** * Suma total de ingresos por nodo regional.
    * Determinación de la **Media Aritmética** y la **Desviación Estándar** para medir la volatilidad de las ventas.
3.  **Segmentación (Performance Filtering):** Identificación automática de ciudades con un desempeño superior al promedio (High-Performance Cities).
4.  **Ajuste Estocástico:** Aplicación de un factor de variación aleatoria para simular proyecciones de ventas ajustadas.

## 📈 Visualización de Resultados
El script genera un gráfico de barras comparativo que ilustra las **Ventas Ajustadas por Ciudad**, permitiendo un análisis visual inmediato del market share simulado.



## 🚀 Ejecución
Para replicar este análisis, clona el repositorio y ejecuta:

```bash
# Instalación de dependencias
pip install pandas numpy matplotlib

# Ejecución del script
python sales_analysis.py
