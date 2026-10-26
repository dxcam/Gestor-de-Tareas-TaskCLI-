# Gestor-de-Tareas-TaskCLI
## Descipción

Programa para registrar tareas universitarias, asignar prioridades y marcar entregas como completadas. 

- **Lenguaje utilizado:** Python
- 

## Objetivo

Planificar y organizar el tiempo dedicado a cada tarea y ver su avance.

## Funcionalidades previstas

El usuario podrá realizar las siguientes actividades:
- Añadir el título de la tarea y establecer la fecha de vencimiento.
- Observar el estado de sus tareas. (Pendiente/Completada)
- Filtrar las tareas por materia o estado.

Además, el programa debe:
- Validar entradas incorrectas y fechas inválidas.
- Guardar los datos en un archivo JSON para no perderlos al cerrar el programa.

## Estado del proyecto

En desarrollo.

## Comportamiento Esperado

- En el menú deberían aparecer las opciones de añadir nueva tarea, listar tareas y salir.
- Al añdir una tarea, debe poderse colocar el título, la fecha en que se entrega la tarea y la asignatura.
- Al listar una tarea, debería existir la opción de filtrar por estado o asignatura. Los estados son completada y pendiente, cuando la tarea esté realizada, el usuario la marca y esta pasa a la lista de tareas completadas.
- Si se coloca una opción que no existe, debería aparecer un mensaje de "Opción no válida. Intente nuevamente". De igual forma, si se coloca una fecha incorrecta, debería aparecer un mensaje de "Fecha incorrecta. Intente nuevamente".
