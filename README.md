# Gestor de Proyectos para Pequeñas Empresas

## Descripción
Esta aplicación permite a las pequeñas empresas gestionar sus proyectos y tareas de manera eficiente, incluyendo asignación de responsables y seguimiento del estado de las actividades.

## Funcionalidades principales
- Creación y gestión de proyectos y tareas.
- Asignación de responsables a tareas.
- Automatización del flujo de trabajo.
- Informes y paneles para estadísticas.

## Estructura de objetos
1. **Proyecto**
   - Campos: Nombre, Fecha de inicio, Fecha de finalización, Estado, Descripción.
   - Relación con Contacto (búsqueda).
   - Relación con Tarea (Maestro-Detalle).
2. **Tarea**
   - Campos: Nombre, Estado, Fecha de vencimiento, Proyecto relacionado, Responsable.

   ## Relaciones
- **Proyecto - Tarea:** Relación Maestro-Detalle.
- **Proyecto - Contacto:** Relación de búsqueda.
- **Tarea - Contacto:** Relación de búsqueda.


## Próximos pasos
//1. Crear los objetos personalizados. (Listo)


2. Diseñar automatizaciones y lógica.
3. Desarrollar la interfaz de usuario.