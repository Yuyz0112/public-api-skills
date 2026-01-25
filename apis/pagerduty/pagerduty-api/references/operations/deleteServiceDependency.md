# POST /service_dependencies/disassociate

**Resource:** [Service Dependencies](../resources/Service-Dependencies.md)
**Disassociate service dependencies**
**Operation ID:** `deleteServiceDependency`

Disassociate dependencies between two services.

Business services model capabilities that span multiple technical services and that may be owned by several different teams.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#business-services)

Scoped OAuth requires: `services.write`


## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | An array of service relationships that were successfully disassociated. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

