## Investigar y contestar las siguientes preguntas. 

### • ¿Que es un usuario root en Linux? 
Es una cuenta de superusuario o administrador que posee todos los derechos administrativos  en todos los modos.

### • ¿Por qué ubuntu no me deja establecer la contraseña durante la instalación? 
Por defecto, root no tiene contraseña y la cuenta de root está bloqueada hasta que le dé una contraseña. Pero al usuario que instaló el sistema operativo le da privilegios de administrador. Y por lo general cuando pide contraseña de administrador es la contraseña de este usuario. Y esta misma sera del usuario root.

### • Cuáles son los procesos típicos de Linux?

1. gnome: entorno gráfico (interfaz)
1. systemd: administrador de servicios 
1. rcu_gp: monitorea la carga de procesos en la CPU

![Captura de la terminal con el comando top]()

### •	¿Cómo identificarlos? 
Corriendo el comando $top$ desde el terminal o con el comando $ps$

### •	Investigar y establecer una contraseña para el usuario root.
La contraseña del usuario root se establece con el comando $sudo$ $passwd$ $root$ el cual se debe ejecutar desde la terminal. Esta también se puede probar ejecutando el comando $su-$

## Linkografía 
* https://www.compuhoy.com/cual-es-la-contrasena-predeterminada-del-usuario-root-de-ubuntu/#%C2%BFComo_encuentro_mi_contrasena_de_root_en_Ubuntu
* https://www.ibm.com/docs/es/rational-build-forge/7.1.3?topic=users-root-user

