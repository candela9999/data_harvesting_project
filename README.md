# data_harvesting_project
This project aims to analyze the spatial distribution of public housing and leisure spaces in Madrid using data harvesting techniques

## holi
The study comprises three main parts:

1. Scrapping Public Housing Data:

Utilizes web scraping techniques, including Selenium, to extract information about public housing from the Empresa Municipal de la Vivienda y Suelo (EMVS) website. 
Extracts the number of dwellings and the district for each housing development.

2. Using Ayuntamiento de Madrid's Datos Abiertos API:

Accesses data about leisure spaces such as theaters, concert halls, cinemas, and parks using the Ayuntamiento de Madrid's Datos Abiertos API, including data extraction, JSON formatting, and location data storage.

3. Data Visualization:

Visualizes the distribution of public housing and leisure spots to observe any potential pattern or trend.

Instructions:

- Ensure Selenium is installed before running the code.
- Ensure all necessary packages are available before running the code.
- Have the required district database files available in .dbf, .prj, .shp, and .shx formats for proper map creation.
- Save these files in the same folder as the script or in a location accessible to the script.
- Execute the code while following the provided comments.
