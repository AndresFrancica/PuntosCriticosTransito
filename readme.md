# 🚦 Análisis de Puntos Críticos de Tránsito en CABA

Este proyecto aborda el análisis exploratorio de datos (EDA) y la geolocalización de incidentes viales junto con el flujo vehicular en la Ciudad Autónoma de Buenos Aires. El objetivo principal es identificar zonas de mayor riesgo vial (puntos negros/críticos) para respaldar la toma de decisiones basada en datos.

---

## 📌 Objetivos del Proyecto

- **Geolocalización:** Limpieza y mapeo espacial de siniestros viales a partir de coordenadas geográficas ($EPSG:4326$).
- **Integración de Datos:** Cruce de información entre reportes de siniestros y mediciones de flujo vehicular.
- **Visualización:** Generación de mapas interactivos y mapas de calor para detectar intersecciones de alto riesgo.
- **Modelado:** Desarrollo de modelos predictivos y de clustering para la categorización de zonas prioritarias.

---

## 🛠️ Tecnologías y Librerías

- **Lenguaje:** Python 3.12
- **Análisis de Datos:** `pandas`, `numpy`
- **Geodatos y Mapas:** `geopandas`, `shapely`, `folium`, `matplotlib`
- **Machine Learning:** `scikit-learn`
- **Entorno:** Visual Studio Code / Jupyter Notebooks

---

## 📂 Estructura del Repositorio

```text
PuntosCriticosTransito/
├── datos/                  # Datasets de siniestros, flujo y geometrías (excluido de Git si es pesado)
├── venv/                   # Entorno virtual (excluido en .gitignore)
├── 01_eda_inicial.ipynb    # Notebook de carga, validación y exploración geográfica
├── .gitignore              # Archivos y carpetas ignorados por Git
└── README.md               # Documentación del proyecto
