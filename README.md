# Sprint 1 - Hardening de Ubuntu #

##Asegura las configuraciones globales.##
Configuración del arranque GRUB.
Establecer una contraseña de arranque.
Establecer permisos fichero de configuración de arranque
Obligar al uso de contraseña en el modo “single user”

##Configuración de usuarios y grupos. Crea un usuario administrador con tu nombre, y añade este al grupo sudoers. Además, aplica  una política de contraseñas adecuada.## 
Complejidad
Reutilización de contraseñas.
Almacenamiento de contraseñas. Comprueba como un hash puede ser roto si el cifrado no es el adecuado. Sigue este tutorial.
Ahora ya has evidenciado la importancia de realizar almacenamiento seguro de contraseñas como por ejemplo sha512. Una vez establecido vuelve a proceder el ataque.
Configuración del entorno (Caducidad y cambio de contraseña, Timeout de inactividad, Bloqueo de cuenta tras varios intentos, etc)

##Actualizaciones de software.##
