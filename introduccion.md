#  ¿Qué son los paquetes rpm?

<p align="justify">
Los paquetes RPM (Red Hat Package Manager) son un formato de empaquetado utilizado en sistemas operativos basados en Red Hat, como Rocky Linux, CentOS y Fedora. Estos paquetes contienen software, bibliotecas y metadatos necesarios para instalar, actualizar y gestionar aplicaciones en un sistema Linux.
</p>

<p align="justify">
Algunas características clave de los paquetes RPM:
</p>

| **Característica**        | **Descripción** |
|---------------------------|--------------------------------------------------------------------------------------|
| **Extensión**            | `.rpm` |
| **Gestor de paquetes**   | Se gestionan con herramientas como `rpm` y `dnf`. |
| **Control de dependencias** | Verifica e instala automáticamente dependencias necesarias para un paquete. |
| **Firma digital**        | Permite verificar la autenticidad e integridad del paquete mediante claves GPG. |
| **Facilidad de instalación** | Se pueden instalar con `dnf install paquete.rpm` o `rpm -ivh paquete.rpm`. |
| **Soporte para actualizaciones** | Se pueden actualizar usando `dnf update` o `rpm -Uvh paquete.rpm`. |
| **Base de datos de paquetes** | Mantiene un registro de paquetes instalados en `/var/lib/rpm/`. |
| **Distribuciones compatibles** | Usado en **Rocky Linux, RHEL, CentOS, Fedora, openSUSE**, entre otras. |

