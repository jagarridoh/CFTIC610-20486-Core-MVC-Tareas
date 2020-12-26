1. **Nombres y apellidos:** Justo Antonio Garrido Herrador

2. **Fecha:** entrega 26-12-2020

3. **Laboratorios / Demos**: 
   - **Demo Módulo 7**: Fichero de Instrucciones: Instructions\20486D_MOD07_DEMO.md. 
   - **Laboratorio Módulo 7**: Fichero de Instrucciones: Instructions\20486D_MOD07_LAK.md
4. **Resumen del Ejercicio:**
   * **Objetivos**: 
      * Demo y Laboratorio Módulo 07: 
          * Utilización de *Entitity Framework Core*: añadido de paquetes *NuGet* para *Sqlite* y *namespaces*.
          * Creación de *PersonContext* heredada de *DbContext*, método *OnModelCreating(...)* para creación de datos de pruebas, añadido de *PersonContext* a los servicios en *ConfigureServices* usando BD *Sqlite*. Llamada en la *pipeline* a *personContext.Database.EnsureDeleted()* y *EnsureCreated()*.
          * Definir el controlador de la clase de modelo *Person*: *PersonController*, con inyección del contexto, definir métodos *Edit Create Delete Update* y el *Index* como lectura.
          * Utilización del patrón de diseño *Repository*: creación de interfaz y clase, métodos *Get* (lectura), *Create*, *Update*, *Delete*, uso de BD *SQLServer* a través del *context*, que ahora utiliza *ConnectionString* MSSQL. Cambios similares en el middleware: servicios y pipeline.
          * Volver a crear el controlador *PersonController* esta vez inyectándole el *repository* en lugar del *context*. En este caso los métodos *Edit, Delete, Create* se pasan directamente al *Repository* en lugar de implementarse en el *Controller*. Recuperar datos desde otros controllers. Acciones en *Controller* para guardar datos editados (*EditPost*), crear (*CreatePost*), borrar (*DeletePost*).
          * Uso de anotaciones en Modelo para definir campos en BBDD: tipo de dato, longitud de campo, obligatoriedad, clave de tabla, no mapeado en BBDD  (y también validaciones en vista de edición). Propiedad *virtual*.
          * Uso de *MS SQL Server*: cambio de cadena de conexión, definición en fichero de configuración.
          * Utilización de *Migrations* para gestionar y automatizar cambios en BBDD:  *Add-Migration InitialCreate, Update-Database,  Add-Migration AddCupcakeCaloricValue, Update-Database*. Prueba añadiendo atributo en modelo, y también sus elementos correspondientes en vistas. No se cambió nada en controller, pero quizás si hubiera hecho falta cambiar en la acción *EditPost(int id)* de *CupcakeController*.
      * **Pasos**:  Demo y Laboratorio Módulo 07: Generación de programación y elementos en C# en MSVisualStudio 2019. Inclusión de dependencias *NuGet*.
5. **Dificultad o problemas presentados y como se resolvieron:** ninguno.

6. **Detalles de la entrega**:

   * **Evidencias capturas de pantalla en carpetas**: **MOD * Capturas**. ( ruta: ...\\CFTIC610-20486-Core-MVC-Tareas\20201223 Tarea 7\MOD * Capturas).

   + **Proyectos modificados** : ver carpetas "**MOD * Proyectos**". ( ruta: ...\CFTIC610-20486-Core-MVC-Tareas\20201223 Tarea 7\MOD * Proyectos).

