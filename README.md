# proyecto-da-promo-63-modulo-4-team2-proyectofinal
FENOMENOS CLIMATOLÓGICOS
# Análisis de avisos AEMET y emergencias: DANA y Filomena

## Descripción del proyecto

Este proyecto analiza la relación entre avisos meteorológicos emitidos por AEMET y registros de emergencias asociados a episodios extremos en España, especialmente DANA y Filomena.

El objetivo principal es limpiar, unificar y analizar diferentes fuentes de datos para construir un dashboard final en Tableau que permita visualizar la evolución temporal, la distribución geográfica y la severidad de los avisos meteorológicos y emergencias.

## Objetivos

- Extraer y preparar datos meteorológicos procedentes de AEMET.
- Limpiar y unificar datasets relacionados con episodios extremos.
- Analizar avisos meteorológicos entre 2021 y 2026.
- Geolocalizar zonas y municipios para su representación en Tableau.
- Crear datasets finales limpios para visualización.
- Desarrollar un dashboard interactivo en Tableau.

## Estructura del repositorio

```text
.
├── data/
│   ├── raw/
│   │   ├── avisos_aemet_2021_2026_descripcion.csv
│   │   └── episodios_extremos_unificados.csv
│   │
│   ├── processed/
│   │   ├── avisos_aemet_final.csv
│   │   ├── datos_dana_emergenciasok.csv
│   │   ├── datos_filomena_emergenciasok.csv
│   │   └── zonas_sin_coordenadas_pendientes.csv
│   │
│   └── final/
│       ├── avisos_aemet_tableau_limpio.csv
│       └── emergencias_limpio.csv
│
├── notebooks/
│   ├── 01_extraccion_datos.ipynb
│   ├── 02_extraccion_avisos_aemet.ipynb
│   ├── 03_eda_aemet_2021_2026_severity.ipynb
│   ├── 04_proyecto_final.ipynb
│   └── 99_extraccion_avisos_aemet_backup.ipynb
│
├── tableau/
│   └── proyecto-da-promo-63-modulo-4-team2.twbx
│
├── .gitignore
├── requirements.txt
└── README.md