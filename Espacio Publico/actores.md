# Lista de Actores que pueden interacturar con la aplicación
* Ciudadano(Peaton) 1
* Dueño del Vehículo 2
* RUNT 3
* Secretaría Movilidad 4
* Policía de Transito 5
* Parqueaderos públicos 6

## Actores secundarios
* valet-parking 7
* Poder del cono 8
* Redes Sociales 9


# Descrición de los Actores
## Ciudadano(Peaton) 1
> Usuario quien va a realizar el respectivo reporte por medio de la aplicación movil, con tan solo dar click para tomar una foto a la placa del vehículo y teniendo el GPS activado

## Dueño del Vehículo 2
> Usuario quíen cometió una infracción al estacionar el vehículo en un lugar prohivido y zona peatonal, al actor le llega una notificación informandole que se encuentra mal parquedado junto con la locación y foto del vehículo y dará información de parqueaderos cercanos

## RUNT 3
> Entidad donde se consulta la información del actor Dueño del Vehículo y sacará los datos de Nombre y Número Celular para enviar la notificación correspondiente.

## Secretaría Movilidad 4
> Entidad quien estará interesado en análizar los datos reportados por los actores Ciudadano para realizar toma de deciciones

## Policía de Transito 5
> Entidad quien tienen autoridad para realizar multas o llamados de atención al actor Dueño del Vehículo

## Parqueaderos públicos 6
> Sector económico que puede puede ayudar al actor Dueño del Vehículo para encontran un parqueadero cercano

## Valet-parking 7
> El actor de Parqueaderos Públicos puede generar empleo a personal para parquear los vehículos del actor Dueño del Vehículo

## Poder del cono 8
> Actor con el cual se puede asociar he interacturar para generar conciencia al actor Dueño del Vehículo

## Redes Sociales 9
> Actor donde se publicará los infractores recurrentes 

# Atributos
## Ciudadano(Peaton) 1
> * Placa *varchar*
> * Longitud *float*
> * Latitud *float*
> * Fecha *date*
> * Hora *time*
> * IP Internet Celular *varchar* *Dato Privado* 
> * MAC Celular *varchar* *Dato Privado*
> * # Celular *numeric* *Dato Privado*
> *Datos Privado = Log y análsis de datos a la entidad competente*

## Dueño del Vehículo 2
> * Nombre *varchar*
> * Apellido *varchar*
> * # Celular *numeric*
> * Placa *varchar*

## RUNT 3
> * IP *varchar*
> * API *varchar*
> * Placa *varchar*

## Secretaría Movilidad 4
> Datos del Usuario quien reporta
> * Placa *varchar*
> * Longitud *float*
> * Latitud *float*
> * Fecha *date*
> * Hora *time*
> * IP Internet Celular *varchar* *Dato Privado* 
> * MAC Celular *varchar* *Dato Privado*
> * # Celular *numeric* *Dato Privado*
> Datos dueño del vehículo
> * Nombre *varchar*
> * Apellido *varchar*
> * # Celular *numeric*

## Policía de Transito 5
> 


