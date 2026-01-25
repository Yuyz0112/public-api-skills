# DELETE /services/{id}

**Resource:** [Services](../resources/Services.md)
**Delete a service**
**Operation ID:** `deleteService`

Delete an existing service.

Once the service is deleted, it will not be accessible from the web UI and new incidents won't be able to be created for this service.

A service may represent an application, component, or team you wish to open incidents against.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#services)

Scoped OAuth requires: `services.write`


## Responses

| Status | Description |
|--------|-------------|
| 204 | The service was deleted successfully. |
| 401 | (reference) |
| 403 | (reference) |

