# POST /services

**Resource:** [Services](../resources/Services.md)
**Create a service**
**Operation ID:** `createService`

Create a new service.

If `status` is included in the request, it must have a value of `active` when creating a new service. If a different status is required, make a second request to update the service.

A service may represent an application, component, or team you wish to open incidents against.

There is a limit of 25,000 services per account. If the limit is reached, the API will respond with an error. There is also a limit of 100,000 open Incidents per Service. If the limit is reached and `auto_resolve_timeout` is disabled (set to 0 or null), the `auto_resolve_timeout` property will automatically be set to  84600 (1 day).

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#services)

Scoped OAuth requires: `services.write`


## Request Body

The service to be created

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | The service that was created |
| 400 | (reference) |
| 401 | (reference) |
| 402 | (reference) |
| 403 | (reference) |

