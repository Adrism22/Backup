# Backup Drive

RCLONE 

- Configurar rclone con el comando `rclone config`
- Establecer un nombre, el tipo de almacenamiento (drive) y dar los permisos correspondientes
- Las demás opciones dejaralas por defecto
- Copiar la carpeta del drive con rclone copy /home/source remote:backup

RESTIC

- Crear una carpeta para usarla de repositorio
- Usar "restic backup [Ruta de la carpeta] --repo [Ruta del repositorio]"

CRONTAB 

- crontab -e
- 0 2 * * * /home/asanchez/copia.sh
