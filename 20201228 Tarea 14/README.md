1. **Nombres y apellidos:** Justo Antonio Garrido Herrador

2. **Fecha:** entrega 29-12-2020

3. **Laboratorios / Demos**: 
   
   - **Demo Módulo 14**: Fichero de Instrucciones: Instructions\20486D_MOD14_DEMO.md. 
   - **Laboratorio Módulo 14**: Fichero de Instrucciones: Instructions\20486D_MOD14_LAK.md
   
4. **Resumen del Ejercicio:**

   * **Objetivos**: 
     
      * Despliegue en Azure: creación de *App Service*, *resource group*, *Hosting Plan*, *Service Plan*. Publicación desde MS Visual Studio. Revisión de la web publicada en Azure. 
      * Azure: almacenamiento *Blob*: crear *Storage Account* en Azure, tipo *Blob*, *Container*, subida manual de *Blobs*. Crear App desde *Marketplace*: *Web App + SQL* (creación de BD).
      * En el proyecto VS: crear *Connected Service* de *Cloud Storage Azure*, *Connection String* en *appsettings.json* utilizado en controlador. Dependencia *NuGet* *WindowsAzure.Storage*. Clases *CloudStorageAccount*, *CloudBlobClient*, *CloudBlobContainer*. Métodos: *GetContainerReference*, *SetPermissionsAsync*, *UploadFromStreamAsync*, *GetBlockBlobReference*.
      * Utilización de *Migrations* (*Add-Migration InitialCreate*, *Update-Database*, *Add-Migration*).
      * Modificación de proyecto para poder ser publicado en Azure. Despliegue/Publicación en Azure. *Connection Strings*.
   * **Pasos**:  Generación de programación y elementos en C# en MSVisualStudio 2019. Inclusión de dependencias NPM y NuGet en el proyecto. Creación en Azure de recursos.
   
5. **Dificultad o problemas presentados y como se resolvieron:**  

   * Los que vimos en clase.
   * Hizo falta crear la columna nueva *ImageURL* a mano desde Azure. Es debido a  que tuve que repetir la práctica con un nuevo proyecto en local pero no repetí la parte de Azure y entonces no funcionaron las migraciones de BD.

6. **Detalles de la entrega**: 

   * La aplicación se puede ver en: http://underwaterjagh.azurewebsites.net/

   * **Evidencias capturas de pantalla en carpetas**: **MOD * Capturas**. ( ruta: ...\\CFTIC610-20486-Core-MVC-Tareas\20201228 Tarea 14\MOD * Capturas).

   + **Proyectos modificados** : ver carpetas "**MOD * Proyectos**". ( ruta: ...\CFTIC610-20486-Core-MVC-Tareas\20201228 Tarea 14\MOD * Proyectos).

