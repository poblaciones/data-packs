# Argentina
data-pack para Poblaciones.

Esta data-pack permite insertar cartografías de base y regiones de recorte para una instalación de la aplicación web Poblaciones. 

NOTA: Esta descarga no incluye información en formato .shp sino solamente registros para el uso en la instalación de Poblaciones.

## Geographies

Las cartografías de base incluidas en el data-pack son:

* Cartografía censal 2010
  * Provincias 
  * Departamentos 
  * Radios 
* Cartografía censal 2001
  * Provincias 
  * Departamentos 
  * Radios 
* Cartografía censal 1991
  * Provincias 
  * Departamentos 
  * Radios 

Las cartografías derivan de la cartografía censal de la Argentina revisada y corregida por Gonzalo Rodriguez (CEUR/CONICET). http://www.ceur-conicet.gov.ar/novedad.php?novedad_id=77

## Clipping Regions

Las regiones de recorte incluidas en el data-pack son:

* Regiones: según cartografía censal 2010.
* Provincias: según cartografía censal 2010.
* Departamentos: según cartografía censal 2010.
* Aglomerados: según cartografía censal 2010.
* Localidades: según Open Streetmap (OSM).
* Municipios: según cartografía IGN + OSM + reconstrucción ad-hoc.
* Barrios: según cartografía oficial + OSM.
* Comunas (CABA): según cartografía oficial.
* Distritos Escolares (CABA): según cartografía oficial.

## Instalación

Para utilizar el data-pack:

1. Realizar la instalación de una base de datos vacía de Poblaciones (con el script del repositorio /poblaciones/startup/dbscript-v1.sql).

2. Expandir el archivo argentina.zip (incluyendo los archivos z01, z02, z03 y z04). Ejecutar el script argentina_v2.23.sql allí contenido.

3. En la consola de administración (sitio/admin), dirigirse a Configuración > Cachés y presionar 'Actualizar' en los cachés de Geografías, Regiones por Geografías y Lookup de Regiones para regenerar los cachés de la instalación con la nueva información.

