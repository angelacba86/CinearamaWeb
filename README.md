# CineramaWeb

Sistema web para la gestión y reserva de boletos de cine desarrollado en **ASP.NET Core** (.NET 10).

## 🚀 Tecnologías utilizadas

- **Plataforma:** .NET 10 (ASP.NET Core MVC)
- **Acceso a datos:** Dapper & Microsoft.Data.SqlClient
- **Generación de boletos:** QuestPDF
- **Frontend:** Razor Views, HTML5, CSS3, JavaScript, Bootstrap

## 📂 Estructura del Proyecto

- `Controllers/`: Controladores MVC encargados de la lógica de navegación y operaciones.
- `Models/`: Entidades y modelos de datos.
- `Repositories/`: Capa de persistencia y consultas mediante Dapper.
- `Services/`: Lógica de negocio y servicios auxiliares (generación de PDFs, etc.).
- `Views/`: Vistas Razor para la interfaz de usuario.
- `wwwroot/`: Recursos estáticos (estilos, scripts, imágenes, boletos generados).

## ⚙️ Configuración y Ejecución

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/angelacba86/CinearamaWeb.git
   ```
2. Configurar la cadena de conexión a la base de datos en `appsettings.json`.
3. Restaurar dependencias y ejecutar:
   ```bash
   dotnet restore
   dotnet run
   ```
