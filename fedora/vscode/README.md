VSCode
==========

Este rol se encargará de instalar el editor de código Visual Studio Code.

Requerimientos
--------------

Al tratarse de paquetes RPM es necesario ejecutarlo sobre RHEL 8 o alguna distribución GNU/Linux derivada del mismo.

Ejemplo de Playbook
-------------------

Para utilizar la función se deben configurar las siguientes variables:

    - name: install vscode
      hosts: all
      become: yes
      roles: 
         - vscode

Licencia
--------

GNU General Public License v3.0