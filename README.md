# StudentHub

StudentHub es una plataforma para gestionar servicios académicos universitarios.
El proyecto será desarrollado colaborativamente utilizando Git y GitHub.

## Funcionalidades

- Gestión de estudiantes
- Gestión de cursos

## Equipo

- Sierra Zapata Angelica
- Martinez Monsalvo Luis Jaime


## Preguntas de reflexión

### 1. ¿Cuál es la diferencia entre `git add` y `git commit`?

`git add` prepara los cambios y los coloca en el staging area. En cambio, `git commit` registra definitivamente esos cambios en el historial del repositorio local junto con un mensaje descriptivo.

### 2. ¿Cuál es la diferencia entre `git push` y `git pull`?

`git push` envía los commits del repositorio local al repositorio remoto en GitHub. `git pull` descarga los cambios del repositorio remoto y los integra en la rama local.

### 3. ¿Cuál es la diferencia entre un repositorio local y uno remoto?

El repositorio local está almacenado en la computadora del desarrollador y permite trabajar con Git. El repositorio remoto está alojado en una plataforma como GitHub y facilita compartir, respaldar y colaborar en el proyecto.

### 4. ¿Qué problema resuelve una rama?

Una rama permite desarrollar cambios o funcionalidades de manera independiente, sin modificar directamente la rama principal ni afectar el trabajo estable del proyecto.

### 5. ¿Qué diferencia existe entre `git merge` y `git rebase`?

`git merge` integra los cambios de dos ramas conservando sus historiales y puede crear un commit de merge. `git rebase` traslada los commits de una rama sobre una base más reciente, creando un historial más lineal y modificando los identificadores de los commits reaplicados.

### 6. ¿Por qué ocurre un conflicto?

Un conflicto ocurre cuando Git encuentra cambios incompatibles, por ejemplo, cuando dos personas modifican de forma diferente la misma línea de un archivo y Git no puede decidir automáticamente cuál versión conservar.

### 7. ¿Quién debe decidir cómo resolver un conflicto?

La decisión debe tomarla el equipo o la persona que comprenda la intención de los cambios. Git solamente identifica el conflicto, pero no puede determinar cuál contenido es el correcto.

### 8. ¿Qué problema resuelve un Pull Request?

Un Pull Request permite proponer, comparar, discutir y revisar los cambios de una rama antes de integrarlos en la rama principal.

### 9. ¿Por qué es recomendable revisar un Pull Request antes de integrarlo?

La revisión permite detectar errores, comprobar que se cumplan los requisitos, mejorar la calidad de los cambios y evitar que contenido incorrecto llegue a `main`.

### 10. ¿Qué ventaja tiene trabajar en una rama en lugar de modificar directamente `main`?

Trabajar en una rama permite desarrollar y probar cambios de forma aislada, colaborar con mayor seguridad y proteger la versión estable almacenada en `main`.