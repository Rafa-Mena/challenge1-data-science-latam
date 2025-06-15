![Análisis de Tiendas](banner.png)

# 📊 Análisis de Tiendas - Reto de Ciencia de Datos

Este proyecto tiene como objetivo ayudar al Sr. João a tomar una decisión informada sobre cuál de las cuatro tiendas de su cadena **Alura Store** debería vender o cerrar, con base en el análisis de datos reales de ventas, calificaciones, envíos y productos.

---

## 📁 Estructura del proyecto

- `reto_alura_store.ipynb`: notebook de Google Colab donde se realizó todo el análisis paso a paso.
- `README.md`: este archivo, con detalles del análisis y cómo interpretarlo.

---

## 🧰 Herramientas utilizadas

- `Python`
- `Pandas` para manipulación de datos
- `Matplotlib` y `Seaborn` para visualización
- `Google Colab` como entorno de desarrollo

---

## 📌 Paso a paso del análisis

### 1. Importación de datos
Se cargaron 4 archivos `.csv` desde GitHub correspondientes a las tiendas 1, 2, 3 y 4. Se unificaron en un solo DataFrame con una columna adicional `Tienda` para identificar el origen de cada registro.

### 2. Análisis exploratorio por tienda
Se analizaron distintas métricas:

- **Facturación total**: suma de ingresos por tienda.
- **Ventas por categoría**: cantidad de productos vendidos por tipo.
- **Calificación promedio**: puntuación promedio dada por los clientes.
- **Productos más y menos vendidos**: identificados por frecuencia.
- **Costo promedio de envío**: eficiencia logística comparada.

Cada uno de estos análisis fue acompañado de gráficos ordenados, visualmente accesibles y explicativos.

---

## 🔗 Datos utilizados

Los archivos utilizados en este análisis están disponibles públicamente y fueron cargados directamente desde GitHub:

- 📄 [Tienda 1](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_1%20.csv)
- 📄 [Tienda 2](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_2.csv)
- 📄 [Tienda 3](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_3.csv)
- 📄 [Tienda 4](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_4.csv)

---

## 📊 Visualizaciones

- Gráficos de barras horizontales para facilitar la lectura de categorías y productos.
- Colores accesibles para personas con daltonismo (`colorblind palette`).
- Textos informativos dentro de los gráficos.
- Gráfico de comparación directa entre producto más y menos vendido.

---

## ✅ Conclusión del análisis

Tras evaluar todas las métricas, se concluyó que **la Tienda 4 presenta el rendimiento general más bajo**:

- Tiene la facturación más baja.
- No se destaca ni en productos ni en categorías vendidas.
- Su calificación es buena, pero no la mejor.
- Su costo de envío no es el más competitivo.

Por lo tanto, se recomienda al Sr. João considerar la venta o reestructuración de la Tienda 4.

---

## ✍️ Autor

Este proyecto fue realizado por **Rafael** como parte de un reto práctico de ciencia de datos.  
Se utilizó un enfoque analítico, visual y accesible para comunicar claramente los resultados.

---

## 🚀 Cómo ver el proyecto

1. Abrir el notebook `reto_alura_store.ipynb` en Google Colab o Jupyter.
2. Ejecutar las celdas en orden para reproducir todo el análisis.
3. Consultar este README como guía de navegación y contexto.
