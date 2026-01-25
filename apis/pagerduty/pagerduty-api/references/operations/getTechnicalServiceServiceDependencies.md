# GET /service_dependencies/technical_services/{id}

**Resource:** [Service Dependencies](../resources/Service-Dependencies.md)
**Get technical service dependencies**
**Operation ID:** `getTechnicalServiceServiceDependencies`

Get all immediate dependencies of any technical service.
Technical services are also known as `services`.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#services)

Scoped OAuth requires: `services.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | An array of service relationships. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

