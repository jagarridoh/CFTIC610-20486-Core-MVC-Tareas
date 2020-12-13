1. **Nombres y apellidos:** Justo Antonio Garrido Herrador

2. **Fecha:** entrega 13-12-2020

3. **Laboratorios / Demos**: 

   - **Demo Módulo 6**: Fichero de Instrucciones: Instructions\20486D_MOD06_DEMO.md. 

   - **Laboratorio Módulo 6**: Fichero de Instrucciones: Instructions\20486D_MOD06_LAK.md

4. **Resumen del Ejercicio:**

      * **Objetivos**: 
* Demo y Laboratorio Módulo 6: 
        
  * Creación de Modelo en MVC. Definición de propiedades. 
          * Preparar Controller asociado al modelo.
              * Enlazar (bind) vistas con modelos mediante *@model BindViewsExample.Models.Restaurant*. Envío de datos desde Controller a vista.
              * Recuperación en la vista de datos del modelo (*@Model.propiedad*)
              * Generación de vista de edición mediante el *HTML Helper @Html.EditorForModel()*. Es una *Strongly Typed View*.
              * Atributos en modelo que definen la vista *[Display(...)], [DataType(...)], [DisplayFormat(DataFormatString...]*.
              * Creación de formulario mediante *tag helpers \<label asp-for...> \<input asp-for...>* y también mediate *HTML Helper @Html.DisplayNameFor(model => model.nombre_propiedad)* y *@HtmlDiplayFor(...)*.
              * Creación de validaciones mediante atributos *[Required(...)], [Range(...)], [StringLength(...)]*.
              * Creación de elementos para los mensajes de errores de validación mediante *tag helpers <span asp-validation-for="... y <div asp-validation-summary="All"*.
              * Creación de clase *Validator* y aplicación mediante atributo a medida *[InUniversityValidation]*.
              * Creación de *ViewModel*. Uso en una vista.
              * Creación de acciones de controller que hacen uso de modelo (creación de instancia).
              * Envío de imágenes a vista mediante *return File(...)*. Su uso mediante *HTML Helper <img ... src=""@Url.Action(...)*.
              * Uso de *Form Helpers* para definir el *<form...>* HTML y su action.
              * Creación de validador a medida con parámetro: *[MaxButterflyQuantityValidation(50)]*.
      
      * **Pasos**: 
        * Demo y Laboratorio Módulo 6: 
          * Generación de C# (Modelos, Validator).
          * Modificación de C# existentes (Controllers, Vistas).
      
5. **Dificultad o problemas presentados y como se resolvieron:** ninguno.

6. **Detalles de la entrega**:

   * **Evidencias capturas de pantalla en carpetas**: **MOD * Capturas**. ( ruta: ...\\CFTIC610-20486-Core-MVC-Tareas\20201212 Tarea 6\MOD * Capturas).

   + **Proyectos modificados** : ver carpetas "**MOD * Proyectos**". ( ruta: ...\CFTIC610-20486-Core-MVC-Tareas\20201212 Tarea 6\MOD * Proyectos).

