# Ansible
## ¿Qué es Ansible?
![](https://upload.wikimedia.org/wikipedia/commons/0/05/Ansible_Logo.png)  
Ansible es una plataforma de automatización de software libre que facilita el despliegue de aplicaciones, la orquestación multi-nivel y la gestión de la configuración de las infraestructuras.

## ¿Cómo instalar Ansible?
Para instalar Podman Compose requerimos tener el gestor de paquetes pip de Python.
> sudo pip3 install ansible

Para verificar su correcta instalación se puede correr el siguiente comando, y así obtener la versión instalada.
> ansible -v

## ¿Cómo utilizar los roles?
Para utilizar los roles se debe crear un archivo **yaml** al nivel de la carpeta **roles** en donde se especifique que ejecutar. En cada **role** se encuentra detallado lo que debe incluir el archivo **yaml**. Una vez creado se ejecuta la siguiente linea.
> ansible-playbook playbook.yaml
