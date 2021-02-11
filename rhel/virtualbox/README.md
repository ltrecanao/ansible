VirtualBox
==========

Este rol se encargará de instalar el virtualizador VirtualBox.

Requerimientos
--------------

- Sin requerimientos

Ejemplo de Playbook
-------------------

Para utilizar la función se deben configurar las siguientes variables:

    - name: install virtualbox
      hosts: all
      become: yes
      roles: 
         - virtualbox

Licencia
--------

GNU General Public License v3.0

