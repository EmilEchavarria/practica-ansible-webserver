# Práctica: Automatización de Servidor Web con Ansible

Este proyecto implementa un servidor web Apache usando Ansible y la arquitectura de roles.

## Estructura del proyecto
- `inventory`: lista de hosts
- `playbook.yml`: playbook principal
- `roles/webserver`: rol para instalar y configurar Apache
- `index.html.j2`: archivo HTML generado via template

## Cómo ejecutar
1. Editar archivo `inventory` y colocar la IP del servidor.
2. Ejecutar:

```bash
ansible-playbook playbook.yml
"# practica-ansible-webserver" 
