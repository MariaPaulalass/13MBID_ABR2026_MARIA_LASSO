# Guía de uso: git

En este documento se presenta una guía para el uso de Git en un proyecto. No se exploran en profundidad algunos aspectos más complejos de la herramienta; sin embargo, con este contenido debería ser suficiente para una primera aproximación.

> [!IMPORTANT]
> Las tareas listadas consideran que se posee un repositorio ya generado en la nube (GitHub en este caso).

## Flujo de inicio y trabajo básico con el repositorio

> [!WARNING]
> A partir de este punto se presentan comandos para ser utilizados en la terminal o consola del equipo del usuario. Si bien existen herramientas visuales que serán empleadas con normalidad, se presenta la forma más básica de ejecución de las tareas previstas.

### 1. Instalación de Git

Esta operación se debe realizar a nivel del ordenador. Se puede descargar el instalador o seguir los pasos indicados en la página oficial de la herramienta:  
https://git-scm.com/

### 2. Clonado del repositorio remoto

Dado que se parte de un repositorio ya creado en GitHub, se debe clonar el repositorio en la máquina local. El comando debe ejecutarse desde la ubicación donde se desea descargar el proyecto:

```bash
git clone https://github.com/MariaPaulalass/13MBID_ABR2026_MARIA_LASSO.git