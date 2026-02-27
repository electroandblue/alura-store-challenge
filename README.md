# Challenge Alura Store - Data Science 📊

Este proyecto consiste en el análisis de datos de ventas de cuatro sucursales de Alura Store Latam para optimizar la toma de decisiones estratégicas.

## 📁 Estructura de los Datos
El conjunto de datos analizado incluye las siguientes dimensiones:
* **Producto y Categoría:** Artículos vendidos y sus respectivas categorías de mercado.
* **Precio y Envío:** Valores de venta al público y costos logísticos asociados.
* **Fecha y Ubicación:** Información temporal y geográfica de las transacciones.
* **Evaluación:** Calificaciones y comentarios dejados por los clientes (Satisfacción).
* **Pago y Cuotas:** Métodos de pago utilizados y financiamiento.
* **Coordenadas Geográficas:** Latitud y longitud para análisis de densidad de ventas.

## 📝 Puntos Desarrollados
1. **Análisis de facturación:** Cálculo del total de ventas por tienda para medir el flujo de ingresos.
2. **Ventas por categoría:** Identificación de las categorías de productos líderes, eliminando redundancias en los datos.
3. **Calificación promedio:** Evaluación de la satisfacción del cliente por sucursal (Métrica de calidad).
4. **Productos más y menos vendidos:** Ranking detallado con cantidades exactas para gestión de inventario.
5. **Costo de envío promedio:** Análisis de eficiencia logística y costos de transporte por sucursal.
6. **Visualización de datos:** Generación de gráficos (Barras y Pie) para comparar el lucro real y el rendimiento de las tiendas.

## 📊 Resumen de Resultados y Conclusiones
Tras consolidar los datos en un DataFrame de resumen y generar las visualizaciones, se presentan los siguientes hallazgos para el Señor Juan:

* **Rendimiento Financiero:** Se calculó el **Lucro Real** restando los costos de envío a la facturación total.
* **Decisión Estratégica:** Se determinó que la **Tienda 4** es la que presenta el menor lucro neto y una eficiencia logística inferior. 
* **Recomendación:** Se sugiere considerar la venta o cierre de la **Tienda 4** para reasignar capital a las sucursales más rentables y optimizar la operación global de Alura Store.

## 🛠️ Tecnologías utilizadas
* **Python**: Con la librería Pandas para el procesamiento de datos y Matplotlib para la visualización.
* **Google Colab**: Entorno de desarrollo interactivo.
* **Git & GitHub**: Control de versiones y documentación del proyecto.
