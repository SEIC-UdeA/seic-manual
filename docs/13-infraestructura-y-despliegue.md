# 13. Infraestructura y Despliegue

## 13.1 Objetivo

Establecer los lineamientos generales para la gestión de la infraestructura y el despliegue de los proyectos del Semillero de Investigación en Ciberseguridad (SEIC), promoviendo buenas prácticas, seguridad y flexibilidad tecnológica.

---

## 13.2 Conceptos clave

### ¿Qué es la infraestructura?

Es el conjunto de servicios, plataformas, servidores y recursos tecnológicos necesarios para ejecutar un proyecto.

### ¿Qué es un despliegue?

Es el proceso mediante el cual una nueva versión de un proyecto se publica en un ambiente donde puede ser utilizada por sus usuarios.

### ¿Qué es un ambiente?

Es un entorno independiente utilizado durante el ciclo de vida de un proyecto. Un proyecto puede contar con ambientes como desarrollo, pruebas o producción, según sus necesidades.

---

## 13.3 Políticas

### 13.3.1 Independencia de infraestructura

SEIC no establece una infraestructura obligatoria para todos los proyectos.

Cada equipo podrá seleccionar la infraestructura más adecuada según los objetivos, recursos disponibles y características del proyecto.

---

### 13.3.2 Selección de infraestructura

La infraestructura deberá seleccionarse considerando, entre otros, los siguientes criterios:

- Adecuación al proyecto.
- Costos.
- Facilidad de mantenimiento.
- Seguridad.
- Escalabilidad.
- Disponibilidad de documentación y soporte.

---

### 13.3.3 Ambientes

Cuando un proyecto lo requiera, podrá utilizar múltiples ambientes, como desarrollo, pruebas y producción.

La cantidad y el tipo de ambientes dependerán de las necesidades específicas de cada proyecto.

---

### 13.3.4 Despliegue a producción

Los despliegues al ambiente de producción deberán ser realizados o autorizados por el Líder del Proyecto correspondiente.

Antes de realizar un despliegue se deberá verificar, cuando aplique:

- Que los cambios hayan sido integrados correctamente.
- Que la documentación esté actualizada.
- Que las pruebas necesarias hayan sido ejecutadas.

---

### 13.3.5 Automatización

Siempre que sea posible, se recomienda automatizar los procesos de construcción, pruebas y despliegue utilizando herramientas apropiadas.

La automatización deberá implementarse cuando aporte beneficios claros al proyecto.

---

### 13.3.6 Seguridad de la infraestructura

Los proyectos deberán aplicar buenas prácticas de seguridad sobre la infraestructura utilizada, incluyendo la protección de credenciales, la actualización de dependencias y la configuración segura de los servicios desplegados.

---

## 13.4 Procedimientos

### Incorporación de infraestructura a un proyecto

1. Identificar las necesidades del proyecto.
2. Evaluar las alternativas disponibles.
3. Seleccionar la infraestructura más adecuada.
4. Documentar la decisión cuando corresponda.
5. Configurar el ambiente.
6. Realizar el despliegue.

### Despliegue de una nueva versión

1. Verificar que los cambios estén integrados.
2. Confirmar que la documentación se encuentre actualizada.
3. Ejecutar las pruebas definidas por el proyecto.
4. Realizar el despliegue.
5. Verificar el correcto funcionamiento de la nueva versión.

---

## 13.5 Responsabilidades

### Líder del Proyecto

- Definir la estrategia de infraestructura del proyecto.
- Autorizar o realizar los despliegues a producción.
- Verificar que se cumplan las políticas definidas en este capítulo.

### Integrantes

- Colaborar en la configuración y mantenimiento de la infraestructura.
- Documentar los aspectos relevantes cuando sea necesario.
- Seguir las buenas prácticas establecidas por el proyecto.

---

## 13.6 Documentos relacionados

- Tecnologías y Estándares Técnicos.
- Seguridad.
- Gestión de Proyectos.
- Documentación.
- PROJECT.md.
