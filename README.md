# Bitácoras de Prácticas de Ingeniería de Servidores - Curso 25/26

Bienvenidos a la asignatura de **Ingeniería de Servidores (ISE)** del curso 25/26. Este repositorio tiene como objetivo gestionar las bitácoras individuales de los alumnos mediante enlaces a sus repositorios privados.

Cada alumno debe crear un repositorio (_**privado**_) en GitHub llamado `practicas-ISE` (atención con minúsculas y mayúsculas) y agregar al profesor como colaborador. Posteriormente, cada alumno deberá realizar un **pull request** (PR) a este repositorio (`bitacoras-ISE-25-26`) para agregar un enlace a su bitácora individual.

## Instrucciones detalladas

Sigue los pasos a continuación para añadir tu bitácora a este repositorio utilizando la interfaz web de GitHub

### 1. Crea tu repositorio privado en GitHub
1. Inicia sesión en tu cuenta de GitHub y crea un repositorio (_**privado**_) llamado **`practicas-ISE`**.
2. Dentro de tu repositorio, crea inicialmente un archivo **`README.md`** donde llevarás un registro de tu progreso en las prácticas de la asignatura. Puedes servirte inicialmente de la plantilla que ha creado el profesor en `https://github.com/juanluck/practicas-ISE/`
3. Invita al profesor como colaborador a tu repositorio privado para que pueda revisarlo. El usuario del profesor en GitHub es: `juanluck`.

### 2. Haz un **Fork** del repositorio del profesor
1. Ve a la página del repositorio del profesor: `https://github.com/juanluck/bitacoras-ISE-25-26`.
2. Haz clic en el botón **Fork** en la esquina superior derecha. Esto creará una copia del repositorio en tu propia cuenta de GitHub.

### 3. En el fork, crea un fichero B1/tu_usuario.md desde la web de GitHub
1. Dentro de tu fork (este repositorio que acabas de copiar a tu cuenta en GitHub), crea un nuevo fichero llamado `tu_usuario_en_github.md` dentro de la carpeta de tu subgrupo (por ejemplo `B1`). Para ello:
2. Haz clic en `Add file` y escribe la ruta completa `B1/tu_usuario.md`. Se entiende que has de sustituir `tu_usuario`  por el nombre de usuario que tengas en github y el grupo de prácticas por el que te corresponda. 
3. Luego, haz clic en el icono del lápiz (✏️) en la esquina superior derecha para editarlo.
4. Introduce un enlace a tu repositorio:
   ```markdown
   - [Nombre de Usuario del Alumno](https://github.com/tu-usuario/practicas-ISE)
   ```

Puedes mirar como ejemplo el fichero [B1/juanluck.md](https://github.com/juanluck/bitacoras-ISE-25-26/blob/main/B1/juanluck.md) que ya ha creado el profesor y que contiene:
   ```markdown
   - [juanluck](https://github.com/juanluck/practicas-ISE)
   ```
esto se renderizará como:

- [juanluck](https://github.com/juanluck/practicas-ISE/)

Míralo y asegúrate que tu fichero `B1/tu_usuario.md` sigue la misma sintaxis.



5. Desplázate hasta el final de la página y escribe un mensaje de confirmación en el campo **Commit changes**. Ejemplo: "Agrego enlace a mi bitácora".
6. Haz clic en **Commit changes** para guardar los cambios en tu fork.

### 4. Crea un Pull Request

1. Después de confirmar los cambios, ve a la pestaña **Pull Requests** en el repositorio de tu fork (copia).
2. Haz clic en el botón verde **New Pull Request**.
3. Asegúrate de que GitHub esté comparando tu fork con el repositorio original del profesor. Debería mostrar algo como:
-  **base repository**: `github-username-del-profesor/bitacoras-ISE-25-26`
-  **head repository**: `tu-usuario/bitacoras-ISE-25-26`
4. Revisa los cambios propuestos para asegurarte de que todo esté correcto.
5. Haz clic en **Create Pull Request**.
6. En la página siguiente, escribe un título descriptivo para el pull request, como "Agrego enlace a mi repositorio de bitácoras". Finalmente, haz clic en **Create Pull Request**.

### 5. Espera la aprobación

Una vez que hayas creado el Pull Request, el profesor revisará tu solicitud y, si todo está correcto, la aceptará. Cuando el Pull Request sea aprobado y fusionado, tu enlace aparecerá en este repositorio  en el archivo `B1/tu_usuario.md`.

### Contacto

Si tienes alguna duda sobre el proceso, no dudes en ponerte en contacto con el profesor a través del correo electrónico, en clase o en las horas de tutoría.
