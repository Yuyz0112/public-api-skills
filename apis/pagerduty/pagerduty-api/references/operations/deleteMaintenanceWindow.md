# DELETE /maintenance_windows/{id}

**Resource:** [Maintenance Windows](../resources/Maintenance-Windows.md)
**Delete or end a maintenance window**
**Operation ID:** `deleteMaintenanceWindow`

Delete an existing maintenance window if it's in the future, or end it if it's currently on-going. If the maintenance window has already ended it cannot be deleted.

A Maintenance Window is used to temporarily disable one or more Services for a set period of time.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#maintenance-windows)

Scoped OAuth requires: `services.write`


## Responses

| Status | Description |
|--------|-------------|
| 204 | The maintenance window was deleted successfully. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 405 | The maintenance window can't be deleted because it has already ended. |
| 429 | (reference) |

