# Práctica 1: IAAS
#### Jaime Simeón Palomar Blumenthal
##### alu0101228587@ull.edu.es
##

## **Índice**

1. [Objetivo de la práctica.](#objetivo)
2. [Instalación de Homebrew for Linux.](#homebrew)
3. [Instalación de Git.](#git)
4. [Configuración de Git Prompt.](#git_prompt)
5. [Alias de comandos en Git (Git aliasses).](#git_aliasses)
6. [Instalación de NVM, Node y extensiones.](#nvm)
7. [Instalación de RVM y Ruby.](#rvm)
8. [Instalación y uso de NERDTree.](#nerdtree)
9. [Puesta en marcha de una aplicación web.](#webapp)

<a name="objetivo"><a>
## **Objetivo de la práctica**

En esta práctica se pretende instalar **todos los programas y extensiones** necesarias para realizar las diferentes actividades de la asignatura.

<a name="homebrew"><a>
## **Instalación de Homebrew for Linux**

Seguimos los pasos indicados en la [**página principal de Homebrew**][homebrew_web], es decir, ejecutamos la siguiente instrucción:

`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`

Es posible que tengamos que instalar **curl** ejecutando `sudo apt install curl` en la terminal.

[homebrew_web]: https://brew.sh/index_es

<a name="git"><a>
## **Instalación de Git**

Para realizar la instalación del sistema de control de versiones emplearemos el gestor de paquetes nativo de Unix: **APT**. En la terminal ejecutaremos `sudo apt install git`:
<p>
![Captura instalación git](./img/fig4.png)