# Proyecto de Manejo de Presupuesto

## Descripción del Proyecto
Este proyecto tiene como objetivo desarrollar una aplicación web para el manejo de presupuestos personales. La aplicación permitirá a los usuarios registrar sus ingresos y gastos, y generar reportes financieros para tener un mejor control de sus finanzas personales.

## Características Principales
- Registro de ingresos y gastos
- Visualización de reportes financieros
- Uso de una base de datos

## Tecnologías Utilizadas
- **Framework**: ASP.NET Core
- **Lenguaje de Programación**: C#
- **Base de Datos**: SQL Server.
- **Frontend**: HTML, CSS y JavaScript
- **Herramientas de Desarrollo**: Visual Studio, Git

## Requisitos Previos
Para ejecutar este proyecto en tu máquina local, necesitarás tener instalado:

- [.NET Core SDK](https://dotnet.microsoft.com/download)
- [Visual Studio](https://visualstudio.microsoft.com/vs/) o [Visual Studio Code](https://code.visualstudio.com/)
- Un gestor de base de datos (SQL Server, MySQL, etc.)
- Git

## Paquetes NuGet Utilizados
- **Microsoft.Data.SqlClient**: Proveedor de cliente SQL para conectarse y trabajar con bases de datos SQL Server.
- **Dapper**: Micro ORM para trabajar con bases de datos de manera más eficiente y con mejor rendimiento.
- **AutoMapper.Extensions.Microsoft.DependencyInjection**: Integración de AutoMapper con el contenedor de inyección de dependencias de Microsoft, facilitando la configuración y uso de AutoMapper en aplicaciones ASP.NET Core.
- **ClosedXML**: Biblioteca para trabajar con archivos Excel (XLSX) de manera fácil y eficiente.

## Restaurar la Base de Datos
Para restaurar la base de datos desde el script SQL:

1. Abre SQL Server Management Studio (SSMS).
2. Conéctate a tu instancia de SQL Server.
3. Abre un nuevo query.
4. Copia y pega el contenido del archivo `nombre-archivo.sql`.
5. Ejecuta el script para crear la base de datos y poblarla con los datos.
