# 🛒 alura-store-challenge

**Challenge Data Science – Alura LATAM**

## 📊 Alura Store – Análisis de Ventas con Python

Este proyecto forma parte del **Challenge de Datos – Alura LATAM**.  
El objetivo es ayudar al Sr. Juan a tomar una **decisión estratégica**: vender una de sus cuatro tiendas virtuales en Colombia. A partir del análisis de ventas, categorías, evaluaciones de clientes, productos más/menos vendidos y costos logísticos, se determina **cuál tienda tiene un desempeño inferior**.

También se incluye un análisis **geográfico adicional (opcional)** para mapear la distribución de ventas a través de coordenadas geográficas.

---

## 🧠 Objetivos del Desafío

Tu jefe te ha pedido responder cinco preguntas clave:

1. 📈 **Facturación total por tienda** → ¿Cuál tienda vende más?
2. 🗂️ **Productos más vendidos por categoría y tienda** → ¿Qué se vende mejor en cada una?
3. 🌟 **Evaluación promedio de cada tienda** → ¿Qué opinan los clientes?
4. 📦 **Productos más y menos vendidos** → ¿Qué productos tienen mayor o menor salida?
5. 🚚 **Costo promedio de envío** → ¿Qué tan caro es despachar desde cada tienda?

---

## ✅ Resultados Clave

- **Bogotá** concentra la mayor facturación total.
- **Tienda 1 y Tienda 2** destacan en zonas urbanas densas (ej. Bogotá, Medellín).
- Existen productos con baja rotación que afectan el rendimiento general.
- Se detectan diferencias logísticas importantes entre tiendas.
- Las calificaciones promedio son positivas, pero **Tienda 4** tiene la más baja.

---

## 🧾 Conclusiones del Análisis

Este análisis integral permitió identificar la tienda con menor rendimiento considerando:

- Facturación total
- Popularidad y rotación de productos
- Evaluación promedio de clientes
- Costos logísticos de envío

**📌 Recomendación final:**  
> Se recomienda al Sr. Juan **vender la Tienda 4**, ya que presenta el desempeño más bajo en todos los indicadores clave.

🔎 *Consulta el archivo [Notebook del proyecto](./Challenge_Alura_Store_Cristian_Velasquez_Rios_(final).ipynb) para visualizar el análisis completo.*

---

## 🌍 Visualizaciones Geográficas (Extra)

Como parte opcional del desafío, se desarrolló un análisis geoespacial utilizando `Folium` y `Plotly` para evaluar:

### Herramientas utilizadas:
- `Folium` → Mapas interactivos con círculos proporcionales
- `Plotly` → Mapas de dispersión con escalas de color
- `Seaborn` → Heatmap para análisis por ciudad y tienda

### Hallazgos clave:

- **Bogotá** representa más del 25 % de las ventas en todas las tiendas.
- **Medellín y Cali** también muestran fuerte rendimiento comercial.
- **Tienda 2** lidera en Bogotá y Medellín.
- **Tienda 4** tiene buena cobertura geográfica, pero menor volumen total.
- Zonas con bajo desempeño (ej. Inírida, Valledupar) podrían requerir revisión logística o comercial.

---

## 🧪 Aprendizajes Aplicados

Durante el desarrollo del proyecto se aplicaron y consolidaron los siguientes conocimientos clave:

- 🧠 Lógica de programación con Python 
- 📊 Manipulación de datos con `groupby`, `pivot`, `merge`, `apply`
- ⚙️ Uso de condicionales y funciones para cálculos dinámicos
- 🧹 Limpieza y formateo de datos reales con estructuras eficientes
- 📉 Visualización comparativa usando `Matplotlib`, `Seaborn`, `Plotly` y `Folium`
- 📚 Desarrollo de storytelling visual basado en datos

---

## 📌 Conclusión

Este proyecto simula un caso real de **análisis de datos para la toma de decisiones comerciales**. Aplicamos conceptos clave de Python y análisis exploratorio para recomendar qué tienda tiene menor rendimiento.  
El enfoque final combina análisis **financiero, de producto, logístico y geográfico**.

---

## 👤 Autor

**Cristian Velásquez Ríos**  
📘 Análisis de Datos – Challenge Alura LATAM 2025  
✉️ [e-mail](cristian.velasquez.rios@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/cristianvelasquez/)

---

## 🚀 Cómo ejecutar este proyecto

1. Clona este repositorio  
2. Abre el archivo `.ipynb` en Google Colab o Jupyter Notebook  
3. Ejecuta cada celda siguiendo el flujo del análisis  
4. Observa los gráficos, resultados y conclusiones al final del notebook  

---

## 📂 Estructura del repositorio

```bash
📁 data/           # Dataset original del desafío
📁 img/            # Capturas o visuales opcionales
📄 Challenge_Alura_Store_Cristian_Velasquez_Rios_(final).ipynb  # Notebook principal
📄 README.md       # Este archivo
