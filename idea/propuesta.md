#Propuesta


Descripción de la solución del proyecto Co-Mapp



Nuestra solución <Inserte el nombre aquí> consiste en 2 secciones. La primera parte sugerimos herramientas ya pre-existentes de captura de datos que proveen los requerimientos descritos en la convocatoria que incluyan un sistema de creación de encuestas dinámicas, con capacidad de trabajo sin internet y que permita capturar datos de geolocalización y que se pueda trabajar en un sistema móvil. 

Para esta parte recomendamos las siguientes aplicaciones:



HarvestYourData
https://www.harvestyourdata.com/features/

Puede utilizarse para Teléfonos y tablets (Android and Apple)
Puedes trabajar con la aplicación offline
Soporta multiples usuarios
Registra las coordenadas de cada encuesta
Notificaciones inmediatas si una encuesta realizada muestra exactamente lo que andabas buscando
Base de datos segura ya que es en un server propio.
Tiene un Dashboard con mapas de Google.
Las encuestas pueden exportarse fácilmente a CSV y archivos SPSS

Costos, solo se paga el tiempo que se está encuestando. 

1 Mes     0%     $89 dolares
2 Meses   0%     $178 dolares
3 Meses   0%     $267 dolares
6 Meses     25%     $400 dolares
9 Meses     38%     $495 dolares
12 Meses    45%     $587 dolares







Survelytics - Mobile Surveys
http://www.survelytics.com/mobile-surveys.html

Puede utilizarse para Teléfonos y tablets (Android and Apple)
Puedes trabajar con la aplicación offline
Soporta múltiples usuarios, pero hay que negociar sobre los autores.
Registra las coordenadas de cada encuesta
Puedes capturar Video y audio
Tiene soporte de diferentes idiomas
Ofrece seguridad en los datos en todos los niveles del uso
Puedes exportar a formatos CSV, XL y SSS.


Costos





Quick Tap Survey 
http://www.quicktapsurvey.com

Puede utilizarse para Teléfonos y tablets (Android and Apple)
Puedes trabajar con la aplicación offline
Soporta múltiples usuarios.
Registra las coordenadas de cada encuesta
Puedes capturar Video y audio
Tiene soporte de diferentes idiomas
Ofrece seguridad en los datos en todos los niveles del uso
Puedes exportar a formatos CSV, PDF y otros formatos

Costo: 19 dolares al mes, incluye licencia de un dispositivo movil, hay que pagar 9 dolares por cada dispositivo extra. 


Data winners
https://www.datawinners.com/en/pricing/

Puede utilizarse para Teléfonos y tablets (Android)
Puedes trabajar con la aplicación offline
Soporta múltiples usuarios.
Registra las coordenadas de cada encuesta
Puedes capturar Video y audio
Ofrece seguridad en la nube
Puedes exportar a diferentes formatos.

Costo: Primer año gratis, despues 99 dolares al mes











La siguiente parte de la solución es la creación de un Sitio Web que provea la visualización de los datos en forma de mapa coroplético, con varias capas de información que permita captar mejor las zonas que son de riesgo para habitar y hacer comparaciones entre datos. 

Esta parte de la solución está basada en el software libre y gratuito llamado GeoShape (http://geoshape.org/) el cual ofrece la posibilidad de crear, compartir y visualizar mapas colaborativos. El cual contiene diferentes componentes que cubren todas las características de este reto los cuales describirémos a continuación con más detalle:

GeoServer: Servidor que permite a los usuario visualizar y editar datos geospaciales. 

GeoGig: Herramienta que permite el seguimiento de cambios en mapas similar a Github. Asi como también permite que la información sea más fácilmente compartida entre diferentes comunidades. 

GeoNode: Aplicacion web para mostrar contenido geospacial

MapLoom: Cliente Web que permite trabajar con diferentes mapas.

Arbiter: Aplicación móvil para trabajar con mapas ( no tiene servicio de encuestas)


Esta solución tendría que estar montada en un servidor  con los siguientes requerimientos mínimos del equipo.


Ubuntu Server Operating System 10GB RAM (Note: 60% de la memoria será asignada a uso de tomcat en el Server de Ubuntu)
Dual Core 2 GHz CPU
100 GB de espacio en disco duro.


Azure tiene soporte para ubuntu, por lo que creemos que la solución en esta plataforma es viable. https://azure.microsoft.com/en-us/documentation/articles/virtual-machines-linux-endorsed-distros/



Ejemplo de sitios y mapas utilizando esta tecnología
 Mapa de referencia - http://geonode.wfp.org/maps/5667



Video demo de componentes
https://www.youtube.com/watch?v=RWKD9VDvdAk
