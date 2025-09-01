# Introducción a Git y GitHub

## ¿Qué es Git?
Git es un sistema de control de versiones que permite llevar un historial de los cambios realizados en un proyecto, facilitando la organización del codigo.

## Instalación de Git
1. Descargar Git desde la pagina oficial: [https://git-scm.com/](https://git-scm.com/)
2. Instalar el ejecutable siguiendo las instucciones.
3. Verificar la instalación en la terminal con:
```bash
git --version
```
## Creación de cuenta en GitHub
1. Ingresar a [https://github.com/](https://github.com/)
2. Crear una cuenta con correo electrpnico y contraseña.
3. Configurar perfil basico (foto, usuario, descripción)

## Creación carpeta de Proyecto
1. Crear una carpeta local para el proyecto.
2. Acceder a la carpeta desde la terminal con el comando **cd**.
```bash
cd C:\ruta\de_la_carpeta
```

## Inicializar repositorio
En la terminal, dentro de la carpeta del proyecto, ejecuta el siguiente comando:
```bash
git init
```

Este comando crea la carpeta oculta .git que contiene tod la informacion del repositorio.

## Staging area y git add
Para preparar un archivo y pasarlo al área de *staging* usar:
```bash
git add nombre_archivo
```

O para agregar todos los archivos modificados o nuevos de una sola vez, usar:

```bash
git add .
```

## Crear un commit
Un commit guarda los cambios en el repositorio con un mensaje descriptivo:
```bash
git commit -m "mensaje del commit"
```
Ejemplo:
```bash
git commit -m "add README file"
```