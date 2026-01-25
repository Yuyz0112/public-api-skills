# GET /services

**Resource:** [Services](../resources/Services.md)
**List services**
**Operation ID:** `listServices`

List existing Services.

A service may represent an application, component, or team you wish to open incidents against.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#services)

Scoped OAuth requires: `services.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | A paginated array of services. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |

