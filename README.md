# Manual de Instalación y Configuración de Moodle

## Introducción
Este repositorio es el proceso de instalación y configuración de Moodle en IsardVDI. Se incluyen capturas de pantalla y explicaciones paso a paso.

## 1. Instalación de Moodle
### 1.1 Descarga de Moodle
Visita [Moodle.org](https://moodle.org) y descarga la última versión.

### 1.2 Instalación en IsardVDI
Sigue los pasos del manual de instalación de aplicaciones web proporcionado.
Sube los archivos de Moodle al servidor y sigue el asistente de instalación.

## 2. Configuración Inicial
### 2.1 Configurar Administrador
Inicia sesión como administrador.
Cambia el correo electrónico, la contraseña y añade un avatar.

<img src="moodle 1.png" width="700" height="500">

### 2.2 Configuración del Sitio
Cambia el nombre del sitio en `Administración del sitio > Primera plana > Parámetros`.
Oculta la página principal para usuarios no autenticados.
Verifica la franja horaria en `Administración del sitio > Ubicación > Parámetros`.
Cambia el idioma en `Administración del sitio > Idioma > Parámetros` y descarga nuevos paquetes de idioma si es necesario.
Ajusta la política de contraseñas en `Administración del sitio > Seguridad > Normativas del sitio`.

<img src="moodle 4.png" width="700" height="500">


<img src="moodle6.png" width="700" height="500">
 
## 3. Creación y Gestión de Cursos
### 3.1 Crear Cursos
Crea un curso **A** con 3 temas y un curso **B** con 5 temas en `Administración del sitio > Gestiona cursos y categorías`.
Añade contenido (ejemplo: documentos PDF).

<img src="moodle9.png" width="700" height="500">

<img src="temab1.png" width="700" height="500">

<img src="temab2.png" width="700" height="500">

<img src="moodle10.png" width="800" height="500">

### 3.2 Administración de Usuarios
Crea manualmente un usuario `Bob`.
Genera 10 alumnos y súbelos mediante un archivo CSV (`Administración del sitio > Usuarios > Cargar usuarios`).
Elimina 2 alumnos desde `Acciones con usuarios en bloque`.

<img src="moodle11.png" width="700" height="500">

<img src="moodle12.png" width="700" height="500">

<img src="usuarios1.png" width="700" height="500">

<img src="moodle13.png" width="800" height="500">

<img src="eliminar1.png" width="800" height="500">

### 3.3 Matriculación de Usuarios
Configura el curso A como público sin inscripción.
Configura el curso B para inscripción manual.
Matricula `Bob` como profesor en el curso B y los alumnos desde el CSV como estudiantes.

<img src="moodle14.png" width="700" height="500">

<img src="matricula1.png" width="800" height="600">

<img src="bobprofesor2.png" width="800" height="500">

## 4. Personalización
### 4.1 Cambiar Apariencia
Descarga e instala un nuevo tema en `Administración del sitio > Conectores > Instal·lar complemento`.
Personaliza la cabecera y el pie de página.

<img src="complementos1.png" width="700" height="500">

<img src="complementos2.png" width="700" height="500">

<img src="tema1.png" width="700" height="500">

<img src="tema2.png" width="700" height="500">

## 5. Seguridad y Administración
Banea una IP desde `Administración del sitio > Seguridad > Restricciones IP`.

<img src="ip1.png" width="700" height="500">

<img src="ip2.png" width="700" height="500">

Aplica una política de seguridad justificando su necesidad.

<img src="ip3.png" width="700" height="500">

## 6. Importación y Exportación de Cursos
Exporta un curso desde `Administración > Cursos > Copias` y envíalo a un compañero.
Importa un curso de otro usuario.

## 7. Evaluaciones y Actividades
### 7.1 Creación de Actividades
Crea actividades evaluables en el curso A. 
Configura tareas con fecha de entrega.
Crea un cuestionario con preguntas del banco de preguntas.

### 7.2 Calificaciones y Certificación
Configura la calificación automática en `Administración del Curso > Configuración de calificaciones`.
Crea una insignia y otórgala a un alumno destacado.
