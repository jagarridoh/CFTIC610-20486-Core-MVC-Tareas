1. **Nombres y apellidos:** Justo Antonio Garrido Herrador
2. **Fecha:** entrega 06-12-2020
3. **Laboratorios / Demos**: 
   
      1. **Demo Módulo 3**: Fichero de Instrucciones: Instructions\20486D_MOD03_DEMO.md. 
      2. **Laboratorio Módulo 3**: Fichero de Instrucciones: Instructions\20486D_MOD03_LAK.md
4. **Resumen del Ejercicio:**
      
      1. **Objetivos**: 
         1. Demo y Laboratorio Módulo 3: configurar el middleware mediante *app.Use* y *app.Run*. Servir elementos estáticos situados en *wwwroot* mediante *app.UseStaticFiles()*, creación de un servicio, activarlo en *ConfigureServices()* mediante *services.AddSingleton<>()*, configurar su uso en la configuración de middleware en *Startup.cs* en *Configure(..., ILogger logger)* gracias a la Inyección de Dependencias nativa que pasa el singleton y permite la llamada directa *logger.Log("Logged line")*. Usar la inyección de dependencias para pasar servicio creado a un controller. 
      2. **Pasos**: 
            1. Demo y Laboratorio Módulo 3: creación de programación C# y revisión del log generado en sistema de ficheros. 
5. **Dificultad o problemas presentados y como se resolvieron:** 

      1. En el ejercicio 4 del LAK, tuve que configurar el servicio MVC con la siguiente opción, pues en caso contrario ocurría error en runtime:

         ```C#
         services.AddMvc(option => option.EnableEndpointRouting = false); 
         ```

         Y también cambiar la signatura de *Configure* para que compilara: 

         ```C#
         public void Configure(IApplicationBuilder app, Microsoft.AspNetCore.Hosting.IHostingEnvironment env, IPollResultsService pollResults)
         ```

      2. Demo y Laboratorio Módulo 3: la carpeta *wwwroot* no existía y la he creado a mano, dentro de VS2019 en el proyecto o bien en el explorador de Windows. 
7. **Detalles de la entrega**:
   
      1. **Evidencias capturas de pantalla en carpetas**: **MOD * Capturas**. ( ruta: ...\\CFTIC610-20486-Core-MVC-Tareas\20201205 Tarea 3\MOD * Capturas).
      2. **Proyectos modificados** : ver carpetas "**MOD * Proyectos**". ( ruta: ...\CFTIC610-20486-Core-MVC-Tareas\20201205 Tarea 3\MOD * Proyectos).

