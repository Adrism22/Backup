# Backup

RCLONE 

- Configurar rclone con el comando "rclone config"
- Establecer un nombre, el tipo de almacenamiento (drive) y dejar lo demas por defecto
- Copiar la carpeta del drive con rclone copy /home/source remote:backup

RESTIC

- Crear una carpeta para usarla de repositorio 
- Usar "restic backup [Ruta de la carpeta] --repo [Ruta del repositorio]"

CRONTAB 
- 0 2 * * * /home/asanchez/copia.sh
