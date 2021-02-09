Brave
=====

Este rol se encargará de instalar el navegador web Brave y en consecuencia desinstalar Firefox.

Requerimientos
--------------

Al tratarse de paquetes RPM es necesario ejecutarlo sobre RHEL 8 o alguna distribución GNU/Linux derivada del mismo.

Ejemplo de Playbook
-------------------

Para utilizar la función se deben configurar las siguientes variables:

    - name: install brave
      hosts: all
      become: yes
      roles: 
         - brave

Licencia
--------

GNU General Public License v3.0
