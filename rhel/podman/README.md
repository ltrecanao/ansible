Podman
======

Este rol se encargará de instalar el motor de contenedores Podman y Podman Compose.

Requerimientos
--------------

Al tratarse de paquetes RPM es necesario ejecutarlo sobre RHEL 8 o alguna distribución GNU/Linux derivada del mismo.

Ejemplo de Playbook
-------------------

Para utilizar la función se deben configurar las siguientes variables:

    - name: install podman
      hosts: all
      become: yes
      roles: 
         - podman

Licencia
--------

GNU General Public License v3.0
