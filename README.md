
# Web Scraping

## Resumen
En este proyecto he realizado un scraping de una web fija en el tiempo, para no alterar lo resultados. Se extraeran detalles de los anuncios de viviendas en venta de todas las páginas disponibles en la web www.century21.com. 
El objetivo es extraer información relevante de cada anuncio (como precio, ubicación, tamaño, etc.) y almacenarla en un archivo CSV para su posterior análisis.

## Información extraída
Cada fila del archivo CSV contiene datos sobre un inmueble, incluyendo:

- Dirección
- Localidad
- Precio
- Habitaciones
- Superficie
- Baños completos
- Aseos
- Tamaño del terreno

## Tecnologías utilizadas

- Python
- Jupyter Notebook

Librerías:
- requests
- BeautifulSoup
- pandas
- time
- random

## Posibles mejoras

- Realizar scraping sobre una web dinámica y no fija.
- Guardar los datos directamente en una base de datos SQL o NoSQL.
- Añadir filtros de búsqueda personalizados.
