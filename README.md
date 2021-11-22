# CUIT_DATABASE_SCRAPING
Base de Datos extraída de https://www.cuitonline.com , más de 27 millones de personas con CUITs , Nombres completos y DNI.
Incluye tanto personas fisicas como juridicas 


![alt text](https://www.cuitonline.com/images/logo-header.png)

## Como se logró extraer toda esta informacíon ?

esta pagina web que contiene una enorme base de datos de personas de Argentina indexa las personas de la siguiente manera:

https://www.cuitonline.com/detalle/NUMERO_DNI/NOMBRE_COMPLETO.html.

Al mirar el sitemap (https://www.cuitonline.com/sitemap.xml) se ve que todos los links se encuentras agrupados en archivos comprimidos .gz
Hay multiples archivos pero solo nos interesan los que tengan el nombre https://www.cuitonline.com/sitemaps/sitemap-detalle-numero.xml.gz

Finalmente armando una notebook en collab usando python y algunos comandos de linux que facilitan la extraccion de los archivos .gz se puedo armar estos .CSV

## Es util esto para algo ?

Puede ser usado para OSINT , modelos de machine learning y para analisis de datos. Muy probablemente estos datos por si solos no sirvan de mucho , va a ser necesario más infromacíon.

## ESTAN LOS DATOS DE TODAS LAS PERSONAS DE ARGENTINA !?!?!?

Por lo que puede ver a simple vista no...de la base de datos hay mas o menos un millon de personas jurídicas. Teniendo entonces 26 millones de personas humanas en la base de datos.

Argentina tiene mas de 45.38 millones de personas por lo que faltan bastantes. 

Personas que pueden no estar en la base de datos : menores de edad , politicos y famosos que no quieren que sepan datos de ellos (algunos estan ).

Hay una gran chance de que multiples personas estén fallecidas ya que existen personas registradas con DNIs de un digito.

## Descargar en .CSV ( Pesan un poco mas de 1 GB cada una):

* Base de datos completa(INCLUYE PERSONAS HUMANAS Y JURIDICAS):

https://www.mediafire.com/file/h6zm51yr41flz54/DB_CUIT_22OCT21.csv/file

* Base de datos solo personas(DNI , NOMBRE COMPLETO Y CUIT):

https://www.mediafire.com/file/hh1w659bc5j5hgu/CUITS-MYF.csv/file

