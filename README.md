
# Sales Date Prediction

Este proyecto es una solución completa para la gestión de órdenes y predicción de próximas compras por cliente, desarrollada como parte de una prueba técnica.

##  Arquitectura del Proyecto

- **Frontend**: Angular 17+ SPA
- **Backend**: ASP.NET Core Web API
- **Base de Datos**: SQL Server
- **Visualización**: D3.js con Vanilla JavaScript

##  Instrucciones para Build y Ejecución

### Backend (.NET Core)
1. Abrir la solución en Visual Studio.
2. Configurar la cadena de conexión a SQL Server en `appsettings.json`.
3. Ejecutar el proyecto para levantar la API.

### Frontend (Angular)
1. Navegar al directorio del frontend.
2. Ejecutar `npm install` para instalar dependencias.
3. Ejecutar `ng serve` para iniciar la aplicación.

### Base de Datos
1. Tener una instancia de SQL Server activa.
2. Ejecutar el script `DBSetup.sql` para crear la base de datos `StoreSample`.

##  Pruebas Unitarias

- Se implementaron pruebas unitarias en el backend utilizando **Microsoft Unit Testing Framework**.
- Las pruebas cubren servicios de negocio y validaciones.
- Para ejecutarlas:
  - Abrir Test Explorer en Visual Studio.
  - Ejecutar todas las pruebas.

## Estructura del Repositorio

```
/SalesDatePrediction
├── backend/                  # Proyecto ASP.NET Core
├── frontend/                 # Proyecto Angular
├── d3-visualization/         # Visualización con D3.js
├── DBSetup.sql               # Script de base de datos
├── README.md                 # Este archivo
```

##  Consideraciones

- Se aplicaron principios SOLID y buenas prácticas de desarrollo.
- Se validan formularios en Angular con ReactiveForms.
- El backend valida modelos con anotaciones y `ModelState`.
- Se implementó manejo de errores y logging.

