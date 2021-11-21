# CUIT_DATABASE_SCRAPING
Base de Datos extraída de https://www.cuitonline.com , más de 26 millones de personas.

## Como se logró extraer toda esta informacíon ?

esta pagina web que contiene una enorme base de datos de personas de Argentina indexa las personas de la siguiente manera:

https://www.cuitonline.com/detalle/NUMERO_DNI/NOMBRE_COMPLETO.html.

Al mirar el sitemap (https://www.cuitonline.com/sitemap.xml) se ve que todos los links se encuentras agrupados en archivos comprimidos .gz
Hay multiples archivos pero solo nos interesan los que tengan el nombre https://www.cuitonline.com/sitemaps/sitemap-detalle-numero.xml.gz

Finalmente armando una notebook en collab usando python y algunos comandos de linux que facilitan la extraccion de los archivos .gz se puedo armar estos .CSV

## Descargar:

* Base de datos completa(INCLUYE PERSONAS HUMANAS Y JURIDICAS)
* FORMATO .CSV
https://drive.google.com/file/d/1Bhkb121EbSvH80hSNKrmjvLOv0Mxd2co/view?usp=sharing

* Base de datos solo personas(DNI , NOMBRE COMPLETO Y CUIT)
* FORMATO .CSV
https://drive.google.com/file/d/1VGTBP2pD7mvH1CcC9-ai9Nqe74iGHAth/view?usp=sharing
