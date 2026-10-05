# Acreditación técnica del backend — 05/10/2026

La comprobación se realizó contra Railway, sin cambiar el producto desplegado. Los cinco escenarios ejecutables volvieron a pasar: vehículos, ciclo del viaje, respuesta 404, perfiles y conductores. Las solicitudes y respuestas completas constan en `assets/evidence/backend-acceptance-now.json`. Los registros creados tienen datos técnicos de prueba.

OpenAPI publicado contiene **37 operaciones**. El Product Backlog del informe contiene **41 historias**. El enunciado exige backend desplegado al 70%, pero no fija una fórmula de ponderación. Si se adoptara un conteo uniforme por historias, harían falta al menos **29 de 41** con todos sus criterios backend satisfechos. Esta equivalencia es una interpretación de medición, no una ponderación dada por el docente.

Los cinco escenarios prueban partes de diez historias referenciadas en el archivo Gherkin. No prueban todos sus criterios positivos, negativos y permisos; no se convierten en diez historias completas ni en un porcentaje de aceptación.

La autenticación (US01/US02) y gestión de incidencias (US11/US31–US36) no cuentan con contratos desplegados. La API actual cubre perfiles, viajes, flota y seguimiento. No se certifica un 70% del alcance total a partir de disponibilidad, número de endpoints o pruebas parciales.

| Historia | Funcionalidad | Evidencia de esta ejecución |
|---|---|---|
| US01 | Registrar cuenta | No cubierta por estos cinco escenarios |
| US02 | Iniciar sesión | No cubierta por estos cinco escenarios |
| US03 | Consultar perfil | Escenario API asociado PASS; criterios completos no acreditados |
| US04 | Actualizar perfil | Escenario API asociado PASS; criterios completos no acreditados |
| US05 | Consultar viajes | No cubierta por estos cinco escenarios |
| US06 | Consultar detalle de viaje | Escenario API asociado PASS; criterios completos no acreditados |
| US07 | Consultar estado del viaje | No cubierta por estos cinco escenarios |
| US08 | Consultar ruta asignada | No cubierta por estos cinco escenarios |
| US09 | Consultar información del conductor | No cubierta por estos cinco escenarios |
| US10 | Consultar información del vehículo | No cubierta por estos cinco escenarios |
| US11 | Registrar incidencia | No cubierta por estos cinco escenarios |
| US12 | Consultar eventos e incidencias del viaje | No cubierta por estos cinco escenarios |
| US13 | Consultar historial de viajes | No cubierta por estos cinco escenarios |
| US14 | Consultar historial del conductor | No cubierta por estos cinco escenarios |
| US15 | Consultar historial del vehículo | No cubierta por estos cinco escenarios |
| US16 | Filtrar historial de viajes | No cubierta por estos cinco escenarios |
| US17 | Programar viaje | Escenario API asociado PASS; criterios completos no acreditados |
| US18 | Asignar ruta a un viaje | No cubierta por estos cinco escenarios |
| US19 | Actualizar estado del viaje | Escenario API asociado PASS; criterios completos no acreditados |
| US20 | Registrar parada | No cubierta por estos cinco escenarios |
| US21 | Registrar descanso | No cubierta por estos cinco escenarios |
| US22 | Finalizar viaje | Escenario API asociado PASS; criterios completos no acreditados |
| US23 | Registrar vehículo | Escenario API asociado PASS; criterios completos no acreditados |
| US24 | Actualizar información del vehículo | Escenario API asociado PASS; criterios completos no acreditados |
| US25 | Registrar conductor | Escenario API asociado PASS; criterios completos no acreditados |
| US26 | Actualizar información del conductor | Escenario API asociado PASS; criterios completos no acreditados |
| US27 | Asignar vehículo a un viaje | No cubierta por estos cinco escenarios |
| US28 | Asignar conductor a un viaje | No cubierta por estos cinco escenarios |
| US29 | Consultar disponibilidad de vehículos | No cubierta por estos cinco escenarios |
| US30 | Consultar disponibilidad de conductores | No cubierta por estos cinco escenarios |
| US31 | Registrar retraso | No cubierta por estos cinco escenarios |
| US32 | Registrar problema | No cubierta por estos cinco escenarios |
| US33 | Registrar accidente | No cubierta por estos cinco escenarios |
| US34 | Actualizar estado de incidencia | No cubierta por estos cinco escenarios |
| US35 | Consultar detalle de incidencia | No cubierta por estos cinco escenarios |
| US36 | Consultar historial de incidencias | No cubierta por estos cinco escenarios |
| US37 | Revisar desempeño de una operación | No cubierta por estos cinco escenarios |
| US38 | Consultar viajes por conductor | No cubierta por estos cinco escenarios |
| US39 | Consultar viajes por vehículo | No cubierta por estos cinco escenarios |
| US40 | Consultar progreso de un envío | No cubierta por estos cinco escenarios |
| US41 | Consultar eventos relevantes de un envío | No cubierta por estos cinco escenarios |

## Contratos publicados

| Método | Ruta |
|---|---|
| GET | `/api/v1/vehicles` |
| POST | `/api/v1/vehicles` |
| GET | `/api/v1/trips` |
| POST | `/api/v1/trips` |
| POST | `/api/v1/trackings` |
| POST | `/api/v1/trackings/{trackingId}/positions` |
| GET | `/api/v1/profiles` |
| POST | `/api/v1/profiles` |
| GET | `/api/v1/drivers` |
| POST | `/api/v1/drivers` |
| PATCH | `/api/v1/vehicles/{vehicleId}/plate-number` |
| PATCH | `/api/v1/vehicles/{vehicleId}/deactivate` |
| PATCH | `/api/v1/vehicles/{vehicleId}/capacity` |
| PATCH | `/api/v1/vehicles/{vehicleId}/activate` |
| PATCH | `/api/v1/trips/{tripId}/start` |
| PATCH | `/api/v1/trips/{tripId}/complete` |
| PATCH | `/api/v1/trips/{tripId}/cancel` |
| PATCH | `/api/v1/trackings/{trackingId}/stops/{stopId}/reason` |
| PATCH | `/api/v1/trackings/{trackingId}/finish` |
| PATCH | `/api/v1/profiles/{profileId}/full-name` |
| PATCH | `/api/v1/drivers/{driverId}/license-number` |
| PATCH | `/api/v1/drivers/{driverId}/deactivate` |
| PATCH | `/api/v1/drivers/{driverId}/activate` |
| GET | `/api/v1/vehicles/{vehicleId}` |
| GET | `/api/v1/vehicles/status/{status}` |
| GET | `/api/v1/trips/{tripId}` |
| GET | `/api/v1/trips/status/{status}` |
| GET | `/api/v1/trackings/{trackingId}` |
| GET | `/api/v1/trackings/trips/{tripId}` |
| GET | `/api/v1/trackings/trips/{tripId}/stops` |
| GET | `/api/v1/trackings/trips/{tripId}/stops/{stopId}` |
| GET | `/api/v1/trackings/trips/{tripId}/last-position` |
| GET | `/api/v1/profiles/{profileId}` |
| GET | `/api/v1/profiles/users/{userReferenceId}` |
| GET | `/api/v1/drivers/{driverId}` |
| GET | `/api/v1/drivers/status/{status}` |
| GET | `/api/v1/drivers/profile/{profileId}` |
