# 003 ModelosEnLaNube

> 📅 **Creado:** 2025-10-28  
> 🔁 **Última actualización:** YYYY-MM-DD  
> 🏷️ **Tags:** #Azure #ModelosDeNube #ConceptosBasicos
---

Los modelos en la nube definen el tipo de implementación de recursos en la nube. Las 3 principales son: privadds, públicos e híbridos 

---

## Nube privada

Evolución natural de un centro de datos corporativo. Brinda servicios de TI a través de internet y es utilizada por una sola entidad. Incluye un mayor costo y menos ventajas que unaimplementacion en la nube pública. Además, se puede hospedar desde el centro de datos del sitio. También pued ehospedarse en un centro de datos dedicado fuera del sitio, posiblemente incluso por un tercero que haya dedicado ese centro de datos a su empresa.

## Nube pública

Un proveedor de nube de terceros crea. controla y mantiene una nube pública. Cualquier persona que quiera comprar servicios en la nube puede acceder a los recursos y usarlos. La disponibilidad pública es la diferencia clave con las privadas.

## Nube híbrida

Entorno que usa nubes públicas y privadas en un entorno interconectado. Se puede usar un entorno de nube híbrida para permitir el incremento de una nube privada y acomodarse al aumento de la demanda temporal mediante la implementación de recursos de la nube pública. Se puede usar para proporcionar una capa adicional de seguridad. Por ejemplo, los usuarios pueden elegir de forma flexible qué servicios mantener en la nube pública y qué iimplementar en su infraestructura de nube privada.


| Nube pública                                                                 | Nube privada                                                                             | Nube híbrida                                                                         |
| ---------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------ |
| No hay gastos de capital para escalar verticalmente                          | Las organizaciones tienen un control total de los recursos y la seguridad                | Proporciona la máxima flexibilidad                                                   |
| Las aplicaciones pueden aprovisionarse y desaprovisionarse rápidamente       | Los datos no se colocan con los datos de otras organizaciones                            | Las organizaciones determinan dónde se van a ejecutar sus aplicaciones               |
| Las organizaciones solo pagan por lo que usan                                | Debe adquirirse hardware para la puesta en funcionamiento y el mantenimiento             | Las organizaciones controlan la seguridad, el cumplimiento o los requisitos legales. |
| Las organizaciones no tienen un control total de los recursos y la seguridad | Las organizaciones son responsables del mantenimiento y las actualizaciones del hardware |                                                                                      |

## Nubes múltiples

Se usan varios proveedores de nube pública. Tal vez use diferentes características de diferentes proveedores de nube. O quizá esté en proceso de migración a otro proveedor. En un entorno de varias nubes lidia con dos (o más) proveedores de nube pública y administra los recursos y la seguridad en ambos entornos.

## Azure arc

Es un conjunto de tecnologías que ayudan a administrar el entorno en la nube. Azure Arc ayuda a administrar el entorno en al nube, ya sea una nube pública únicamente en Azure, una nube privada en el centro de datos, una configuración híbrida o incluso un entorno de varias nubes que se ejecute en varios proveedores a la vez.

## Azure VMware Solution

¿Qué ocurre si ya está establecido con VMware en un entorno de nube privada, pero quiere migrar a una nube pública o híbrida? Azure VMware Solution le permite ejecutar las cargas de trabajo de VMware en Azure con una integración y escalabilidad perfectas.