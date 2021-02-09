Vagrant
=======

Este rol se encargará de instalar la herramienta de creación y configuración Vagrant.

Requerimientos
--------------

Al tratarse de un binario puede instalarse en cualquier distribución GNU/Linux.

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