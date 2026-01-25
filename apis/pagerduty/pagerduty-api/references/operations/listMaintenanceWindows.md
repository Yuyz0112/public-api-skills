# GET /maintenance_windows

**Resource:** [Maintenance Windows](../resources/Maintenance-Windows.md)
**List maintenance windows**
**Operation ID:** `listMaintenanceWindows`

List existing maintenance windows, optionally filtered by service and/or team, or whether they are from the past, present or future.

A Maintenance Window is used to temporarily disable one or more Services for a set period of time.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#maintenance-windows)

Scoped OAuth requires: `services.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | A paginated array of maintenance windows. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 429 | (reference) |

