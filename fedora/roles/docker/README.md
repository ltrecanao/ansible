Docker
======

Este rol se encargará de instalar el motor de contenedores Docker y Docker Compose.

Requerimientos
--------------

- Gestor de paquetes Pip

Ejemplo de Playbook
-------------------

Para utilizar la función se deben configurar las siguientes variables:

    - name: install docker
      hosts: all
      become: yes
      roles: 
         - docker

Licencia
--------

GNU General Public License v3.0
