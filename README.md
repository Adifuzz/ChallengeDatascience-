# ChallengeDatascience-

📊 Análisis de Ventas por Tienda – Proyecto Data Science
🎯 Propósito del Análisis
El propósito de este análisis es ayudar al Sr. Juan a tomar una decisión informada sobre en qué tienda debería vender sus productos. Para ello, se analizan y comparan los datos de ventas de cuatro tiendas distintas, considerando aspectos clave como:

Ingresos totales por tienda.

Categorías de productos más y menos vendidos.

Calificaciones promedio de los clientes.

Productos más y menos vendidos.

Coste de envío promedio.

Distribución geográfica de las ventas (Extra/Desafío opcional).

Este análisis combina técnicas de limpieza, visualización y exploración de datos usando Python y bibliotecas como pandas, matplotlib, seaborn y folium.

🗂️ Estructura del Proyecto
bash
Copiar
Editar
proyecto_ventas_tiendas/
│
├── notebook.ipynb                # Notebook principal con análisis y visualizaciones
├── README.md                     # (Opcional) Descripción del proyecto
├── data/                         # Carpeta virtual de datos
│   ├── tienda_1.csv              # Datos de la tienda 1
│   ├── tienda_2.csv              # Datos de la tienda 2
│   ├── tienda_3.csv              # Datos de la tienda 3
│   └── tienda_4.csv              # Datos de la tienda 4
⚠️ En Google Colab no es necesario descargar los archivos si se utilizan los enlaces CSV desde GitHub.

📈 Ejemplos de Gráficos e Insights
✅ Ingresos Totales
Gráfico de barras que compara el ingreso total generado por cada tienda. La Tienda 3 lidera en ventas, seguida de la Tienda 1.

✅ Calificaciones Promedio
Se observa que la Tienda 1 tiene la mejor calificación promedio (4.31), lo que indica mayor satisfacción de los clientes.

✅ Categorías Más Vendidas
Las categorías más populares son Electrónica y Hogar en todas las tiendas. Las categorías menos vendidas varían según la tienda (ej: Ropa, Deportes, Juguetes).

✅ Costos de Envío
La Tienda 2 ofrece el costo de envío más bajo, mientras que la Tienda 4 tiene el más alto.

🌍 Distribución Geográfica (Extra)
Mediante gráficos de dispersión y mapas de calor se visualiza la concentración de ventas por ubicación. Se detectaron zonas urbanas con mayor volumen de ventas.

▶️ Instrucciones para Ejecutar el Notebook
Abre el archivo notebook.ipynb en Google Colab.

Asegúrate de tener conexión a internet, ya que los datos se cargan desde GitHub.

Ejecuta las celdas paso a paso (menú: Entorno de ejecución > Ejecutar todo).

Observa los gráficos generados para cada sección del análisis.

Revisa la conclusión final, donde se recomienda la tienda más conveniente para el Sr. Juan, con justificación basada en los datos analizados.
