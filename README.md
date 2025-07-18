# alura-store-challenge
Challenge Data Science – Alura LATAM

# 🛍️ Alura Store – Análisis de Ventas con Python

Este proyecto forma parte del **Challenge de Datos – Alura LATAM**. El objetivo es ayudar al Sr. Juan a tomar una decisión estratégica: vender una de sus cuatro tiendas virtuales en Colombia. A partir del análisis de las ventas, categorías, evaluaciones de clientes, productos más/menos vendidos y costos logísticos, se determina cuál tienda tiene un desempeño inferior.

También se incluye un análisis **geográfico adicional (opcional)** para mapear la distribución de ventas a través de coordenadas geográficas.

---

## 🧠 Objetivos del Desafío

1. **Facturación total por tienda** → ¿Cuál tienda vende más?
2. **Productos más vendidos por categoría y tienda** → ¿Qué se vende mejor en cada una?
3. **Evaluación promedio de cada tienda** → ¿Qué opinan los clientes?
4. **Productos más y menos vendidos** → ¿Qué productos tienen mayor o menor salida?
5. **Costo promedio de envío** → ¿Qué tan caro es despachar desde cada tienda?

### Extra (Opcional):
- 📍 Análisis del **desempeño geográfico** de las tiendas utilizando coordenadas `lat/lon` con mapas interactivos (Folium/Plotly).

---

## 🧰 Herramientas y Tecnologías

- **Python 3**
- `Pandas` – manipulación y análisis de datos
- `Matplotlib` / `Seaborn` – visualización de datos y heatmaps
- `Folium` – mapas interactivos con coordenadas geográficas
- `Plotly Express` – mapas con leyenda dinámica y visualización avanzada
- `Jupyter Notebook` (Google Colab)
- Git + GitHub para versionado

---

## 📊 Contenido del Análisis

| Sección                         | Descripción |
|--------------------------------|-------------|
| 🧾 **Análisis de facturación** | Comparación de ventas totales entre tiendas |
| 🛍️ **Categorías más populares** | Análisis de ventas por tipo de producto |
| ⭐ **Evaluación promedio por cliente** | Cálculo del rating medio por tienda |
| 🛒 **Productos más y menos vendidos** | Identificación de extremos en cantidad de ventas |
| 🚚 **Costo de envío promedio** | Promedio del gasto logístico por tienda |
| 🗺️ **Análisis geoespacial (extra)** | Mapa con distribución de ventas por ciudad y tienda |

---

## 🧾 Estructura del Repositorio

```bash
📁 alura-store-challenge/
│
├── Challenge_Alura_Store_Cristian_Velasquez_Rios_(final).ipynb   # Notebook con análisis completo
├── README.md                                                      # Este archivo
├── /img                                                           # Capturas opcionales de visualizaciones
└── /data                                                          # Dataset consolidado (opcional)
