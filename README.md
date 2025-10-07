# CarTracker

Aplicación web simple para registrar vehículos y controlar kilometrajes usando `localStorage`.

## Requisitos
- Navegador moderno con acceso a Internet (para cargar Tailwind y Font Awesome desde CDN).

## Cómo ejecutar
1. Abre la carpeta del proyecto `C:\Users\Inspiron\CascadeProjects\cartracker`.
2. Haz doble clic en `index.html` o ábrelo con tu navegador preferido.
3. Registra tu primer vehículo y comienza a actualizar el kilometraje.

## Datos y privacidad
- Los datos se guardan únicamente en tu navegador, en `localStorage` bajo las claves:
  - `carTrackerVehicles`
  - `carTrackerCurrentVehicle`
- Para borrar datos, usa Configuración → "Reiniciar aplicación".

## Notas
- La alerta de mantenimiento aparece cuando cruzas cada múltiplo de 5000 km respecto al mayor kilometraje registrado.
- Puedes gestionar múltiples vehículos desde la sección "Mis Vehículos".
