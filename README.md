# Análisis del Impacto del IDH en la Deserción Escolar en Colombia

## Descripción del Proyecto
Este proyecto analiza la relación entre el Índice de Desarrollo Humano (IDH) y las tasas de deserción escolar en Colombia. A través de un proceso de Extracción, Transformación y Carga (ETL), hemos consolidado datasets del DANE y el Ministerio de Educación Nacional para identificar patrones de rezago educativo en distintas regiones.

## Tecnologías Utilizadas
- **Python**: Procesamiento y análisis de datos.
- **Pandas**: Limpieza y manipulación de DataFrames.
- **Seaborn/Matplotlib**: Visualización de datos estadísticos.
- **Git/GitHub**: Gestión de versiones y colaboración.

## Estructura del Repositorio
/proyecto-idh-colombia
│
├── /data
│   ├── /raw         # Archivos originales (fuentes oficiales)
│   └── /processed   # Datasets limpios listos para análisis
├── notebook.ipynb   # Código ETL y análisis exploratorio (EDA)
├── presentacion.pdf # Presentación ejecutiva de hallazgos
└── README.md        # Este archivo

## Contribuidores
- Miguel Augusto Gómez Delgado
- Alejandro Rivera Muriel

------------------------------------------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------------------------------------------

# Analysis of the Impact of HDI on School Dropout Rates in Colombia

## Project Description
This project analyzes the relationship between the Human Development Index (HDI) and school dropout rates in Colombia. Through an ETL (Extract, Transform, Load) process, we have consolidated datasets from DANE and the Ministry of National Education to identify educational lag patterns across different regions.

## Technologies used
- Python: Data processing and analysis.
- Pandas: Data cleaning and manipulation.
- Seaborn/Matplotlib: Statistical data visualization.
- Git/GitHub: Version control and collaboration.

## Repository structure
/proyecto-idh-colombia
│
├── /data
│   ├── /raw         # Original files (official sources)
│   └── /processed   # Cleaned datasets ready for analysis
├── notebook.ipynb   # ETL code and Exploratory Data Analysis (EDA)
├── presentacion.pdf # Executive presentation of findings
└── README.md        # This file

## Contributors
- Miguel Augusto Gómez Delgado
- Alejandro Rivera Muriel

### Acceso a los datasets/ datasets access
Ministerio de Educación Nacional de Colombia. (2026). Estadísticas en educación en 
preescolar, y media por departamento 
[Conjunto datos]. https://www.datos.gov.co/Educaci-n/MEN_ESTADISTICAS_EN_EDUCACION_EN_PREESCOLAR-B-SICA/ji8i-4anb/about_data

Ministerio de Educación Nacional de Colombia. (2026). Matrícula en educación en preescolar, básica media por deaprtamento [Conjunto de 
datos]. https://www.datos.gov.co/Educaci-n/MEN_MATRICULA_EN_EDUCACION_EN_PREESCOLAR-B-SICA-Y-/ngw5-c5nw/about_data 

Programa de las Naciones Unidas para el Desarrollo. (2024). Índice de desarrollo humano a nivel en Colombia [Conjunto datos] https://www.undp.org/es/colombia/data-futures-exchange-platform (datos scrappeados/scrapped data: https://docs.google.com/spreadsheets/d/1Malwl8yEsoOtdoUvdQsvdfsNPlsiN5mg/edit?usp=sharing&ouid=106696535163356436450&rtpof=true&sd=true)