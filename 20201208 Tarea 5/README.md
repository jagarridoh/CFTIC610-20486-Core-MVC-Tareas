1. **Nombres y apellidos:** Justo Antonio Garrido Herrador

2. **Fecha:** entrega 08-12-2020

3. **Laboratorios / Demos**: 

   - **Demo Módulo 5**: Fichero de Instrucciones: Instructions\20486D_MOD05_DEMO.md. 

   - **Laboratorio Módulo 5**: Fichero de Instrucciones: Instructions\20486D_MOD05_LAK.md

4. **Resumen del Ejercicio:**

      * **Objetivos**: 

        * Demo y Laboratorio Módulo 5: 

          * Creación de vista con *Razor*, paso de info mediante *ViewBag*, programación *Razor*.
          * Utilización de *HTML Helpers* para crear enlaces a acciones *@Html.ActionLink()* y generar URL con *@UrlAction()*. 
          * Bucles *@foreach* en *Razor*. 
          * Paso de parámetros en *HTML Helpers*: *@Html.ActionLink()* y *@UrlAction()*. 
          * Retorno de ficheros en acción de controller mediante *File* de *C#*.
          * Activación de *Tag Helper* en vistas *Razor* mediante  *@addTagHelper* **, Microsoft.AspNetCore.Mvc.TagHelpers*.
          * Uso de *Tag Helpers* de llamada a controller y action: *\<a asp-controller="Employee" asp-action="Index">*. Paso de parámetros en Tag Helpers: *\<a asp-action="Details" asp-route-employeename="@currentName">*.
          * Utilización de la vista incluida por defecto en las demás */Views/_ViewImports.cshtml*. (sin hacer uso de activación *@addTagHelper* ).
          * Uso de *Partial Views*, uso de servicio *PersonProvider* que se nos ha dado ya configurado como *Singleton* e *inyectado* en el *HomeController*, programación *Razor* con bucles *@for* anidados, en una vista que llama a otra *vista parcial* pasando parámetro mediante *@await Html.PartialAsync("_CardDesign", cardIndex)*, vista parcial *_CardDesign* que tiene como modelo el *int* que se le pasa en *cardIndex* y que le sirve para seleccionar de una matriz recibida en *@ViewBag* el elemento a renderizar.
          * Creación de *ViewComponent*, creación de carpetas para situar *View Components*, clase derivada de *ViewComponent* que tiene la lógica del *View Component*, definición en ésta del método *InvokeAsync()*, devolución como *Result* de la vista a renderizar, la cual será la *vista parcial* definida anteriormente quitandole el _ para que deje de considerarse como *vista parcial* y pase a considerarse como *vista de componente*, cambiar el *HTML Helper* de llamada a *vista parcial* por *HTML Helper* de llamada a *View Component*: *@await Component.InvokeAsync()*.
          * Creación de *View* desde método *Action* de *Controller*.
          * *Inyección de dependencias* en vistas mediante *@Inject*.
        * **Pasos**: 
          * Demo y Laboratorio Módulo 5: 
            * creación de elementos en C#.
            * creación de elementos *Razor*.
5. **Dificultad o problemas presentados y como se resolvieron:** ninguno.

6. **Detalles de la entrega**:

   * **Evidencias capturas de pantalla en carpetas**: **MOD * Capturas**. ( ruta: ...\\CFTIC610-20486-Core-MVC-Tareas\20201208 Tarea 5\MOD * Capturas).

   + **Proyectos modificados** : ver carpetas "**MOD * Proyectos**". ( ruta: ...\CFTIC610-20486-Core-MVC-Tareas\20201208 Tarea 5\MOD * Proyectos).

