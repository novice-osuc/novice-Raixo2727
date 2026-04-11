<h1 align="center">Template Novice</h1>

---

Este sera tu repositorio para desarrollar tus misiones semanales, despues de cada taller se te asignara una nueva misión, la cual deberás desarrollar y subir a este repositorio, para que los mentores puedan revisar tu progreso y darte feedback.

## Requisitos

- Tener git instalado en tu computadora. Sigue esta [guía](./GIT.md).
- Tener una cuenta en GitHub. Puedes crear una cuenta gratuita desde [aquí](https://github.com/signup).
- Tener Visual Studio Code (VSCode) instalado en tu computadora. Puedes descargarlo desde [aquí](https://code.visualstudio.com/Download).

> [!NOTE]
> Puedes utilizar cualquier editor de código que prefieras, pero en este curso utilizaremos VSCode para las demostraciones y ejemplos.

## Reglas

No esta permitido compartir tu código con otros compañeros, cada misión debe ser desarrollada de forma individual. Si tienes dudas o necesitas ayuda, puedes preguntar a los mentores o a tus compañeros en el canal de Discord. Recuerda que el objetivo de este curso es aprender y mejorar tus habilidades, por lo que es importante que desarrolles tus misiones por tu cuenta.

El uso de la inteligencia artificial (IA) para resolver las misiones esta restringido, ya que el objetivo es que desarrolles tus habilidades de programación y resolución de problemas por tu cuenta. Solo esta permitido el uso para resolver dudas teoricas o para obtener explicaciones sobre conceptos, pero no para resolver las misiones directamente. En caso de utilizar IA, deberás crear un documento IA.md donde tendras que compartir los chats que tuviste con la IA, para que los mentores puedan revisar tu proceso de aprendizaje y darte feedback.

## Workflow de desarrollo

### Una rama por misión
Cada misión debe ser desarrollada en una rama diferente, con el nombre de la misión, por ejemplo: `misión-x`.

Puedes crear una nueva rama directamente desde VSCode:



https://github.com/user-attachments/assets/09da8b30-2ec8-4425-8a1b-10637fa67470




O también puedes crear una nueva rama desde la terminal con el siguiente comando:

```bash
git switch -c mision-x
```

> [!IMPORTANT]
> - Es importante que cada misión se desarrolle en una rama diferente.
> - Debes haber configurado Git previamente.


### Subir tus cambios y hacer commits

Para subir tus cambios a GitHub puedes utilizar nuevamente la integración de Git en VSCode:



https://github.com/user-attachments/assets/2eb62c28-43c3-4a7a-8fc4-ef9d593744f6



O también puedes utilizar la terminal para hacer commits y subir tus cambios con los siguientes comandos:

```bash
git add .
git commit -m "Mensaje del commit"
git push origin mision-x
```

### Crear un Pull Request (PR)

Después de subir tu rama con los cambios, debes crear un Pull Request (PR) para que los mentores puedan revisar tu trabajo y darte feedback. 

Para crear una PR, debes ir a tu repositorio de GitHub y realizar los siguientes pasos:



https://github.com/user-attachments/assets/7b09a8db-4209-45ae-bd25-f2ebd4a683c4


