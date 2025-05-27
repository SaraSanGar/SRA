# Análisis de Trayectoria - Ejercicio Individual 2

Este proyecto consiste en el análisis de trayectorias de un conjunto de datos GPS utilizando técnicas de ciencia de datos y visualización. El objetivo principal es explorar, analizar y representar gráficamente la información para extraer conclusiones relevantes sobre el comportamiento espacial de los datos.

## 📁 Contenido

El proyecto se compone de un notebook de Jupyter donde se desarrollan las siguientes etapas:

1. **Carga de datos**: Lectura de datos GPS desde un archivo CSV.
2. **Visualización inicial**: Representación de las trayectorias en un mapa utilizando `matplotlib` y `geopandas`.
3. **Procesamiento y filtrado**: Conversión de coordenadas, limpieza de datos y transformación en `GeoDataFrames`.
4. **Análisis espacial**:
   - Cálculo de distancias y velocidades.
   - Identificación de puntos clave (inicio, fin).
   - Segmentación de trayectorias.
5. **Visualización avanzada**: Mapas interactivos con `folium`, trazado de rutas, y representaciones por color y tamaño en función de la velocidad.

## 🛠 Requisitos

Para ejecutar correctamente el proyecto, asegúrate de tener instaladas las siguientes bibliotecas de Python:

```bash
pip install pandas numpy matplotlib geopandas shapely folium
```
---

## 🚀 Cómo usar
1. Clona este repositorio o descarga el archivo .ipynb.
2. Abre el notebook con Jupyter Notebook o Google Colab.
3. Ejecuta cada celda en orden para reproducir el análisis.

---

## 📌 Notas
- El dataset debe estar disponible en la ruta indicada dentro del notebook o adaptarse a la ubicación correcta.
- Se recomienda tener un entorno virtual para gestionar las dependencias
