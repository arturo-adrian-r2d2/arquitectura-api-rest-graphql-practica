# Diseño de API REST

## ¿Qué es REST?
REST (Representational State Transfer) es un estilo arquitectónico diseñado para
sistemas distribuidos que utiliza el protocolo HTTP como medio de comunicación.

## Principios clave
- Stateless: el servidor no mantiene estado de sesión.
- Cacheable: las respuestas pueden almacenarse temporalmente.
- Interfaz uniforme: uso consistente de recursos y verbos HTTP.

## Ejemplo de endpoints
- GET /api/v1/productos
- GET /api/v1/productos/{id}
- POST /api/v1/ordenes
- PATCH /api/v1/ordenes/{id}

## Ventajas
- Simplicidad
- Fácil integración con clientes
- Soporte nativo de cache HTTP

## Limitaciones
- Over-fetching de datos
- Múltiples peticiones para recursos relacionados