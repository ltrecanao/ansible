Vagrant
=======

Este rol se encargará de instalar la herramienta de creación y configuración Vagrant.

Requerimientos
--------------

- Sin requerimientos

Ejemplo de Playbook
-------------------

Para utilizar la función se deben configurar las siguientes variables:

    - name: install vagrant
      hosts: all
      become: yes
      roles: 
         - vagrant

Licencia
--------

GNU General Public License v3.0
