# CONTRIBUTING.md

# Contribuir al proyecto

Gracias por contribuir a este proyecto de SEIC-UdeA.

Este documento establece el flujo básico que deben seguir los integrantes para realizar cambios en el repositorio.

---

## 1. Antes de comenzar

Todo trabajo deberá comenzar con un **Issue**.

Antes de desarrollar:

1. Identifica o crea el Issue correspondiente.
2. Revisa que el trabajo no esté siendo realizado por otro integrante.
3. Comenta en el Issue si es necesario aclarar algo.
4. Crea una rama asociada al trabajo.

---

## 2. Flujo de trabajo

El flujo general es:

```text
Issue
  ↓
Branch
  ↓
Desarrollo
  ↓
Commits
  ↓
Pull Request
  ↓
develop
  ↓
main
```

Las ramas de trabajo deberán integrarse mediante Pull Request.

---

## 3. Convenciones de ramas

Las ramas deberán utilizar nombres en inglés, en minúsculas y siguiendo la siguiente estructura:

```text
feature/nombre-de-la-funcionalidad
fix/nombre-del-error
docs/nombre-del-cambio
refactor/nombre-del-refactor
test/nombre-de-la-prueba
```

Ejemplos:

```text
feature/user-authentication
fix/login-validation
docs/update-readme
refactor/user-service
test/login-tests
```

---

## 4. Commits

Los commits deberán seguir **Conventional Commits**.

Formato:

```text
tipo: descripción
```

Tipos principales utilizados en SEIC:

```text
feat: nueva funcionalidad
fix: corrección de un error
docs: cambios en documentación
refactor: modificación del código sin cambiar su comportamiento
test: creación o modificación de pruebas
```

Ejemplos:

```text
feat: add user authentication
fix: correct login validation
docs: update project documentation
refactor: simplify user service
test: add authentication tests
```

Los mensajes deberán ser claros y describir brevemente el cambio realizado.

---

## 5. Pull Requests

Todo cambio deberá integrarse mediante un Pull Request.

El Pull Request deberá:

- Tener un título claro.
- Explicar brevemente los cambios realizados.
- Estar relacionado con el Issue correspondiente.
- Indicar las pruebas realizadas cuando corresponda.

### Pull Request hacia `develop`

Los cambios podrán integrarse a `develop` mediante Pull Request sin requerir aprobación.

### Pull Request hacia `main`

Todo cambio destinado a producción deberá pasar mediante Pull Request y contar con la aprobación correspondiente.

Los Pull Requests hacia `main` podrán ser aprobados por:

- Coordinador del Semillero.
- Administrador de la organización.
- Líder del Proyecto.

---

## 6. Issues

Los Issues se utilizarán para organizar y hacer seguimiento al trabajo.

Cada Issue deberá:

- Tener un título claro.
- Describir el trabajo que debe realizarse.
- Tener la etiqueta correspondiente.
- Ser asociado al proyecto cuando corresponda.

Etiquetas principales:

```text
feature
bug
documentation
refactor
test
```

Cuando sea posible, las ramas, commits y Pull Requests deberán estar relacionados con el Issue correspondiente.

---

## 7. Buenas prácticas

- Mantener los cambios relacionados con el objetivo del Issue.
- Evitar incluir cambios innecesarios.
- Mantener la documentación actualizada.
- Escribir código claro y mantenible.
- Realizar las pruebas correspondientes antes de crear el Pull Request.
- No incluir credenciales, contraseñas, tokens u otros secretos en el repositorio.
- Revisar los cambios antes de enviarlos.

---

## 8. Dudas y colaboración

Si existe alguna duda sobre el funcionamiento del proyecto, el integrante deberá consultar al Líder del Proyecto o utilizar los canales de comunicación establecidos por SEIC.
