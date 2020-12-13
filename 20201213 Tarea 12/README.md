1. **Nombres y apellidos:** Justo Antonio Garrido Herrador

2. **Fecha:** entrega 13-12-2020

3. **Laboratorios / Demos**: 

   - **Demo Módulo 12**: Fichero de Instrucciones: Instructions\20486D_MOD12_DEMO.md. 

   - **Laboratorio Módulo 12**: Fichero de Instrucciones: Instructions\20486D_MOD12_LAK.md

4. **Resumen del Ejercicio:**

      * **Objetivos**: 
        
        * Demo y Laboratorio Módulo 12: 
          * Uso de *[NotMapped]* en modelo. 
          * Uso de *ViewComponent*.
          * Cacheado de recuperación de BD mediante *tag helper:  \<cache vary-by="@ViewBag.SelectedProductId">*.
          * Uso de información de estado: configuración de su servicio: *services.AddSession();* inclusión en la pipeline: *app.UseSession();* guardar y recuperar de *HttpContext.Session*. Utilización de *HTML Helper: @Context.Session.Get...(..)*.
          * Creación y uso de servicio (*SquareManager*).
          * Uso de web sockets mediante *SignalR*: utilización de servicio *services.AddSignalR()*, añadido en pipeline: *app.UseSignalR(...)*, creación de *Hub* *SquaresHub.cs*, definición de ruta del hub *routes.MapHub<SquaresHub>("/squareshub")*, añadido de dependencia NPM *"@aspnet/signalr": "1.0.0"*, programación JS necesaria.
          * Utilización de memoria caché: *Microsoft.Extensions.Caching.Memory*, inyección en el constructor del controlador, recuperación y guardado en caché (*TryGetValue(), MemoryCacheEntryOptions(), Set())*. 
          * Envío de mensaje *SendAsync(...)*.
        
      * **Pasos**: 
      
        * Demo y Laboratorio Módulo 12: 
          * Generación de C# y modificación de C# existentes.
          * Utilización de módulos NPM y su inclusión en la pipeline *app.UseNodeModules(env.ContentRootPath);*, revisión en *node_modules*.


5. **Dificultad o problemas presentados y como se resolvieron:** ninguno (hecho en clase).

6. **Detalles de la entrega**:

   * **Evidencias capturas de pantalla en carpetas**: **MOD * Capturas**. ( ruta: ...\\CFTIC610-20486-Core-MVC-Tareas\20201213 Tarea 12\MOD * Capturas).

   + **Proyectos modificados** : ver carpetas "**MOD * Proyectos**". ( ruta: ...\CFTIC610-20486-Core-MVC-Tareas\20201213 Tarea 12\MOD * Proyectos).

