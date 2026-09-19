# 002-Tienda_Ice

# 🎮 Análisis Predictivo de Ventas de Videojuegos para Tienda "ICE"

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![Seaborn](https://img.shields.io/badge/Seaborn-Data%20Viz-3776AB)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## 📌 Descripción del Proyecto

Este proyecto consiste en un **Análisis Exploratorio de Datos (EDA)** y estudio estadístico realizado para la tienda online internacional de videojuegos **"ICE"**. 

## 🎯 Objetivo Principal

El objetivo principal es identificar patrones históricos en las ventas globales, impacto de las calificaciones (usuarios/críticos), ciclo de vida de las plataformas y clasificaciones de contenido (ESRB). Con base en los datos acumulados hasta diciembre de 2016, el análisis permite detectar proyectos prometedores y planificar campañas publicitarias estratégicas para el año 2017.

## 🛠️ Tecnologías y Librerías Utilizadas

* Lenguaje: Python 3.x
* Manipulación de Datos: pandas, numpy
* Análisis Estadístico: scipy.stats
* Visualización de Datos: matplotlib, seaborn
* Entorno de Desarrollo: Jupyter Notebook / VS Code

## ⚙️ Pasos de Procesamiento y Limpieza de Datos (Data Wrangling)

1. Estandarización de Encabezados: Conversión de los nombres de columnas a minúsculas y formato snake_case.

2. Transformación de Tipos de Datos (Casting):

  * Conversión de user_score a tipo numérico manejando valores no numéricos (coerce para valores tipo TBD).
  * Optimización de memoria cambiando columnas categóricas (platform, genre) y tipos enteros opcionales (Int64).
    
3. Tratamiento de Valores Nulos:

  * Eliminación de registros con valores ausentes en name, genre y year_of_release debido a su baja representatividad.
  * Imputación de valores faltantes en la columna rating bajo la categoría 'Unknown'.

4. Ingeniería de Características: Creación de la columna total_sales sumando las ventas de todas las regiones.

## 📈 Hallazgos y Conclusiones del Análisis

1. Evolución de la Industria por Épocas:

* Años 80 - 90: Registro escaso de datos debido al tamaño reducido de la industria y enfoque en éxitos masivos.
* Década de 2000 - 2010: Gran auge comercial impulsado por consolas como PS2, Nintendo DS y Wii.
* Periodo 2011 - 2016: Estabilización y leve declive del formato físico por la transición paulatina al mercado digital.

2. Ciclo de Vida de las Consolas:

* El ciclo de vida útil promedio de una consola varía entre 10 a 12 años.
* El periodo de madurez y auge de ventas de una consola oscila entre los 3 y 6 años desde su lanzamiento.

3. Plataformas Líderes Históricas:

* PS2: Líder absoluto con más de 1,250 millones de ventas globales.
* X360 y PS3: Cercanas a los 950 millones de ventas cada una.
* Wii y DS: Superando la franja de los 800-900 millones.

Creado por [Abraham Gómez]

📧 Correo: gomez.rangel.abraham@gmail.com

💼 LinkedIn: www.linkedin.com/in/abraham-gomez-rangel

🌐 Portfolio / Sitio Web: https://github.com/abraham232425

Si este proyecto te resultó útil o te sirvió de inspiración, ¡no dudes en darle una ⭐ al repositorio!
