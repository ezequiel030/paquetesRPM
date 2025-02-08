# 🖥 Comandos básicos en Rocky Linux  

A continuación, se muestran los comandos esenciales para gestionar paquetes en Rocky Linux usando 'dnf'.  

###  Actualizar el sistema  
- sudo dnf update -y = (Este comando actualiza todos los paquetes instalados a sus versiones más recientes.)

### Buscar un paquete
- dnf search nombre_del_paquete = (Permite encontrar paquetes disponibles en los repositorios.)

### Instalar un paquete
- sudo dnf install -y nombre_del_paquete = (Instala un paquete específico desde los repositorios oficiales.)

### Comprobar si un paquete está instalado
- dnf list --installed | grep nombre_del_paquete

#### También puedes verificarlo con:
- rpm -q nombre_del_paquete

### Desinstalar un paquete
- sudo dnf remove -y nombre_del_paquete = (Elimina un paquete del sistema.)

#### Elimina un paquete del sistema.
- sudo dnf autoremove -y = (Este comando elimina dependencias que quedaron sin usar tras desinstalar paquetes.)






