# Proyecto: Creando Requisitos de Producto con IA

## Nombre del producto

**StudyAI**

---

# Planificador de Producto MVP

## Problema

Muchos estudiantes tienen dificultades para organizar su tiempo de estudio, priorizar tareas y preparar exámenes de manera eficiente.

## Público objetivo

- Estudiantes universitarios.
- Estudiantes de bachillerato.
- Personas que preparan oposiciones.
- Estudiantes de cursos online.

## Propuesta de valor

StudyAI ayuda a los estudiantes a organizar automáticamente su estudio mediante Inteligencia Artificial, generando planes personalizados según sus asignaturas, tareas y fechas de examen.

## Objetivo del MVP

Permitir que un estudiante pueda:

- Registrarse en la plataforma.
- Crear y administrar sus asignaturas.
- Registrar fechas de exámenes.
- Obtener un plan de estudio generado automáticamente por IA.

## Funcionalidades principales

### Gestión de usuarios

- Registro de usuario.
- Inicio de sesión.
- Edición del perfil.

### Gestión académica

- Crear asignaturas.
- Editar asignaturas.
- Eliminar asignaturas.
- Registrar tareas.
- Registrar exámenes.

### Planificación con IA

- Generar automáticamente un calendario de estudio.
- Reorganizar el plan cuando cambien las fechas de examen.

### Dashboard

- Visualizar próximas tareas.
- Ver exámenes pendientes.
- Consultar el progreso del estudio.

## Funcionalidades fuera del alcance del MVP

- Chat entre estudiantes.
- Integración con Google Calendar.
- Aplicación móvil.
- Sistema de gamificación.
- Compartir apuntes.

## Beneficio principal

Reducir el tiempo dedicado a organizar el estudio y ayudar al estudiante a prepararse de forma más eficiente.

---

# Documento de Requisitos del MVP

## Descripción del producto

StudyAI es una aplicación web que utiliza Inteligencia Artificial para ayudar a estudiantes a planificar su tiempo de estudio mediante la creación automática de calendarios personalizados.

## Objetivos

### Objetivo principal

Ayudar a los estudiantes a organizar su estudio de forma inteligente.

### Objetivos secundarios

- Reducir el estrés antes de los exámenes.
- Mejorar la productividad.
- Automatizar la planificación semanal.

---

## Usuarios objetivo

- Universitarios.
- Estudiantes de secundaria.
- Personas que preparan oposiciones.
- Estudiantes de formación online.

---

## Requisitos funcionales

### Gestión de usuarios

- El sistema permitirá crear una cuenta.
- El sistema permitirá iniciar sesión.
- El usuario podrá modificar su perfil.

### Gestión de asignaturas

- Crear asignaturas.
- Editar asignaturas.
- Eliminar asignaturas.

### Gestión de exámenes

- Registrar una fecha de examen.
- Asociar el examen a una asignatura.

### Planificador con IA

La Inteligencia Artificial deberá:

- Analizar las fechas de examen.
- Calcular el tiempo disponible.
- Distribuir las sesiones de estudio.
- Reorganizar automáticamente el calendario cuando cambie alguna fecha.

### Dashboard

El usuario podrá visualizar:

- Próximos exámenes.
- Tareas pendientes.
- Progreso del estudio.
- Horas recomendadas por día.

---

## Requisitos no funcionales

- Interfaz responsive.
- Tiempo de respuesta inferior a 2 segundos.
- Autenticación segura mediante JWT.
- Almacenamiento persistente en base de datos.
- Diseño sencillo e intuitivo.

---

## Tecnologías sugeridas

### Frontend

- React

### Backend

- Flask o FastAPI

### Base de datos

- PostgreSQL

### Inteligencia Artificial

- API de OpenAI

### Autenticación

- JWT

---

## Historias de usuario

### Historia 1

**Como estudiante**, quiero registrar mis asignaturas para organizar mejor mi estudio.

### Historia 2

**Como estudiante**, quiero añadir las fechas de mis exámenes para que la IA genere automáticamente un plan de estudio.

### Historia 3

**Como estudiante**, quiero consultar mi progreso para saber cuánto me queda por estudiar.

### Historia 4

**Como usuario**, quiero modificar mi planificación cuando cambien las fechas de examen.

---

## Criterios de aceptación

- El usuario puede registrarse correctamente.
- El usuario puede iniciar sesión.
- El usuario puede crear asignaturas.
- El usuario puede registrar exámenes.
- La IA genera un calendario personalizado.
- El usuario puede visualizar su planificación.

---

## Riesgos del proyecto

- La planificación generada por la IA puede no ajustarse a todos los estilos de estudio.
- Cambios frecuentes en las fechas de examen pueden requerir múltiples reorganizaciones.
- Dependencia de servicios externos para el funcionamiento de la IA.

---

## Mejoras futuras

- Aplicación móvil para Android e iOS.
- Integración con Google Calendar.
- Sistema de recordatorios mediante notificaciones.
- Chat con tutores o profesores.
- Sistema de gamificación con logros y recompensas.
- Estadísticas avanzadas sobre hábitos de estudio.

---

# Prompt utilizado para generar los requisitos con IA

```text
Actúa como un Product Manager Senior especializado en desarrollo de software.

Necesito crear un Documento de Requisitos para un MVP de una aplicación llamada StudyAI.

El producto ayuda a estudiantes a organizar su tiempo mediante Inteligencia Artificial.

Genera un documento profesional que incluya:

- Descripción del producto.
- Objetivos.
- Usuarios objetivo.
- Requisitos funcionales.
- Requisitos no funcionales.
- Historias de usuario.
- Criterios de aceptación.
- Riesgos del proyecto.
- Mejoras futuras.
- Tecnologías recomendadas.
```

---

# Conclusión

El MVP de **StudyAI** está diseñado para validar una idea de negocio enfocada en la organización del estudio mediante Inteligencia Artificial. Esta primera versión incorpora únicamente las funcionalidades esenciales para que los usuarios puedan registrar sus asignaturas, introducir las fechas de sus exámenes y recibir un plan de estudio personalizado, permitiendo obtener retroalimentación temprana antes de desarrollar características más avanzadas.
