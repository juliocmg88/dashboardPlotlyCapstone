# 🚀 SpaceX Launch Records Dashboard

Este proyecto es una aplicación interactiva construida con **Plotly Dash** que permite explorar los registros históricos de lanzamientos de SpaceX. A través de visualizaciones dinámicas, los usuarios pueden analizar el rendimiento de diferentes sitios de lanzamiento, rangos de carga útil y versiones de cohetes **Falcon 9 Booster**.

## 📊 Funcionalidades

- **Dropdown** para seleccionar un sitio de lanzamiento específico o visualizar todos.
- **Gráfico de torta (Pie Chart)** que muestra:
  - Total de lanzamientos exitosos por sitio.
  - Comparación éxito vs. fallo para un sitio específico.
- **Slider de rango de carga útil** que permite filtrar lanzamientos por peso transportado (en kilogramos).
- **Gráfico de dispersión (Scatter Plot)** que muestra:
  - Correlación entre la carga útil y el resultado del lanzamiento.
  - Coloreado por categoría de versión del booster.

## 🧠 Preguntas que puedes responder con el dashboard

- ¿Cuál sitio tiene más lanzamientos exitosos?
- ¿Qué sitio tiene la mayor tasa de éxito?
- ¿Qué rangos de carga útil son más exitosos?
- ¿Qué versión del Falcon 9 presenta mejor rendimiento?

## 🛠️ Tecnologías utilizadas

- Python 3
- Dash (Plotly)
- Pandas
- Plotly Express

## 📁 Archivos principales

- `spacex-dash-app.py`: Código fuente de la aplicación.
- `spacex_launch_dash.csv`: Dataset con los registros de lanzamientos de SpaceX.
- `README.md`: Documentación del proyecto.

## ▶️ Cómo ejecutar

1. Clona este repositorio:

```bash
git clone https://github.com/tu-usuario/spacex-dash-app.git
cd spacex-dash-app
