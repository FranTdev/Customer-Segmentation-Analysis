# Segmentación Estratégica de Clientes (K-Means Clustering)

## Descripción del Proyecto
Este proyecto simula un caso de negocio real para un centro comercial que busca optimizar sus campañas de marketing. Utilizando técnicas de Machine Learning no supervisado (**K-Means Clustering**), se analizaron datos de clientes para identificar patrones de comportamiento y segmentar el mercado.

El objetivo final fue transformar datos crudos en **insights accionables**, permitiendo al equipo de marketing diseñar estrategias personalizadas para cada grupo de clientes.

## Tecnologías y Herramientas
* **Lenguaje:** Python 3.x
* **Análisis y Manipulación:** Pandas, NumPy
* **Visualización:** Seaborn, Matplotlib
* **Machine Learning:** Scikit-learn (K-Means, Silhouette Score)
* **Entorno:** Jupyter Notebook / Anaconda

## Metodología (Estructura del Análisis)
El proyecto se desarrolló siguiendo un flujo de trabajo profesional de 5 fases:
1.  **Entendimiento del Negocio:** Definición de objetivos y KPIs.
2.  **EDA (Exploratory Data Analysis):** Análisis de distribuciones y correlaciones bivariadas.
3.  **Preprocesamiento:** Limpieza y estandarización de datos (`StandardScaler`) para optimizar el algoritmo.
4.  **Modelado:** Determinación del número óptimo de clusters (K) usando el **Método del Codo** y validación con **Coeficiente de Silueta**.
5.  **Interpretación de Negocio:** Traducción de los clusters matemáticos a perfiles de clientes reales (Arquetipos).

## Principales Hallazgos (Insights)
El modelo identificó **5 segmentos clave** de clientes:

* **Clientes VIP:** Altos ingresos y alto puntaje de gastos. (Objetivo principal para fidelización).
* **Clientes Objetivo:** Ingresos medios y gastos medios. (Masa crítica del negocio).
* **Ahorradores:** Altos ingresos pero bajo gasto. (Oportunidad latente de conversión).
* **Despreocupados:** Bajos ingresos y alto gasto. (Público joven/impulsivo).
* **Cautelosos:** Bajos ingresos y bajo gasto.

## 🚀 Cómo ejecutar este proyecto
1. Clonar el repositorio:
   ```bash
   git clone [https://github.com/FranTdev/Customer-Segmentation-Analysis.git](https://github.com/FranTdev/Customer-Segmentation-Analysis.git)

2. Instalar dependencias:
   ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn

3. Ejecutar el notebook Segmentacion_KMeans.ipynb en Jupyter o VS Code.
   
4. Tambien pueden ingresar con [Colab](https://colab.research.google.com/github/FranTdev/Segmentacion_Clientes_KMeans/blob/main/Segmentacion_KMeans.ipynb)


Proyecto desarrollado por mi Francisco Steven Tabares como parte de mi portafolio de Análisis de Datos.
