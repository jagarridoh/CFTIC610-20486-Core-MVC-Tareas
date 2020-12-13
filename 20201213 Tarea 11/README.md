1. **Nombres y apellidos:** Justo Antonio Garrido Herrador

2. **Fecha:** entrega 13-12-2020

3. **Laboratorios / Demos**: 

   - **Demo Módulo 11**: Fichero de Instrucciones: Instructions\20486D_MOD11_DEMO.md. 

   - **Laboratorio Módulo 11**: Fichero de Instrucciones: Instructions\20486D_MOD11_LAK.md

4. **Resumen del Ejercicio:**

      * **Objetivos**: 
        * Demo y Laboratorio Módulo 11: 
          * Configurar autenticación: en startup.cs se añade el servicio de identificación mediante *AddDefaultIdentity* pasándole la clase que gestiona usuarios *Student*y se configura las reglas de formato de contraseña. 
          * Activar en la pipeline en startup.cs en Configure:  *app.UseAuthentication()* de manera que se impide el acceso al resto de la pipeline de los usuario no autenticados. En StudentController, en caso de no estar autenticado se envía al login. 
          * Creación de controller para el login y el registro de usuarios: *AccountController.cs*. En caso de login exitoso envía a controller Student, vista Index. Verifica la contraseña en acción *Login* accediendo por *Post*, creación de *Logout()*. Utiliza los servicios SignInManager y UserManager mediante inyección de dependencias, para tratar passwords/sesiones y usuarios respectivamente. Creación de acción *AccessDenied()*.
          * Utilización de servicio *Identity* para autenticación y autorización.
          * Crear clase de autenticación a medida heredando de *IdentityUser*.
          * Crear clase auxiliar para acceso a BD heredando de *IdentityDbContext*.
          * Modificar vista layout añadiendo opciones de menú de Login / Logout.
          * Uso de atributos *[AllowAnonymous]*, *[Authorize]*. Uso de:  *[Authorize(Roles = "Administrator")]* para autorización basada en roles.
          * Utilización en *AccountController* de *RoleManager* mediante inyección de dependencias. Registro de usuarios en BD en *AccountController*.
          * Autenticación basada en políticas *Claims*. Añadido de políticas en el servicio *AddAuthorization*. Uso de *[Authorize(Policy = "RequireEmail")]*.
          * Evitar ataque *CSRF (Cross-Site Request Forgery)*. Creación de proyecto auxiliar para su test. Utilización de atributo *[ValidateAntiForgeryToken]* para evitarlo.
        
      * **Pasos**: 
        * Demo y Laboratorio Módulo 11: 
    * Generación de C# y modificación de C# existentes.
        * Utilización de componentes NPM. Utilización de SQLite.
        * Pruebas CSRF.


5. **Dificultad o problemas presentados y como se resolvieron:** ninguno (hecho en clase).

6. **Detalles de la entrega**:

   * **Evidencias capturas de pantalla en carpetas**: **MOD * Capturas**. ( ruta: ...\\CFTIC610-20486-Core-MVC-Tareas\20201213 Tarea 11\MOD * Capturas).

   + **Proyectos modificados** : ver carpetas "**MOD * Proyectos**". ( ruta: ...\CFTIC610-20486-Core-MVC-Tareas\20201213 Tarea 11\MOD * Proyectos).

