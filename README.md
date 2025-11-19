1. Arquitectura del Proyecto
Docker (5 servidores Ubuntu)
        ↓
SSH habilitado
        ↓
Ansible (desde WSL o Linux host)
        ↓
Playbook automatiza:
  - Update APT
  - Crear usuario itla
  - Crear carpeta /home/itla/app
  - Crear archivo hola.txt
  - Instalar cowsay + htop
