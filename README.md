# Proyecto Airbnb Argentina

Este proyecto tiene como objetivo analizar los datos de Airbnb en Argentina, utilizando herramientas de Python y Power BI. El propósito es obtener información sobre el mercado de alojamiento, las preferencias de los viajeros, los precios, las ubicaciones y las tendencias.

## ETL en Python

Para realizar el proceso de extracción, transformación y carga (ETL) de los datos, se utilizó el lenguaje de programación Python. Se descargaron los datos de Airbnb desde el sitio web [Inside Airbnb](http://insideairbnb.com/get-the-data.html), que ofrece datos públicos sobre los anuncios de Airbnb en diferentes ciudades del mundo. Se seleccionaron los archivos correspondientes a Buenos Aires, Córdoba, Mendoza y Bariloche, que son las principales ciudades turísticas de Argentina.

Se realizó un análisis exploratorio de los datos, para verificar su calidad, completitud y consistencia. Se identificaron y eliminaron los valores faltantes, duplicados y erróneos. Se aplicaron técnicas de limpieza y normalización de los datos, como la conversión de tipos de datos, la estandarización de formatos y la eliminación de caracteres especiales. Se realizaron operaciones de agregación, filtrado, agrupación y unión de los datos, para obtener las variables de interés para el análisis. Se generaron nuevas columnas con información derivada, como el precio por noche, el precio por persona, la ocupación y la rentabilidad.

Finalmente, se exportaron los datos transformados a un archivo CSV, que se utilizó como fuente de datos para Power BI.

## Dashboard en Power BI

Para realizar la visualización y el análisis de los datos, se utilizó la herramienta Power BI. Se importó el archivo CSV generado en el paso anterior, y se creó un modelo de datos con las tablas y las relaciones necesarias. Se definieron las medidas y los cálculos que se utilizaron para generar los indicadores y las gráficas.

Se diseñó un dashboard interactivo, que permite explorar los datos de Airbnb en Argentina desde diferentes perspectivas. El dashboard consta de las siguientes secciones:

- Resumen general: muestra el número de anuncios, el número de huéspedes, el precio promedio y la ocupación promedio de Airbnb en Argentina, así como su distribución por ciudad y por tipo de alojamiento.
- Análisis de precios: muestra la distribución de los precios por noche y por persona, así como el ranking de los alojamientos más caros y más baratos por ciudad.
- Análisis de tendencias: muestra la evolución de los anuncios, los huéspedes, los precios y la ocupación de Airbnb en Argentina a lo largo del tiempo, así como la estacionalidad y la variación por mes y por día de la semana.
- Análisi de sentimiento segpun los reviews de los clientes. 

El dashboard permite al usuario interactuar con los datos, seleccionando diferentes filtros, segmentos y niveles de detalle. El dashboard ofrece una visión integral y dinámica de los datos de Airbnb en Argentina, facilitando la comprensión y el descubrimiento de patrones e insights.
