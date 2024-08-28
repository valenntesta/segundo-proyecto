# Proyecto de Análisis de Datos para Empresa de Telecomunicaciones

## Descripción del Proyecto

Este proyecto está enfocado en el análisis de datos para una empresa de telecomunicaciones, utilizando herramientas y técnicas de análisis de datos para obtener insights significativos sobre el acceso a internet y la evolución de las conexiones. El análisis incluye el uso de Python para el procesamiento de datos y Power BI para la visualización de indicadores clave de rendimiento (KPI).

## Herramientas y Librerías Utilizadas

- **Python**: Para el análisis de datos y procesamiento.
  - **pandas**: Manipulación y análisis de datos.
  - **numpy**: Cálculos matemáticos y operaciones numéricas.
  - **matplotlib.pyplot**: Visualización de datos.
  - **seaborn**: Creación de gráficos estadísticos.
  - **math**: Operaciones matemáticas.
  - **warnings**: Manejo de advertencias.

- **Power BI**: Para la visualización interactiva de datos y KPIs.

## KPIs

1. **KPI de Penetración de Internet**:
   - **Fórmula**: `KPI = ((NuevoAcceso - AccesoActual) / AccesoActual) * 100`
   - **Descripción**: Mide el porcentaje de aumento en el acceso a internet comparado con el trimestre anterior.

2. **KPI de Crecimiento en Conexiones de Más de 30 Mbps**:
   - **Fórmula**: `Crecimiento Más de 30 Mbps = ((Total 'Más de 30 Mbps' trimestre actual - Total 'Más de 30 Mbps' trimestre anterior) / Total 'Más de 30 Mbps' trimestre anterior) * 100`
   - **Descripción**: Mide el crecimiento porcentual en el número de conexiones con velocidades superiores a 30 Mbps entre trimestres.

## Exploratory Data Analysis (EDA)

El EDA realizado en el proyecto abarca los siguientes aspectos:

1. **Búsqueda de Valores Faltantes**:
   - Identificación y manejo de datos faltantes para asegurar la integridad del análisis.

2. **Detección de Valores Atípicos/Extremos**:
   - Identificación y tratamiento de outliers para mejorar la precisión de los análisis.

3. **Detección de Registros Duplicados**:
   - Eliminación de registros duplicados para evitar sesgos en los análisis.

4. **Uso de Gráficos Coherentes**:
   - Utilización de gráficos adecuados para cada tipo de variable, facilitando la interpretación de los datos.

## ETL (Extracción, Transformación y Carga)

El proceso ETL incluye:

1. **Extracción**:
   - Obtención de datos desde diferentes fuentes.

2. **Transformación**:
   - Limpieza y preparación de datos para el análisis, incluyendo la normalización y agregación de datos.

3. **Carga**:
   - Carga de los datos transformados en los formatos necesarios para el análisis en Power BI y en Python.

## Instrucciones para Ejecutar el Proyecto

1. **Configuración del Entorno**:
   - Asegúrate de tener Python instalado y las librerías necesarias (`pandas`, `numpy`, `matplotlib`, `seaborn`, `math`, `warnings`).

2. **Ejecutar los Scripts de Python**:
   - Ejecuta los scripts Python proporcionados para procesar y analizar los datos.

3. **Importar Datos a Power BI**:
   - Importa los datos procesados en Power BI.
   - Configura los KPIs en Power BI usando las medidas proporcionadas.

4. **Visualizar los Datos**:
   - Usa los gráficos y KPIs en Power BI para interpretar los resultados y obtener insights.
   
