# Scrapping web
Este código es un ejemplo de cómo extraer las URLs de una página web usando Python. El código hace lo siguiente:

- Importa los módulos necesarios: requests, BeautifulSoup y pandas.
- Define la URL de la página web que se quiere raspar: https://www.universidadeuropea.com.
- Envía una petición a la página web y obtiene la respuesta HTML.
- Analiza el contenido HTML usando BeautifulSoup.
- Encuentra todas las URLs que hay en la página web y las guarda en una lista.
- Crea un DataFrame para almacenar las URLs.
- Exporta el DataFrame a un archivo Excel llamado urls.xlsx.

# English version
This code is an example of how to scrape the URLs from a web page using Python. The code does the following:

- Imports the necessary modules: requests, BeautifulSoup and pandas.
- Defines the URL of the web page that you want to scrape: https://www.universidadeuropea.com.
- Sends a request to the web page and gets the HTML response.
- Parses the HTML content using BeautifulSoup.
- Finds all the URLs that are on the web page and saves them in a list.
- Creates a DataFrame to store the URLs.
- Exports the DataFrame to an Excel file named urls.xlsx.
