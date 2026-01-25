# POST /services/{id}/integrations

**Resource:** [Services](../resources/Services.md)
**Create a new integration**
**Operation ID:** `createServiceIntegration`

Create a new integration belonging to a Service.

A service may represent an application, component, or team you wish to open incidents against.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#services)

Scoped OAuth requires: `services.write`


## Request Body

The integration to be created

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | The integration that was created. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 429 | (reference) |

