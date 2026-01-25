# GET /maintenance_windows/{id}

**Resource:** [Maintenance Windows](../resources/Maintenance-Windows.md)
**Get a maintenance window**
**Operation ID:** `getMaintenanceWindow`

Get an existing maintenance window.

A Maintenance Window is used to temporarily disable one or more Services for a set period of time.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#maintenance-windows)

Scoped OAuth requires: `services.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | The maintenance window that was updated. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

