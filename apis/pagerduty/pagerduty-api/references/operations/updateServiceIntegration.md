# PUT /services/{id}/integrations/{integration_id}

**Resource:** [Services](../resources/Services.md)
**Update an existing integration**
**Operation ID:** `updateServiceIntegration`

Update an integration belonging to a Service.

A service may represent an application, component, or team you wish to open incidents against.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#services)

Scoped OAuth requires: `services.write`


## Request Body

The integration to be updated

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | The integration that was updated. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

