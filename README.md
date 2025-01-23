Resumen del contenido para documentar el proceso para la creación de un servidor FTP, documentando los pasos por medio de la documentación , capturas y desarrollando las opciones más importantes del fichero de configuración:

Los procesos a desarrollar son los siguientes:

1. Instalar un Servidor FTP:

El paquete más común para un servidor FTP en Ubuntu es vsftpd (Very Secure FTP Daemon). 
Asegurarse de que el sistema está actualizado y luego proceder a instalar el paquete vsftpd desde los repositorios oficiales de Ubuntu. 
Una vez instalado, verificar que el servicio está activo y en ejecución para confirmar que la instalación fue exitosa.

2. Configuración:

El archivo principal de configuración para vsftpd se encuentra en /etc/vsftpd.conf. 
Antes de realizar cambios, es recomendable crear una copia de seguridad del archivo original. 
Al editar el archivo, asegurarse de configurar opciones clave.
Configurar un rango de puertos específico para conexiones pasivas, lo que puede ser necesario en configuraciones de red más complejas.
Una vez realizadas las modificaciones, guardar los cambios y reiniciar el servicio para que las nuevas configuraciones entren en vigor.
