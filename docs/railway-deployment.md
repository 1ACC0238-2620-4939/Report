# Deployment Railway de Trakto Route

Verificado el 04/10/2026 (America/Lima). Proyecto: `trakto-route-tb1`, ID `02da3efa-2273-4f25-9ac0-364c862c0648`.

| Servicio | Revisión | Deployment | Verificación |
|---|---|---|---|
| landing-page | `96bead9` | `f32c0478-8c83-4034-a050-e2bf79a1b799` | SUCCESS / RUNNING; raíz HTTP 200; `/health` devuelve `ok` |
| backend | `915662b` | `784ca149-7335-4163-b55d-b9ad7a4820b7` | SUCCESS / RUNNING; OpenAPI HTTP 200; conexión MySQL y escritura/lectura verificadas |
| MySQL | imagen `mysql:9` | `84c86afa-8e5c-41e3-8ce9-f10be1db54fb` | SUCCESS / RUNNING; volumen en `/var/lib/mysql` |

- Frontend: https://landing-page-production-9db1.up.railway.app/
- API: https://backend-production-8735.up.railway.app/
- OpenAPI: https://backend-production-8735.up.railway.app/v3/api-docs
- Swagger: https://backend-production-8735.up.railway.app/swagger-ui.html
- Dashboard: https://railway.com/project/02da3efa-2273-4f25-9ac0-364c862c0648

Las credenciales usan referencias a variables del servicio MySQL y no están incluidas en este documento. El backend registró conexión HikariCP y creación de tablas. La prueba técnica creó el vehículo `TBX406`, identificador `f12c04e5-9994-4214-adea-e2152ebc46ed`, con POST HTTP 201; un GET posterior devolvió HTTP 200 y los mismos datos. Este registro es un dato de prueba.

Esta evidencia valida el deployment de la landing y la persistencia del backend. La integración Android–API y la aceptación completa del producto permanecen pendientes.
