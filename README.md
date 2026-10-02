# Práctica 1 - Uso de POSTMAN (PayPal Subscriptions API)

**Estudiante:** Manuel William Villa Quishpe
**Materia:** Patrones de Diseño de APIs
**Docente:** Ing. Patsy Malena Prieto, MSc.

## Descripción
Práctica de laboratorio para probar los métodos HTTP (GET, POST, PUT/PATCH, DELETE) usando Postman con la API de Suscripciones de PayPal en entorno Sandbox.

## Archivos
- `create_plan.json`: Body para crear un plan (POST).
- `update_pricing.json`: Body para actualizar precios (POST).
- `patch_plan.json`: Body para actualizar un plan (PATCH).
- `get_response.json`: Respuesta del listado de planes (GET).

## Métodos probados
| Método | Endpoint | Código |
|--------|----------|--------|
| GET | /v1/billing/plans | 200 OK |
| POST | /v1/billing/plans | 201 Created |
| PATCH | /v1/billing/plans/{id} | 204 No Content |
| POST | /v1/billing/plans/{id}/deactivate | 204 No Content |
