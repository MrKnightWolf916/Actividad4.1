# Actividad4.1
# Configuración de Entorno de Desarrollo

## Descripción

En esta actividad configuraremos nuestro entorno de desarrollo para trabajar en los proyectos prácticos del curso. Utilizaremos una máquina virtual previamente creada y realizaremos la instalación de diversas herramientas esenciales para el desarrollo en distintos lenguajes y tecnologías.

## Prerrequisitos

Antes de comenzar, asegúrate de tener acceso a la máquina virtual creada en la actividad anterior.

### Tecnologías a instalar

- Visual Studio Code
- Git
- Apache2
- PHP
- Compilador de C (build-essential)

## Pasos para su ejecución

1. **Acceder a la máquina virtual**  
   Inicia tu máquina virtual y abre una terminal.

2. **Actualizar el sistema**  
   ```bash
   sudo apt update && sudo apt upgrade -y
sudo snap install code --classic
sudo apt install git -y
sudo apt install apache2 -y
sudo apt install php libapache2-mod-php -y
sudo apt install build-essential -y

