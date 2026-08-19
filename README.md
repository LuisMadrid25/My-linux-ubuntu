# Linux & System Administration Fundamentals

Repositorio de estudio y notas técnicas orientadas a la administración de sistemas Linux, comandos CLI y resolución de problemas de red para entornos Cloud (IaaS/PaaS).

---

## 📂 Estructura del Repositorio

```text
linux-fundamentals/
├── 01-filesystem-and-navigation/
├── 02-file-permissions-and-ownership/
├── 03-user-and-group-management/
├── 04-package-management-and-editors/
├── 05-networking-troubleshooting/
└── scripts/
```

---

## 📑 Módulos de Estudio

| Módulo | Descripción | Enlace |
| :--- | :--- | :--- |
| **01. Filesystem & Navigation** | Jerarquía del sistema de archivos (`/etc`, `/var`, `/proc`), rutas y comandos de navegación básica. | [Ver apuntes](./01-filesystem-and-navigation/) |
| **02. Permissions & Ownership** | Gestión de permisos en notación octal y simbólica (`chmod`, `chown`, `chgrp`, `umask`). | [Ver cheatsheet](./02-file-permissions-and-ownership/) |
| **03. User & Group Management** | Administración de cuentas, contraseñas, grupos y permisos de `sudo` (`useradd`, `/etc/passwd`). | [Ver módulo](./03-user-and-group-management/) |
| **04. Package Managers & Editors** | Comparativa de gestores de paquetes (`apt`, `dnf`) y atajos esenciales de Vim/Nano. | [Ver cheatsheet](./04-package-management-and-editors/) |
| **05. Network Troubleshooting** | Herramientas de diagnóstico de red (`ping`, `curl`, `tcpdump`, `ss`, `mtr`). | [Ver guía](./05-networking-troubleshooting/) |

---

## 🛠️ Scripts & Utilidades

Los scripts de automatización y verificación práctica se encuentran en la carpeta [`/scripts`](./scripts/):
* `common-troubleshooting.sh`: Script para comprobar estado de interfaces, conectividad DNS y puertos abiertos.

---

## 🚀 Cómo usar este repositorio

1. Clona el repositorio:
   ```bash
   git clone [https://github.com/tu-usuario/My-linux-ubuntu.git](https://github.com/tu-usuario/My-linux-ubuntu.git)
   cd My-linux-ubuntu
   ```
2. Otorga permisos de ejecución a los scripts si deseas probarlos:
   ```bash
   chmod +x scripts/*.sh
   ```
