<h1 align="center">Configurar Git</h1>

En esta sección te guiaremos para configurar Git en tu computadora, lo cual es esencial para poder subir tus misiones al repositorio y recibir feedback de los mentores.

Posteriormente haremos un taller para usar git en profunidad, pero por ahora lo importante es que tengas Git instalado y configurado para poder seguir el workflow de desarrollo que se describe en el README.

### Instalar Git

Para instalar Git, puedes seguir la guía oficial de instalación en el sitio web de [Git](https://git-scm.com/install).

### Configurar Git

Una vez instalado Git, es importante configurarlo con tu nombre de usuario y correo electrónico, ya que esta información se asociará con tus commits. Si te encuentras en Windows puedes utilizar Git Bash, que es una terminal que viene con Git y te permite ejecutar comandos de Git de manera sencilla.

En la terminal ejecuta los siguientes comandos, reemplazando "Tu Nombre" y "Tu Correo" con el nombre y correo que utilizaste para crear tu cuenta de GitHub:

```bash
git config --global user.name "Tu Nombre"
git config --global user.email "Tu Correo"
```

Con estos comandos, Git quedará configurado con tu información de usuario, lo que te permitirá hacer commits y subir tus misiones al repositorio sin problemas.

## Usar Git

### Git en VSCode

VSCode tiene una integración nativa con Git, lo que facilita el proceso de hacer commits, crear ramas y subir tus cambios al repositorio. Para usar Git en VSCode, simplemente abre tu proyecto en VSCode y verás una sección de control de versiones en la barra lateral izquierda, donde podrás gestionar tus cambios y ramas de manera visual. También puedes acceder al menu con el atajo `Ctrl + Shift + G` (o `Cmd + Shift + G` en Mac) para abrir la vista de control de versiones. Desde allí, podrás hacer commits, crear ramas y subir tus cambios al repositorio con unos pocos clics.

### Git en la terminal

Si aventurarte a usar Git desde la terminal, aquí tienes algunos comandos básicos para empezar:

- `git status`: Muestra el estado actual de tu repositorio, incluyendo los archivos modificados y los cambios que aún no han sido commitados.
- `git add .`: Agrega todos los cambios al área de staging, preparándolos para el commit.
- `git commit -m "Mensaje del commit"`: Crea un commit con los cambios que has agregado al área de staging, utilizando el mensaje que describes entre comillas.
- `git push origin nombre-de-la-rama`: Sube tus commits a la rama especificada en el repositorio remoto (GitHub).
- `git switch -c nombre-de-la-rama`: Crea una nueva rama y cambia a ella.