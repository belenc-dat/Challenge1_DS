# Challenge1_DS

# 📊 Análisis de Tiendas Alura Store

## 1. Propósito del Análisis
El objetivo principal de este proyecto es determinar **cuál de las cuatro tiendas de la cadena Alura Store debe ser vendida** para iniciar un nuevo emprendimiento.  
La decisión se basa en identificar la tienda menos eficiente en la generación de ganancias, utilizando métricas clave de **ventas, rendimiento y satisfacción del cliente**.

---

## 2. Estructura del Proyecto y Organización de Archivos
El proyecto se organiza en un único **notebook de Google Colab** que incluye:

- **Importación de datos**: carga de los archivos CSV en DataFrames de pandas (`tienda1`, `tienda2`, `tienda3`, `tienda4`).  
- **Análisis de facturación**: cálculo de ingresos totales por tienda.  
- **Ventas por categoría**: distribución y valor de ventas por categoría de producto.  
- **Calificación promedio**: satisfacción promedio de los clientes por tienda.  
- **Productos más y menos vendidos**: identificación de los productos con mayor y menor facturación.  
- **Envío promedio**: cálculo del coste de envío promedio por tienda.  
- **Visualizaciones**: gráficos para mostrar los resultados clave.  
- **Informe final**: conclusiones y recomendación basada en el análisis.

Los datos provienen de **cuatro archivos CSV externos** alojados en un repositorio de GitHub, uno por cada tienda.

---

## 3. Ejemplos de Gráficos e Insights Obtenidos

### Gráfico 1: Ingresos Totales por Tienda (Barras)
- **Insight**: La **Tienda 1** genera mayores ingresos, mientras que la **Tienda 4** obtiene los menores.  
  → Este hallazgo fue clave para la recomendación final.

### Gráfico 2: Ingresos Totales por Categoría (Barras Horizontales)
- **Insight**: Las categorías **Electrónicos** y **Electrodomésticos** aportan la mayor parte de los ingresos en todas las tiendas.  
  → Destacan como estratégicas para la cadena.

### Gráfico 3: Proporción del Costo de Envío Promedio por Tienda (Circular)
- **Insight**: La **Tienda 1** tiene el coste de envío más alto, mientras que la **Tienda 4** el más bajo.  
  → Los bajos costes de envío de la Tienda 4 no compensan sus menores ingresos.

### Gráfico 4: Calificación Promedio por Tienda (Líneas)
- **Insight**: Las calificaciones son similares (entre 3.97 y 4.05).  
  → La **Tienda 3** destaca ligeramente por encima y la **Tienda 1** por debajo.

---

## 4. Instrucciones para Ejecutar el Notebook
Para replicar el análisis en Google Colab:

1. **Abrir en Google Colab**
2. **Ejecutar las celdas secuencialmente**: haz clic en el botón ▶️ de cada celda o usa *Entorno de ejecución > Ejecutar todo*.  
3. **Visualizar resultados**: los gráficos y métricas aparecerán debajo de cada celda.  
4. **Revisar el Informe Final**: al final del notebook encontrarás las conclusiones y la recomendación sobre qué tienda vender.

---

## ✅ Se determinó que la **Tienda 4 es la menos eficiente**, ya que presenta los **menores ingresos totales**, a pesar de tener costes de envío bajos y calificaciones aceptables.  
Por ello, se recomienda vender esta tienda para liberar recursos e impulsar el nuevo emprendimiento del Sr. Juan.
