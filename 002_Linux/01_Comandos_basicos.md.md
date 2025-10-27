# 01 Comandos basicos

> 📅 **Creado:** 2025-10-27  
> 🔁 **Última actualización:** YYYY-MM-DD  
> 🏷️ **Tags:** #linux #cli #bash #fundamentos

---

## 🧠 Conceptos clave
-  Linux es un sistema operativo basado en Unix que se maneja principalmente desde la **CLI
-  Todo en Linux es un **archivo**
- La CLI permite controlar el sistema con precisión, automatizar tareas y adminstrar servidores.

---

## ⚙️ Comandos esenciales
```bash
# --- Navegaión en el sistema de archivos --- #

	pwd             #Muestra el directorio actual
	ls -la          # LIsta de archivos (con permisos ocultos)
	cd /ruta        # Cambia de directorio
	cd ..           # Sube un nivel
	cd ~            # Ir al home del usuario
	
# --- Archivos y directorios ---
	
	touch archivo.txt     # Crea un archivo vacío
	mkdir nueva_carpeta   # Crea una carpeta
	cp origen destino     #Copa archivos o carpetas
	mv origen destino     # Mueve o renombra
	rm archivo.txt        # Elimina un archivo
	rm -r carpeta         # Elimina una carpeta recursivamente
	
# --- Ver contenido ---
cat archivo.txt           # Muestra contenido completo
head archivo.txt          # Muestra las primeras lineas
tail archivo.txt          # Muestra las ultimas líneas
less archivo.txt          # Visualiza contenido con paginación

# --- Información de sistema ---

whoami                    # Muestra el usuario actual
uname -a                  # Info del kernel y del sistema
uptime                    # Tiempo que lleva encendido el sistema
df -h                     # Espacio en disco
du -h                     # Tamaño de archivos o directorios
free -h                   # Uso de memoria RAM

# --- Gestión de usuarios ---

sudo su                   # Cambiar a superUsuario
adduser nuevo_usuario     # Crea un nuevo usuario
passwd usuario            # Cambia de contraseña
userdel nombre_usuario    # Elimina la cuenta del sistema pero no su carpeta personal
userdel -r nombre_usuario # Elimina el usuario y su carpeta personal

# --- Permisos ---
chmod 755 archivo           # Cambia d epermisos (rwxr-xr-x)
chown usuario:grupo archivo # Cambia de propietario

# --- Búsqueda ---

find / -name archivo.txt    # Busca archivos por nombre
grep "palabra" archivo      # Busca texto dentro de archivo

# --- Red ---

ping 8.8.8.8                # Verifica conectividad
ip addr show                # Muestra interfaces y direcciones IP
ifconfig                    # informacion de red


```

