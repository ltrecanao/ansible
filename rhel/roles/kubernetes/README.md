Kubernetes
==========

Este rol se encargará de instalar el cliente de Kubernetes.

Requerimientos
--------------

- Sin requerimientos

Ejemplo de Playbook
-------------------

Para utilizar la función se deben configurar las siguientes variables:

    - name: install kubernetes
      hosts: all
      become: yes
      roles: 
         - kubernetes

Licencia
--------

GNU General Public License v3.0