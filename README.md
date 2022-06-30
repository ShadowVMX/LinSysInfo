# LinSysInfo v2.0

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

-	Versión de Kernel e información complementaria del mismo.
-	Verificar dmesg y boot del sistema.
-	CPU y Mhz de la misma.
-	Variables de entorno.
-	Información complementaria de las variables y rutas de ejecución.
-	RAM disponible y ocupada por el sistema.
-	Servicios activos en el sistema.
-	Syslog.conf
-	Chttpd.conf
-	Lighttp.conf
-	Cupsd.conf
-	Inetd.conf
-	Apache2.conf
-	My.conf
-	Httpd.conf
-	Capabilities
-	Permisos SUID
-	Permisos GUID
-	Id (groups).
-	Permisos de ejecución con “sudo –l”
-	Visualización /etc/passwd
-	Visualización /etc/shadow
-	Visualizar directorio de root.
-	Conexiones TCP.
-	Conexiones UDP.
-	Procesos totales del sistema.
-	Procesos parciales SOLO de root.
-	ARP
-	Interfaces
-	IPtables
-	DNS
-	Hostnames
-	Disponibilidad de SSH con PermitRootLogin –> Yes
-	SSH authorized keys.
-	SSH public Keys.
-	SSH private Keys.
-	Shells disponibles en el sistema.
-	Información acerca de las contraseñas del sistema.
-	Todos los crons disponibles en el sistema podrán ser visualizados.
-	Versión de sudo.
-	Versión de apache2.
-	Versión de MySQL.
-	Softwares críticos (nc,nmap,gcc,curl,wget… etc)
-	Ver toda la información del usuario tanto normal como oculta.
-	Visualización de TODOS los historiales tanto en usuario como en root.
-	Rutas alternas como /var/spool/mail/root y normal user.
-	Archivos referentes a todos los Dockers del sistema por si fuera posible verificar Passwords.



## Reporte de las capturas:

![ParrotPentesting-2022-06-23-00-39-19](https://user-images.githubusercontent.com/92258683/175166460-9a8f94c7-a0e4-4b01-adf9-9ad02e25a9a3.png)



![ParrotPentesting-2022-06-23-00-40-16](https://user-images.githubusercontent.com/92258683/175166471-2e6685ff-b48a-4c56-96f8-5883671543cd.png)



![ParrotPentesting-2022-06-23-00-40-28](https://user-images.githubusercontent.com/92258683/175166476-a6119e2a-54de-40b2-9d55-db38eebd8fb8.png)




