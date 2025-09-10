# EV_PARCIAL_INGENIERIA_DEVOPS_1
Repositorio dedicado al desarrollo de la primera evaluación de la asignatura Ingeniería DevOps.

Para la creación de los archivos del repositorio utilizamos el formato TBD, el cual justificamos a continuación.

Para la realización de la evaluación, elegimos implementar Trunk-based Development, ya que es bastante recomendado en proyectos pequeños, justo como el que nos compete llevar a cabo en este momento.

## Flujo de trabajo con ramas

Usamos el siguiente flujo de ramas:

- `main`: Rama principal, estable.
- `feature/contributing-doc`: Para documentación de CONTRIBUTING.md.

## ¿Cómo contribuir?

Lee el archivo [CONTRIBUTING.md](./CONTRIBUTING.md) para conocer las reglas de colaboración.

## Convenciones de commit 

- Commits en español.
- Titulos cortos.
- Descripción simple solo con lo necesario.

## Flujos de merge

- Pull request obligatorio hacia la rama main una vez terminada la funcionalidad.
- Revisión e intregración con la rama main realizada por un compañero de trabajo.

## Naming de ramas

- `feature/<nombre>`: Para agregar nuevas funcionalidades o nuevos apartados a ya existentes, el nombre debe ser representativo.
- `hotfix/<nombre>`: Para arreglar funcionalidades ya existentes, el nombre debe ser representativo.

## Estrategias de revisión

- Trunk-Based Development (TBD) → ramas cortas que se integran rápido a main.
- Para mayor información vaya al link que se encuentra en el apartado de "¿Cómo contribuir?"

## Automatización (CI/CD)

Este repositorio cuenta con un workflow de GitHub Actions que:

- Se activa en cada `push` o `pull request`.
- Ejecuta la acción `DavidAnson/markdownlint-cli2-action@v20`.
- Valida todos los archivos `.md` según las reglas definidas en `.markdownlint.json`.
- Falla si algún archivo no cumple con las reglas.

Puedes ver los resultados en la pestaña [Actions](https://github.com/NBello26/MiPrimerDevOps/actions).

## Licencia

Este proyecto está licenciado bajo la [MIT License](./LICENSE.md).

---

¡Gracias por visitar el proyecto! ✨