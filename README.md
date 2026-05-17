# Trabajo de Fin de Grado (TFG)

**Título:** Trends on the Seasonal Evolution of Total Precipitable Water Vapour over the Mediterranean Sea.  
**Autora:** Adriana Ballester Olmo  
**Tutor/a:** Jose Luis Palau Aloy  
**Grado:** Física  
**Universidad:** Universidad Europea de Valencia  
**Año:** 2026

## Descripción

Este repositorio contiene el código fuente del Trabajo de Fin de Grado (TFG).  
El análisis se desarrolla íntegramente en el cuaderno `TFG.ipynb`, donde se procesan, analizan y visualizan datos meteorológicos.

El código principal está en el cuaderno Jupyter Notebook:  
📓 **`TFG.ipynb`** – Incluye todo el proceso: carga de datos, análisis, modelos/experimentos y conclusiones.

## Contenido

- `TFG.ipynb` – Cuaderno con el código final completo.
- `README.md` – Este archivo.
- (Si se incluyen otros: `requirements.txt`, `data/`, `images/`, etc., añádelos aquí)

## Datos

Los datos utilizados en este análisis provienen de la **NASA** (Goddard Earth Sciences Data and Information Services Center – GES DISC).  
Se emplean archivos CSV con series temporales de:

- **Vapor de agua precipitable (TPW)**  
- **Evaporación neta**

Los archivos esperados por el cuaderno son:

- `WMBwatervapor.csv`
- `EMBwatervapor.csv`
- `WMBevap.csv`
- `EMBevap.csv`

### Cómo obtener los datos

1. Accede al portal de la NASA: [https://giovanni.gsfc.nasa.gov/giovanni/](https://giovanni.gsfc.nasa.gov/giovanni/)
2. Selecciona la región geográfica (West Mediterranean Basin – WMB y East Mediterranean Basin – EMB).
3. Descarga las variables en formato CSV con la nomenclatura indicada.
4. Coloca los archivos en la siguiente estructura de carpetas (relativa al cuaderno):

TFG/
├── DATOS/
│   ├── WMBwatervapor.csv
│   ├── EMBwatervapor.csv
│   ├── WMBevap.csv
│   └── EMBevap.csv
└── TFG.ipynb

> **Nota**: Los datos no se incluyen en este repositorio por su tamaño y políticas de distribución. Deben descargarse directamente desde la fuente oficial.

## Requisitos

Para ejecutar el cuaderno necesitas:

- Python 3.8 o superior
- Jupyter Notebook o JupyterLab

Y las siguientes librerías:

- `pandas`
- `numpy`
- `matplotlib`
- `scipy`
- `statsmodels`

### Instalación rápida de dependencias

Puedes instalar todas las dependencias con:

```bash
pip install pandas numpy matplotlib scipy statsmodels jupyter
