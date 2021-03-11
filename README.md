# Ansible
![](https://upload.wikimedia.org/wikipedia/commons/0/05/Ansible_Logo.png)

Ansible es una plataforma de automatización de software libre que facilita el despliegue de aplicaciones, la orquestación multi-nivel y la gestión de la configuración de las infraestructuras.

## Instalar Ansible
Para instalar Ansible requerimos tener el gestor de paquetes **pip** de **Python**.  
`pip install --user ansible`

Para verificar su correcta instalación se puede correr el siguiente comando, y así obtener la versión instalada.  
`ansible -v`

## Configurar los hosts
Ansible requiere que editemos el archivo de configuración **/etc/ansible/hosts**, añadiendo las direcciones IP o nombres de los equipos con los que se conectará nuestro host vía SSH. En el archivo hay ejemplos de como debe configurarse, para editar el archivo es necesario utilizar privilegios tal como se muestra en la siguiente linea.  
`sudo vi /etc/ansible/hosts`

## Claves SSH
Ansible requiere que configuremos las claves SSH de nuestro host para compartir con aquellos clientes a los que se accederá vía SSH. Por lo que se deberá crear un par de claves SSH.  
`ssh-keygen -t rsa`

Luego de crear el par de claves SSH, se debe copiar a los equipos clientes, reemplazando user y host por los mismos del cliente.  
`ssh-copy-id user@host`

## Utilizar los roles
Para utilizar los roles se debe crear un archivo **playbook.yml**, este especifica que roles ejecutará cuando se lo ejecute, y un directorio llamado **roles**, donde se almacenarán los roles que se deseén ejecutar. En cada **role** se encuentra detallado lo mínimo que debe incluir el archivo **playbook.yml**. Una vez creado el archivo playbook.yml y el directorio roles se ejecuta la siguiente linea.  
`ansible-playbook playbook.yml -K`
