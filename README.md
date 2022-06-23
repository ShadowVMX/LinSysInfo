# LinSysInfo v1.4

![privilege](https://user-images.githubusercontent.com/92258683/175166216-dcd34d54-3daa-4fc6-9553-241cba414157.png)


Script en bash que tiene como objetivo verificar las distintas características y versiones del sistema para llevar a cabo la escalada de privilegios en los SO Linux. 


## Instalación:

git clone https://github.com/ShadowVMX/LinSysInfo.git

cd LinSysInfo

chmod +x linsysinfo

## Ejecución:

Simplemente debemos de ejecutarlo en el sistema estemos donde estemos.

**CONSEJO**

 - Guárdalo en la carpeta /tmp para evitar dejar rastro.


## ¿Qué lleva a cabo?

-Versión del kernel.

-CPU Modelo y MHZ.

-Variables de entorno.

-Variables de entorno complementarias.

-Memoria física usada.

-Memoria RAM.

-Servicios actuales cargados.

-Capabilities.

-Permisos SUID.

-Permisos GUID.

-ID (grupos).

-Permisos de ejecución del usuario actual.

-Acceso al /etc/passwd.

-Acceso al /etc/shadow (si es posible).

-Acceso al directorio de root.

-Listado de conexiones TCP.

-Listado de conexiones UDP.

-Listado de los procesos actuales del sistema.

-Información ARP.

-Información Networking (interfaces).

-Usuarios conectados al sistema actualmente.

-Posibilidad de conexión vía SSH.

-Shells disponibles.

-Información acerca de las contraseñas del sistema.

-Información de TODAS las tareas cron en el Sistema.

-Versión del SUDO.

-Versión de Apache2.

-Versión de MySQL (Si lo hubiera).

-Presencia de software crítico.

-Acceso a historial de usuario.

-Acceso a historial de root.

-Archivos de Dockers en el sistema.


## Reporte de las capturas:

![ParrotPentesting-2022-06-23-00-39-19](https://user-images.githubusercontent.com/92258683/175166460-9a8f94c7-a0e4-4b01-adf9-9ad02e25a9a3.png)



![ParrotPentesting-2022-06-23-00-40-16](https://user-images.githubusercontent.com/92258683/175166471-2e6685ff-b48a-4c56-96f8-5883671543cd.png)



![ParrotPentesting-2022-06-23-00-40-28](https://user-images.githubusercontent.com/92258683/175166476-a6119e2a-54de-40b2-9d55-db38eebd8fb8.png)


