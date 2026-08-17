# Arquitectura inicial

## Capas

### Frontend
PWA responsive, mobile-first.

### Backend
API, autenticación, casos, equipos, permisos y estados.

### Geolocalización
Ubicación, recorridos, sectores, áreas y rutas.

### Datos
Usuarios, animales, casos, equipos, recorridos, pistas, lugares y eventos.

### IA
Clasificación, extracción, coincidencias y asistencia.

### Integraciones
Mapas, notificaciones, comunicación y fuentes externas.

## Principio de desacoplamiento

Usar adaptadores/interfaces para proveedores externos:

- MapProvider
- NotificationProvider
- AnimalSourceProvider
- AIProvider

El producto no debe quedar atado desde el comienzo a un proveedor específico.
