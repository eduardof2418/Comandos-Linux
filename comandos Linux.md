# Comandos-Linux
## Comandos Linux todo el cuatrimestre
### Eduardo Flores Ruiz
| Comando | Descripcion | Ejemplo |
| ------- | ----------- | ------- |
| sudo ls | Muestra la lista de carpetas en el directorio seleccionado. | sudo ls |
| pwd | Imprime en consola la ruta en la que estamos actualmente. | pwd |
| cd / | Cambia el directorio a la dirección asignada. | cd / |
| nano | Editor de texto version consola. | nano |
| ls -l | Imprime los archivos en formato de lista. | ls -l |
| ls -a | Imprime los archivos ocultos. | ls -a |
| cat  | Imprime en la terminal el contenido del archivo.  | cat |
| mkdir | Crea una carpeta nueva. | mkdir |
| rm | Borra un archivo. | rm |
| rm -R | Borra una carpeta. | rm -R |
| clear | Borra todo el terminal. | clear |
| rm -Rf | Borra un archivo forzosamente. | rm -Rf |
| cd | Lleva al directorio madre. | cd |
| top | Enseña el estado de los procesos de la máquina. | top |
| htop | Muestra el estado de los procesos de la máquina. | htop |
| ps -auclx | Terminal no interactiva, imprime en pantalla el estado de los procesos. | ps -auclx|
| pstree | Muestra los procesos en pantalla en forma de árbol. | pstree |
| kill -9 processid | Cierra una aplicación o proceso activo. | kill -9 processid |
| ip a | Muestra las direcciones IP del equipo en pantalla. | ip a |
| sudo apt update && sudo apt upgrade | Actualizar el sistema. | sudo apt update && sudo apt upgrade |
| root | Acceder al usuario de administrador | root |
| exit | Salir del usuario de administrador. | exit |
| whoami | Muestra en pantalla que usuario está siendo utilizado. | whoami |
| sudo adduser  | Añade un usuario al sistema | sudo adduser |
| sudo passwd | Cambiar el password. | sudo passwd |
| history | Muestra el historial de todos los comandos utilizados. | history |
| tail | Muestra las últimas diez líneas de un archivo. | tail |
| sudo dmidecode --type 17 cat /proc/meminfo   | Muestra información en pantalla del tamaño de la memoria. | sudo dmidecode --type 17 cat /proc/meminfo |
| free -h | Muestra un desglose de la memoria y el swap. | free -h |
| cat /proc/sys/vm/swappiness | Muestra la cantidad de memoria que se destina a la RAM, es importante notar que va de 0 a 60. | cat /proc/sys/vm/swappiness |
| swapon | Muestra la partición de SWAP y el tamaño. | swapon |
| sudo reboot | Reinicia el equipo. | sudo reboot |
| sudo mkdir /mnt/ram_disk sudo mount -t tmpfs -o size=1024m new_ram_disk /mnt/ram_disk | Crea una partición en la memoria RAM. | Ejemplo |
| du | Muestra en pantalla el tamaño de un archivo. | du |
| stat | Muestra las fechas de modificación de un archivo. | stat |
| file  | Muestra en pantalla el formato de un archivo. | file |
| chmod +r | Le da permisos de lectura a un archivo. | chmod +r |
| chmod +w | Le da permisos de escritura a un archivo. | chmod +w |
| chmod +x | Le da permisos de ejecución a un archivo. | chmod +x |
| chmod +rwx | Le da todos los permisos a un archivo. | chmod +rwx |
| chown | Usado para cambiar el propietario de un archivo. Solo puede ser usado por el superusuario. | chown |
| df -h | Muestra el espacio del disco usado. | df -h |
| mount | Utilizado para montaje de dispositivos. | mount |
| gnome-disk-utility | Muestra la partición del disco | gnome-disk-utility |
| ps -aux | Muestra el proceso activo seleccionado. | ps -aux |
| touch | Utilizado para crear un archivo | touch |
| vim | Editor de texto en consola. | vim |
| echo | Sirve para imprimir texto en pantalla para archivos .txt | echo |
| service | Permite inicializar y/o detener servicios | service mysql start |
| tree | Permite ver la estructura de los directorios, así como ver que hay dentro de cada uno | Tree -L2 |
| build | Permite al usuario crear su propia imagen de Docker. | build |
| docker create | Con Docker, crea un contenedor pero no lo inicia | Docker create |
| docker pull/pull | Sirve para descargar imágenes de un registro de Docker. | Docker pull ubuntu1 |
| bridge | DescrCrea un puente/conexión a la hora de crear una redipcion | Docker network create –driver bridge red1 |
| network |  Permite ver que dispositivos participan en el enrutamiento | network |
| id | Muestra el UID y el GID del usuario especificado | id user1 |
| cat | Combina varios archivos en uno solo o crea uno nuevo | cat |
| Search  | Inicia una búsqueda recursiva en los directorios  | Search |
| run | Ejecuta un contenedor desde el ID de la imagen | docker run nginx |
| info | Muestra la documentación del comando junto con el que es ejecutado  | docker info |






