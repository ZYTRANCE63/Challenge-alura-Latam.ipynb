
# 📑 README.md: Análisis Consolidado Alura Store Latam

Este repositorio contiene el análisis de ventas consolidado de cuatro tiendas (tienda_1.csv a tienda_4.csv) de la marca Alura Store Latam. El análisis fue realizado utilizando Python y la librería Pandas, con el objetivo de obtener una visión integral del rendimiento del negocio.

🎯 Propósito del Análisis
El objetivo principal de este proyecto es transformar datos brutos de ventas en insights accionables para la toma de decisiones estratégicas. Específicamente, el análisis busca:

Medir el Rendimiento Global: Cuantificar la facturación total, la ganancia bruta y las métricas operacionales clave (promedio de calificación, costo de envío).

Identificar Impulsores de Crecimiento: Determinar las categorías y productos que generan la mayor parte de los ingresos y el volumen de ventas.

Detectar Ineficiencias: Señalar la unidad de negocio menos rentable para proponer una reestructuración o venta (ej. la tienda con la menor ganancia bruta).

Evaluar la Satisfacción del Cliente: Entender el nivel general de servicio a través de la calificación promedio.

📂 Estructura del Proyecto y Organización de ArchivosEl proyecto se organiza en una estructura simple para la carga y ejecución:.

├── AluraStoreLatam.ipynb      # Notebook principal con todo el código Python y los insights.

├── tienda_1.csv               # Datos de transacciones de la Tienda 1 (Formato CSV).

├── tienda_2.csv               # Datos de transacciones de la Tienda 2 (Formato CSV).

├── tienda_3.csv               # Datos de transacciones de la Tienda 3 (Formato CSV).

└── tienda_4.csv               # Datos de transacciones de la Tienda 4 (Formato CSV).

El notebook AluraStoreLatam.ipynb contiene los pasos para cargar, limpiar, consolidar y analizar los cuatro archivos CSV.💡 Ejemplos de Gráficos e Insights ObtenidosTópico AnalizadoInsight ClaveFacturación TotalEl Ingreso Total combinado supera los **$695 millones**.RentabilidadLa Tienda 3 es la menos lucrativa, registrando la menor Ganancia Bruta ($160.4M), principalmente debido a un Costo de Envío excesivamente alto.Categorías PopularesMuebles es la categoría líder tanto en ingresos (22.64%) como en volumen de ventas, seguida de cerca por Electrodomésticos y Electrónicos.Ventas por ProductoLos productos más vendidos son: Mesa de centro, Silla de oficina y Mesa de comedor.SatisfacciónLa Calificación Promedio General es de 3.01 / 5, indicando una necesidad de mejorar la experiencia del cliente para superar las expectativas básicas.LogísticaEl Costo Promedio de Envío por transacción varía significativamente entre tiendas, siendo un punto crítico de optimización.

Visualización Sugerida (Ejemplo):⚙️ Instrucciones para Ejecutar el NotebookPara replicar el análisis, siga los siguientes pasos:Requisitos: Asegúrese de tener Python instalado, junto con las librerías pandas y numpy.Bashpip install pandas numpy
Organización de Archivos: Coloque el notebook (AluraStoreLatam.ipynb) y los cuatro archivos CSV (tienda_1.csv, tienda_2.csv, tienda_3.csv, tienda_4.csv) en la misma carpeta.Ejecución:Abra el notebook utilizando Jupyter Notebook o Google Colab.Ejecute todas las celdas en secuencia. El código está diseñado para cargar y consolidar automáticamente los datos antes de proceder con el análisis.Verifique las salidas de cada sección para obtener las tablas de resultados y las conclusiones.