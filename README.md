# Inversores teco

## Comandos de Arranque

Leer la documentación para crear una web desde cero .NET Core 2.2 en

https://dotnet.microsoft.com/learn/web/aspnet-hello-world-tutorial

Luego correr las siguientes lineas para crear la app virgen:

```bash 
dotnet new webApp -o inversores-net
cd inversores-net
dotnet run
```

* Modificar los archivos:
  * Index y su CS
  * Agregar la carpeta `Helpers` con sus archivos
  * Agregar las configuraciones del Azure en appsettings.json
* Incluir las bibliotecas de MS Identity y Graph con las siguientes líneas

```bash
dotnet add package Microsoft.Identity.Client
dotnet add package Microsoft.Graph
```

