# Argentina
data-pack para Poblaciones.

Esta data-pack permite insertar cartograf�as de base y regiones de recorte para una instalaci�n de la aplicaci�n web Poblaciones. 

NOTA: Esta descarga no incluye informaci�n en formato .shp sino solamente registros para el uso en la instalaci�n de Poblaciones.

## Geographies

Las cartograf�as de base incluidas en el data-pack son:

* Cartograf�a censal 2010
  * Provincias 
  * Departamentos 
  * Radios 
* Cartograf�a censal 2001
  * Provincias 
  * Departamentos 
  * Radios 
* Cartograf�a censal 1991
  * Provincias 
  * Departamentos 
  * Radios 

Las cartograf�as derivan de la cartograf�a censal de la Argentina revisada y corregida por Gonzalo Rodriguez (CEUR/CONICET). http://www.ceur-conicet.gov.ar/novedad.php?novedad_id=77

## Clipping Regions

Las regiones de recorte incluidas en el data-pack son:

* Regiones: seg�n cartograf�a censal 2010.
* Provincias: seg�n cartograf�a censal 2010.
* Departamentos: seg�n cartograf�a censal 2010.
* Aglomerados: seg�n cartograf�a censal 2010.
* Localidades: seg�n Open Streetmap (OSM).
* Municipios: seg�n cartograf�a IGN + OSM + reconstrucci�n ad-hoc.
* Barrios: seg�n cartograf�a oficial + OSM.
* Comunas (CABA): seg�n cartograf�a oficial.
* Distritos Escolares (CABA): seg�n cartograf�a oficial.

## Instalaci�n

Para utilizar el data-pack:

1. Realizar la instalaci�n de una base de datos vac�a de Poblaciones (con el script del repositorio /poblaciones/startup/dbscript-v1.sql).

2. Expandir el archivo argentina.zip (incluyendo los archivos z01, z02, z03 y z04). Ejecutar el script argentina_v2.23.sql all� contenido.

3. En la consola de administraci�n (sitio/admin), dirigirse a Configuraci�n > Cach�s y presionar 'Actualizar' en los cach�s de Geograf�as, Regiones por Geograf�as y Lookup de Regiones para regenerar los cach�s de la instalaci�n con la nueva informaci�n.

