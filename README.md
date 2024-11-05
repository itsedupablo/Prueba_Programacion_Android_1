# Prueba de Programación Android 1 
### Enlace al repositorio: https://github.com/itsedupablo/Prueba_Programacion_Android_1
## EJERCICIO 1: Aplicación de gestión de tareas "Mis Recordatorios"
### Descripción
El objetivo de este ejercicio es realizar una aplicación que sirva para que el usuario tenga una lista actualizada de tareas pendientes de ser realizadas. De cada tarea sólo se almacenará un texto que la describa. La tarea se añadirá automáticamente a una lista de tareas pendientes que el usuario visualizará en la misma Activity. Desde esa lista, mediante un menú contextual, el usuario podrá eliminar o bien marcarla como “Hecha”, en cuyo caso irá a parar a otra lista de tareas realizadas. El usuario también dispondrá de dos botones que permitirán visualizar las tareas pendientes o las ya realizadas en el ListView

### Estructura
Se ha hecho uso de 2 clases:
- **MainActivity.** Clase principal donde se desarrolla toda la lógica de la aplicación (la app solo cuenta con una pantalla).
- **BDHelper.** Clase que ayuda a la integración de una Base de Datos


## EJERCICIO 2: Lista de la compra
### Descripción
El objetivo de este ejercicio es realizar una aplicación que sirva como lista de la compra. El usuario podrá introducir tanto el nombre del producto como la cantidad y su precio aproximado. Hay que tener en cuenta que el único dato obligatorio será el nombre del producto, pudiéndose dejar en blanco los otros dos. La aplicación mostrará siempre el número de productos de la lista y el precio total de la misma (contabilizando solamente aquellos productos para los que se ha indicado su precio).

### Estructura
Se ha hecho uso de 4 clases:
- **MainActivity.** Clase principal donde se desarrolla toda la lógica de la aplicación (la app solo cuenta con una pantalla).
- **BDHelper.** Clase que ayuda a la integración de una Base de Datos
- **Producto.** Clase que permite crear instancias de productos. En este caso se ha añadido esta clase ya que a diferencia de en el ejercicio 1 donde solo había que guardar el nombre en la lista, en este ejercicio hay que almacenar también otros atributos por lo que la creación de objetos lo facilita.
- **ProductoAdapter.** Clase que permite la conversión de cada objeto "Producto" en una vista legible para mostrarlo en la ListView de forma personalizada


## EJERCICIO 3: Aplicación de gestión de tareas "Mis Recordatorios" (Ampliada)
### Descripción
El objetivo de este ejercicio es realiza una aplicación que sirva como lista de tareas (MisTareas2) pero en este caso la aplicación constará de 3 Activities: registro de tareas, listado de tareas y detalles de tareas. La aplicación seguirá el diseño que se indica en las siguientes capturas de pantalla:

### Estructura
 **MainActivity.** Clase principal donde se desarrolla toda la lógica de la aplicación (la app solo cuenta con una pantalla).
- **BDHelper.** Clase que ayuda a la integración de una Base de Datos
- **Tarea.** Clase que permite crear instancias de productos. En este caso se ha añadido esta clase ya que a diferencia de en el ejercicio 1 donde solo había que guardar el nombre en la lista, en este ejercicio hay que almacenar también otros atributos por lo que la creación de objetos lo facilita.
- **RegistroTareasActivity.** Clase asociada con la activity que maneja la creación de un objeto tarea con sus atributos correspondientes.
- **InfoTareasActivity.** Claseasociada con la activity que maneja la visualización de los atributos de una tarea (añadidos en la pantalla de registro de tareas).

