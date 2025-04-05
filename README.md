
# Aplicación CRUD Simple con React y SQLite

#Link para PDF de cuestionario: [
](https://itlaedudo-my.sharepoint.com/:b:/g/personal/20209410_itla_edu_do/EepZ3rSOcw1Nqfr9ZZZhxjEBEszgj1nyi1MDzasHF3L12Q?e=MctAIf)
Esta es una aplicación básica para gestionar tareas que implementa operaciones CRUD (Crear, Leer, Actualizar, Eliminar).

## Tecnologías utilizadas

- Frontend: React
- Backend: Node.js con Express
- Base de datos: SQLite

## Estructura de Git Flow

El proyecto sigue la metodología Git Flow con las siguientes ramas:
- main: Versión de producción
- develop: Rama de desarrollo principal
- qa: Rama para pruebas de calidad
- feature/setup: Configuración inicial del proyecto
- feature/create: Implementación de la funcionalidad de creación
- feature/read: Implementación de la funcionalidad de lectura
- feature/update: Implementación de la funcionalidad de actualización
- feature/delete: Implementación de la funcionalidad de eliminación

## Configuración del proyecto

1. Clona el repositorio
2. Instala las dependencias:
   ```
   npm run setup
   ```
3. Inicia el servidor y el cliente:
   ```
   npm run dev
   ```
4. Abre http://localhost:3000 en tu navegador

## Funcionalidades

- Crear nuevas tareas con título, descripción y estado
- Ver la lista de tareas existentes
- Actualizar tareas existentes
- Eliminar tareas

## API Endpoints

- GET /api/tasks - Obtener todas las tareas
- GET /api/tasks/:id - Obtener una tarea específica
- POST /api/tasks - Crear una nueva tarea
- PUT /api/tasks/:id - Actualizar una tarea existente
- DELETE /api/tasks/:id - Eliminar una tarea
*/
