# 11. Seguridad

## 11.1 Objetivo

Establecer las políticas y buenas prácticas de seguridad para proteger las cuentas, la información, los recursos y la infraestructura del Semillero de Investigación en Ciberseguridad (SEIC).

---

## 11.2 Conceptos clave

### ¿Qué es una cuenta institucional?

Es cualquier cuenta utilizada oficialmente por el semillero para administrar sus plataformas, servicios o comunicaciones.

### ¿Qué es un incidente de seguridad?

Es cualquier evento que comprometa o pueda comprometer la confidencialidad, integridad o disponibilidad de los recursos del semillero.

---

## 11.3 Políticas

### 11.3.1 Protección de cuentas institucionales

Todas las cuentas institucionales deberán utilizar contraseñas robustas y, siempre que sea posible, autenticación multifactor (MFA).

---

### 11.3.2 Gestión de administradores

Los privilegios administrativos deberán asignarse únicamente a quienes los requieran para desempeñar sus funciones.

Los permisos deberán revisarse periódicamente y actualizarse cuando cambien los responsables o un integrante deje el semillero.

---

### 11.3.3 Protección de la información

No deberá compartirse información sensible mediante canales públicos o no autorizados.

La información institucional deberá almacenarse únicamente en las plataformas oficiales definidas por el semillero.

---

### 11.3.4 Gestión de secretos

Las contraseñas, claves API, tokens, llaves SSH y demás secretos no deberán almacenarse en el código fuente ni incluirse en los repositorios.

Cada proyecto deberá utilizar mecanismos adecuados para gestionar esta información de forma segura.

---

### 11.3.5 Reporte de incidentes

Todo integrante que identifique una vulnerabilidad o un incidente de seguridad relacionado con la infraestructura, plataformas o recursos del semillero deberá reportarlo oportunamente al Coordinador del Semillero o al Administrador de Plataformas.

El objetivo será resolver el incidente de manera responsable, preservando la confidencialidad de la información y documentando las acciones realizadas cuando sea necesario.

---

## 11.4 Procedimientos

### Gestión de una cuenta institucional

1. Crear la cuenta utilizando un correo oficial cuando corresponda.
2. Configurar una contraseña robusta.
3. Activar MFA cuando el servicio lo permita.
4. Registrar los responsables de la cuenta.
5. Revisar periódicamente los accesos.

### Atención de un incidente de seguridad

1. Identificar el incidente.
2. Reportarlo al responsable correspondiente.
3. Analizar el impacto.
4. Aplicar las medidas necesarias para mitigar el problema.
5. Documentar el incidente y las acciones realizadas, cuando corresponda.

---

## 11.5 Responsabilidades

### Administrador de Plataformas

- Gestionar las cuentas institucionales.
- Administrar los permisos de acceso.
- Promover la aplicación de las buenas prácticas de seguridad.

### Coordinador del Semillero

- Supervisar la gestión de incidentes relevantes.
- Apoyar la toma de decisiones relacionadas con la seguridad institucional.

### Líder del Proyecto

- Promover buenas prácticas de seguridad dentro de su proyecto.
- Verificar el manejo adecuado de los secretos utilizados por el equipo.

### Integrantes

- Proteger sus credenciales.
- Utilizar responsablemente las plataformas institucionales.
- Reportar incidentes o vulnerabilidades cuando los identifiquen.

---

## 11.6 Documentos relacionados

- GitHub y Flujo de Trabajo.
- Gestión de Integrantes.
- Infraestructura y Despliegue.
- Manual de Organización.
