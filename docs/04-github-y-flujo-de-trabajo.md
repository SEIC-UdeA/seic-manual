# 4. GitHub y Flujo de Trabajo

## 4.1 Objetivo

Establecer el estándar institucional para la gestión del código fuente, el desarrollo colaborativo y el control de versiones de los proyectos del Semillero de Investigación en Ciberseguridad (SEIC).

---

## 4.2 Políticas

### 4.2.1 Organización de GitHub

SEIC utilizará una **Organización de GitHub** como espacio central para alojar todos los repositorios oficiales del semillero.

Cada proyecto aprobado deberá contar con su propio repositorio dentro de la organización.

---

### 4.2.2 Permisos

Los permisos dentro de la organización deberán administrarse bajo el principio de **mínimo privilegio**.

- El **Administrador de Plataformas** tendrá permisos de administración sobre la organización.
- Los integrantes tendrán acceso únicamente a los repositorios en los que participen.
- Los permisos deberán revisarse cuando un integrante ingrese, cambie de proyecto o deje el semillero.

---

### 4.2.3 Estrategia de ramas

Todos los proyectos deberán mantener, como mínimo, las siguientes ramas permanentes:

- `main`: versión estable o de producción.
- `develop`: integración de cambios en desarrollo.

Las demás ramas deberán crearse a partir de `develop` utilizando las siguientes convenciones:

- `feature/`
- `fix/`
- `docs/`
- `refactor/`
- `test/`

Cada rama deberá representar un único objetivo o cambio específico.

---

### 4.2.4 Flujo de desarrollo

Todo trabajo deberá iniciar con la creación de un **Issue**.

Un **Issue** es un registro que representa una tarea, mejora, error o actividad pendiente dentro de un proyecto.

En SEIC, todo trabajo deberá comenzar con la creación de un Issue. Esto permite planificar las actividades, asignar responsables, realizar seguimiento al progreso y mantener un historial organizado de las decisiones y cambios realizados.

Cada Issue deberá contar, como mínimo, con:

- Un título descriptivo.
- Una descripción clara del objetivo.
- Una etiqueta que identifique el tipo de trabajo.
- Un responsable, cuando corresponda.

Siempre que sea posible, las ramas, commits y Pull Requests deberán estar asociados al Issue correspondiente.

El flujo institucional será el siguiente:

1. Crear un Issue.
2. Crear una rama asociada.
3. Desarrollar la solución.
4. Realizar commits siguiendo Conventional Commits.
5. Abrir un Pull Request hacia `develop`.
6. Validar los cambios.
7. Integrar los cambios en `develop`.
8. Cuando corresponda, abrir un Pull Request desde `develop` hacia `main`.

No se permitirá realizar cambios directamente sobre las ramas `main` o `develop`.

---

### 4.2.5 Pull Requests

Toda integración entre ramas deberá realizarse mediante Pull Request.

Los Pull Requests hacia `main` deberán ser revisados y aprobados por alguno de los siguientes responsables:

- Coordinador del Semillero.
- Administrador de Plataformas.
- Líder del Proyecto correspondiente.

Los Pull Requests hacia `develop` también serán obligatorios, con el fin de mantener un historial claro de los cambios realizados.

---

### 4.2.6 Convención de commits

Todos los proyectos deberán utilizar **Conventional Commits**.

Tipos permitidos:

- `feat`
- `fix`
- `docs`
- `refactor`
- `test`

Ejemplos:

```text
feat: agregar autenticación con GitHub
fix: corregir validación del formulario
docs: actualizar README
refactor: simplificar lógica de autenticación
test: agregar pruebas para el módulo de usuarios
```

---

### 4.2.7 Gestión de Issues

Todo trabajo deberá estar asociado a un Issue.

Etiquetas oficiales:

- `feature`
- `bug`
- `documentation`
- `refactor`
- `test`

Siempre que sea posible, los commits y Pull Requests deberán hacer referencia al Issue correspondiente.

---

### 4.2.8 GitHub Projects

Cada proyecto deberá contar con un tablero en GitHub Projects para gestionar sus actividades.

Estados institucionales:

- Backlog
- Ready
- In Progress
- Review
- Done

---

### 4.2.9 Convención para nombres de repositorios

Todos los repositorios deberán cumplir las siguientes reglas:

- Utilizar únicamente letras minúsculas.
- Separar palabras mediante guiones (`-`).
- Utilizar nombres descriptivos.

Ejemplos:

- `seic-manual`
- `ctf-platform`
- `web-recon-tool`

---

### 4.2.10 Idioma

Los nombres técnicos deberán escribirse en inglés.

La documentación institucional podrá redactarse en español.

---

## 4.3 Procedimientos

Cuando un nuevo proyecto sea aprobado:

1. El Administrador de Plataformas creará el repositorio.
2. Creará el GitHub Project correspondiente.
3. Configurará la estructura inicial del repositorio.
4. Asignará los permisos a los integrantes del proyecto.
5. El Líder del Proyecto iniciará la planificación mediante Issues.

---

## 4.4 Responsabilidades

### Administrador de Plataformas

- Administrar la organización de GitHub.
- Crear repositorios.
- Gestionar permisos.
- Configurar los GitHub Projects.

### Líder del Proyecto

- Supervisar el flujo de trabajo del proyecto.
- Revisar Pull Requests cuando corresponda.
- Verificar el cumplimiento de los estándares establecidos.

### Integrantes

- Seguir el flujo institucional de desarrollo.
- Mantener una relación entre Issues, ramas, commits y Pull Requests.
- Respetar las convenciones definidas en este capítulo.

---

## 4.5 Documentos relacionados

- CONTRIBUTING.md
- README.md
- PROJECT.md
- Plantilla de Issue
- Plantilla de Pull Request
