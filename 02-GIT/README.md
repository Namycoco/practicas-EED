# 2. Git

## ¿Qué es Git?

Git es un sistema de control de versiones distribuido que permite registrar los cambios realizados en los archivos de un proyecto.

Gracias a Git podemos:

- Guardar diferentes versiones de un proyecto.
- Consultar los cambios realizados.
- Recuperar versiones anteriores.
- Trabajar en equipo.
- Crear ramas para desarrollar nuevas funcionalidades.

Git funciona desde la terminal mediante comandos.

## 2.1. Instalación de Git

Para instalar Git en Ubuntu o distribuciones basadas en Debian, ejecutamos los siguientes comandos:

```bash
sudo apt update
sudo apt install git
```

Para comprobar que Git se ha instalado correctamente:

```bash
git --version
```

## 2.2. Configuración inicial

Antes de empezar a utilizar Git, debemos configurar nuestro nombre y correo electrónico. Esta información aparecerá asociada a los cambios que guardemos.

```bash
git config --global user.name "Tu Nombre"
git config --global user.email "tu_correo@ejemplo.com"
```

Para consultar la configuración:

```bash
git config --list
```

## 2.3. Crear un repositorio

Para comenzar a trabajar con Git, debemos situarnos en la carpeta de nuestro proyecto desde la terminal.

```bash
cd nombre-del-proyecto
```

A continuación, inicializamos el repositorio:

```bash
git init
```

Este comando crea un repositorio Git en la carpeta actual. A partir de ese momento, Git podrá realizar