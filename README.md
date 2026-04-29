# UF1467_EC02_Axel_Contreras
Esta guía explica de forma sencilla qué es Git, qué es GitHub y cuáles son los comandos básicos para comenzar a trabajar con control de versiones desde la terminal o VS Code.

## 🧩 ¿Qué es Git?  

![Logo Git](img/git-logo.png)

Git es un sistema de control de versiones que permite guardar el historial de cambios, trabajar en equipo y gestionar ramas de desarrollo.

## 🌐 ¿Qué es GitHub?

GitHub es una plataforma en la nube donde puedes:
Guardar repositorios Git, colaborar con otros desarrolladores, crear issues, pull requests y gestionar proyectos.

Git es la herramienta; GitHub es el lugar donde compartes lo que haces.

## 🛠️ Comandos básicos de Git
git config --global user.name "Tu Nombre"
git config --global user.email "tuemail@example.com"

## 🔹 Crear un repositorio
git init
## 🔹 Ver el estado del repositorio
git status
## 🔹 Añadir archivos al área de preparación (staging)
git add archivo.txt
git add .
## 🔹 Guardar cambios (commit)
git commit -m "Mensaje descriptivo del cambio"
## 🔹 Ver historial de commits
git log
## 🔹 Conectar con un repositorio remoto (GitHub)
git remote add origin https://github.com/usuario/repositorio.git
## 🔹 Subir cambios a GitHub
git push -u origin main
## 🔹 Descargar cambios del repositorio remoto
git pull

## 🌿 Trabajo con ramas
git branch nombre-rama
## 🔹 Cambiar Rama
git checkout nomre-rama
## 🔹 Crear y cambiar Rama
git checkout -b nombre-rama
## 📦 Clonar un repositorio
git clone https://github.com/usuario/repositorio.git


## 🔹 Ejemplo Practico

git init
git remote add origin https://github.com/usuario/repositorio.git

## luego de esto haces tu codigo y cuando vas a guardar lo haces con estos codigos

git add .
git commit -m "aca vas a escribir un breve mensaje de lo que hiciste"
git push origin la-rama-en-que-trabajaste


📁 Tecnologías utilizadas
Git
GitHub
Visual Studio Code

🤝 Contribuciones
Este proyecto es una guía educativa. Si deseas mejorarla, puedes abrir un issue o enviar un pull request.

📄 Licencia
Uso libre para fines educativos.