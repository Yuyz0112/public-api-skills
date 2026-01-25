# GET /services/{id}/integrations/{integration_id}

**Resource:** [Services](../resources/Services.md)
**View an integration**
**Operation ID:** `getServiceIntegration`

Get details about an integration belonging to a service.

A service may represent an application, component, or team you wish to open incidents against.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#services)

Scoped OAuth requires: `services.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | The integration that was requested. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

