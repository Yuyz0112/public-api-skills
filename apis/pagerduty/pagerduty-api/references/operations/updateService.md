# PUT /services/{id}

**Resource:** [Services](../resources/Services.md)
**Update a service**
**Operation ID:** `updateService`

Update an existing service.

A service may represent an application, component, or team you wish to open incidents against.

There is a limit of 100,000 open Incidents per Service. If the limit is reached and you disable `auto_resolve_timeout` (set to 0 or null), the API will respond with an error.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#services)

Scoped OAuth requires: `services.write`


## Request Body

The service to be updated.

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | The service that was updated. |
| 401 | (reference) |
| 402 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

