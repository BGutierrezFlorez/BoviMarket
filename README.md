# BoviMarket

Plataforma para la compra y venta de ganado bovino.

## Frontend React

```powershell
cd frontend-react
npm ci
npm run dev
```

Validaciones disponibles:

```powershell
npm run lint
npm run build
```

## Backend Web API

Abre `backend/BoviMarket.sln` en Visual Studio con soporte para ASP.NET Web Application y .NET Framework 4.7.2, y ejecuta el proyecto con IIS Express. La API conserva la base `/api` y el puerto local ya configurado.

La conexión y los scripts SQL existentes mantienen el nombre de base de datos `CowShop`. No ejecutes scripts SQL de instalación o reconstrucción como parte del cambio de marca.

## Sitio HTML existente

El sitio HTML principal usa `index.html`. Para las funciones que llaman a la API, sirve el sitio por HTTP y ejecuta también el backend.