# 002 Modelo De Responsabilidad Compartida

> 📅 **Creado:** 2025-10-28  
> 🔁 **Última actualización:** YYYY-MM-DD  
> 🏷️ **Tags:** #Azure #ResponsabilidadCompartida 

---
En la nube, la seguridad y el mantenimiento se reparten entre el proveedor y el cliente.

## Proveedor de nube

Siempre se encarga de:
- Seguridad física del centro de datos
- Infraestructura: red, servidores, energía, refiregeración.
-  Hosts físicos donde corren los servicios.

Cliente se encarga de:

- Datos e información almacenada
-  Dispositivos que acceden a la nube (PC, móvil,etc.)
-  Cuentas e indentidades )usuarios, contraseñas, roles, permisos)


| Tipo de servicio                     | Qué gestionas tú                      | Qué gestiona el proveedor              |
| ------------------------------------ | ------------------------------------- | -------------------------------------- |
| IaaS (Infraestructura como servicio) | SO, apps, parches,datos               | Hardware, red, centro de datos         |
| PaaS (Plataforma como servicio)      | Datos, usuarios, permisos             | Infraestructura + SO + plataforma      |
| SaaS (Software como Servicio)        | Usuarios, datos, configuración básica | Todo (Infraestructura, app, seguridad) |

**En resumen:**

Cuanto más "servicio" te da la nube, menos tienes que gestionar tí.
Pero los datos y las identidades siempre son tu responsabilidad.