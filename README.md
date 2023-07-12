# PROMO E, PROYECTO MÓDULO 1


## Descripción del proyecto:
Nuestro cliente está inmerso en un proceso activo de transformación digital, a raíz de esto nos ha mandando una serie de diferentes ficheros que contienen información relacionada entre si y desea obtener una base de datos que agregue toda la información en diferentes tablas.

De esta forma nos ha mandando 3 ficheros:

- Archivo en formato XML.
- Archivo en formato txt.
- Archivo en formato sql.

Para ello deberemos:

Primero: Crear la base de datos, inserción, modificación y extracción los ficheros de la base de datos a fichero externo.
Segundo: Limpiar de los datos de los ficheros xml automatizada.
Tercero: Limpiar de los datos de los ficheros txt automatizada.
Cuarto:  Insertar de los datos de los ficheros xml y txt a la BBDD mediante Python.
Quinto:  Automatizar de lectura de archivos, procesado y actualización de datos.

## Motivación de la realización del proyecto:

Realizar una serie de tablas finales que tengan la información parcialmente procesada y que se automatice todo el sistema de procesado de datos, ya que de forma periódica se recibirán otras remesas de datos similares actualizados.

## Lista de las librerías usadas para ejecutar el código.
 
 Las librerías que hemos usado han sido:
 
 os para Python (nos permite acceder a funcionalidades del sistema operativo)
 re para Python (para operaciones con expresiones regulares) 
 xml.etree.ElementTree as ET para XML (para trabajar con datos de ficheros xml)

## Estructura de las carpetas que tiene el proyecto

datos - SQLproyecto.sql - data_sql.sql - data_txt.txt - data_xml.xml
 
jupiter - SQL_creacion_BBDD.ipynb - read_xml_txt.ipynb - txt_limpio.ipynb - xml_limpio.ipynb