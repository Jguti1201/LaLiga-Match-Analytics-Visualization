# ⚽ LaLiga Match Analytics & Visualization

Este proyecto automatiza la **extracción, análisis y visualización de estadísticas de partidos de LaLiga**, utilizando datos públicos de Marca y archivos de eventos de Opta. Genera **infografías estilo neón** con métricas clave, mapas de pases, tiros y posesión por equipo.

---

## 🔹 Características principales

1. **Scraping de datos en vivo**:
   - Obtiene información de partidos desde [Marca.com](https://www.marca.com/).
   - Extrae equipos, goles, posesión y estadísticas avanzadas del **Shadow DOM** usando Selenium.

2. **Análisis de estadísticas**:
   - Calcula métricas de ataque, defensa y amonestaciones.
   - Filtra y normaliza eventos de partidos (pases, tiros, goles).
   - Agrupa datos por zonas del campo y bloques de tiempo.

3. **Visualizaciones interactivas y gráficas estilo neón**:
   - Barras horizontales comparando estadísticas por equipo.
   - Mapas de pases por zonas horizontales del campo.
   - Distribución de tiros por tiempo del partido.
   - Campo de fútbol estilizado con **Pitch Plot** y escudos de los equipos.
   - Todas las gráficas se guardan en PNG en la carpeta `infografias partido`.

4. **Soporte para múltiples equipos y partidos**:
   - Diseñado para FC Barcelona y Real Sociedad como ejemplo.
   - Fácilmente extensible a otros partidos y equipos de LaLiga.

---

## 🛠 Tecnologías y librerías

- **Python**:
  - `selenium` + `webdriver-manager` → scraping de sitios web dinámicos.
  - `pandas`, `numpy` → limpieza y procesamiento de datos.
  - `matplotlib`, `plotly` → visualización de datos y gráficos interactivos.
  - `PIL`, `requests` → carga de escudos y recursos gráficos.


---

## 📂 Estructura del proyecto

