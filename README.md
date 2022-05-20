# Ansible
![](https://upload.wikimedia.org/wikipedia/commons/0/05/Ansible_Logo.png)

## Utilizar los roles
Para utilizar los roles se debe crear un archivo **playbook.yml**, este especifica que roles ejecutará cuando se lo ejecute, y un directorio llamado **roles**, donde se almacenarán los roles que se deseén ejecutar. En cada **role** se encuentra detallado lo mínimo que debe incluir el archivo **playbook.yml**. Una vez creado el archivo playbook.yml y el directorio roles se ejecuta la siguiente linea.  
`ansible-playbook playbook.yml -K`
