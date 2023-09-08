# Incidencias CampusLands

_proyecto personal junto con documentacion con el objetivo de mejorar mis habilidades en BackEnd_

## Para clonar repositorio 🚀

```
git clone https://github.com/soymariam10/incidenciascorregido.git
```


## Instalacion de paquetes 📦
---
_Que cosas necesitas para instalar el software y como instalarlas_

1. Instalar Gestor de paquetes y despues hacer las debidas instalaciones desde Command Palette (ctrl+shift+p)
2. instalar la ultima version de cada paquete en su carpeta correspondiente

## Gestor de paquetes Nugets (https://www.nuget.org/)

## Dentro del proyecto API  🛠️

* [ayuda a controlar y limitar la cantidad de solicitudes que una aplicación web puede recibir en un tiempo determinado] (https://www.nuget.org/packages/AspNetCoreRateLimit) AspNetCoreRateLimit
* [Biclioteca de Mapeo] (https://www.nuget.org/packages/AutoMapper.Extensions.Microsoft.DependencyInjection) AutoMapper.Extensions.Microsoft.DependencyInjection
* [ validar y autenticar tokens JWT] (https://www.nuget.org/packages/Microsoft.AspNetCore.Authentication.JwtBearer/8.0.0-preview.7.23375.9) Microsoft.AspNetCore.Authentication.JwtBearer
* [Gestion de Versiones de API] (https://www.nuget.org/packages/Microsoft.AspNetCore.Mvc.Versioning) Microsoft.AspNetCore.Mvc.Versioning
* [documentación automática de API utilizando el estándar OpenAPI] (https://www.nuget.org/packages/Microsoft.AspNetCore.OpenApi/8.0.0-preview.7.23375.9) Microsoft.AspNetCore.OpenApi
* [ tareas relacionadas con el diseño y la gestión de modelos de datos] (https://www.nuget.org/packages/Microsoft.EntityFrameworkCore.Design/8.0.0-preview.7.23375.4) Microsoft.EntityFrameworkCore.Design

## Dentro del proyecto Dominio 🤜🏻🤛🏻
* [realizar validaciones de datos en aplicaciones ASP.NET Core] (https://www.nuget.org/packages/FluentValidation.AspNetCore) FluentValidation.AspNetCore
* [permite convertir fácilmente HTML y CSS en archivos PDF] (https://www.nuget.org/packages/itext7.pdfhtml) itext7.pdfhtml
* [biblioteca fundamental para el desarrollo de aplicaciones .NET] (https://www.nuget.org/packages/Microsoft.EntityFrameworkCore/8.0.0-preview.7.23375.4) Microsoft.EntityFrameworkCore

## Dentro del proyecto Persistencia 🤸🏻‍♀️

* [biblioteca fundamental para el desarrollo de aplicaciones .NET] (https://www.nuget.org/packages/Microsoft.EntityFrameworkCore/8.0.0-preview.7.23375.4) Microsoft.EntityFrameworkCore
* [ integración de MySQL en aplicaciones .NET Core] (https://www.nuget.org/packages/Pomelo.EntityFrameworkCore.MySql) Pomelo.EntityFrameworkCore.MySql

## Estructura del Proyecto
Estas son las carpertas de configuracion las cuales vamos a utilizar para nuestros proyectos
 - 📂 En Dominio  
        Aqui se crean las tablas que representan la BD y van a estar ubicadas las carpetas de Entidades e Interfaces.

 - 📂 En Persistencia  
        Aqui se crea la instancia de conexion a la BD y van a estar ubicadas las carpetas de Data, Configuracion, Archivo context y Migraciones.

 - 📂 En Aplicacion  
        Aqui se crea la inyeccion de dependecia para la comunicacion con el WebApi y van a estar ubicadas las carpetas de Unidad de trabajo y Repositorios.
        
 - 📂 En WebApi  
        Aqui se crean clases encargadas de recibir peticiones de los clientes y van a estar ubicadas las carpetas de Controladores, helpers, Dtos, Profile, Contenedor de dependecias(program.cs) y Extenciones.

 - 📂 En Seguridad  
        Aqui se crean clases encargadas de la configuración de los archivos JWT(JSON Web Tokens) para la seguridad de nuestro proyecto.
