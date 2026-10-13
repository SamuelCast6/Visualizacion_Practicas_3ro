# Práctica 1: Análisis de los Datos de Acceso a la Universidad

**Asignatura:** Visualización de Datos  
**Autores:** Samuel Castaño Farelo y David López Poza

## 1. Estructura de la Práctica

* **`src/Notebook.ipynb`**: Notebook principal con la carga, procesamiento y visualización de los datos de acceso de UAM, UCM y URJC.
* **`docs/graficas_pdf/`**: Exportación en alta calidad (300 DPI) de todas las figuras generadas en formato PDF vectorial.
* **`docs/practica1.pdf`**: Enunciado oficial de la práctica.

## 2. Tecnologías y Librerías Utilizadas

* **Matplotlib:** Empleado en las Partes 1 y 2 para visualizaciones básicas y figuras multipanel (`subplots`) con escala simétrica logarítmica (`symlog`) y ejes combinados (`twinx`).
* **Seaborn:** Empleado en la Parte 3 para análisis avanzados de distribución (`boxplot`, `violinplot`, `stripplot`).
* **Pandas:** Carga, agregación y cruce de datos con la clasificación de ramas del Ministerio de Universidades.