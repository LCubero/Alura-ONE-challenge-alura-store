# 🏪 Alura ONE Challenge – Alura Store

## 📋 Descripción del proyecto
Este proyecto forma parte del **Challenge Alura ONE**, y consiste en realizar un **análisis de datos de ventas** de cuatro tiendas pertenecientes a la plataforma **Alura Store**.  
El objetivo principal es ayudar al **Sr. Juan**, propietario de las tiendas, a decidir **cuál tienda vender** para iniciar un nuevo emprendimiento, con base en información objetiva obtenida del análisis de datos.

---

## 🎯 Objetivos del análisis

El análisis se centró en los siguientes puntos:

1. **Facturación total por tienda**  
   Determinar cuál tienda genera mayores y menores ingresos.

2. **Categorías más populares**  
   Identificar las categorías de productos con mayor volumen de ventas.

3. **Calificaciones promedio de los clientes**  
   Evaluar el nivel de satisfacción de los clientes en cada tienda.

4. **Productos más y menos vendidos**  
   Reconocer los productos con mayor y menor rotación.

5. **Costo promedio de envío**  
   Calcular el valor medio del envío para cada tienda.

6. **Análisis geográfico (Extra opcional)**  
   Examinar las coordenadas geográficas (latitud y longitud) para identificar patrones de ubicación o concentración de ventas.

---

## 🧰 Tecnologías utilizadas

- **Python 3** 🐍  
- **Pandas** → Manipulación y análisis de datos  
- **Matplotlib** → Visualización y gráficos  
- **Google Colab** → Entorno de desarrollo y ejecución  

---

## 🧮 Proceso del análisis

1. **Carga y limpieza de datos:**  
   Se importaron los archivos CSV de las cuatro tiendas y se verificó la consistencia de columnas y valores nulos.

2. **Cálculo de métricas principales:**  
   Se calcularon ingresos totales, calificaciones promedio, ventas por categoría, productos más y menos vendidos, y promedio de costos de envío.

3. **Generación de visualizaciones:**  
   Se crearon gráficos de barras, circulares, de dispersión y de calor para representar los resultados de forma clara y visual.

4. **Análisis geográfico (extra):**  
   Se utilizaron las columnas `lat` y `lon` para mapear las ventas.  
   Se descubrió que las cuatro tiendas operan en las **mismas 19 coordenadas geográficas**, por lo que **no existen diferencias regionales** entre ellas.

---

## 📈 Resultados principales

- **Tienda 1** presenta los **mayores ingresos totales**, siendo la más rentable.  
- **Tienda 4** obtiene los **menores ingresos**, convirtiéndose en la menos eficiente.  
- Todas las tiendas comparten las mismas categorías y ubicaciones, por lo que las diferencias de rendimiento **no están relacionadas con la ubicación geográfica**.  
- Las calificaciones y los productos vendidos refuerzan el menor desempeño general de la **Tienda 4**.

---

## ✅ Conclusión

Tras analizar todos los factores, se recomienda que el **Sr. Juan venda la Tienda 4**, ya que presenta el **menor rendimiento general** en ingresos y rotación de productos.  
Las demás tiendas muestran un desempeño estable y mayor potencial de crecimiento.

---

## 🌍 Extra geográfico

El análisis de las coordenadas geográficas demostró que las cuatro tiendas venden en **los mismos puntos de venta**, sin diferencias de cobertura o concentración.  
Por lo tanto, **la ubicación no influye en los resultados**. Las variaciones se explican por aspectos comerciales y de gestión.

---
