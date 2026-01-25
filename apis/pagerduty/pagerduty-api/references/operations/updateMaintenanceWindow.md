# PUT /maintenance_windows/{id}

**Resource:** [Maintenance Windows](../resources/Maintenance-Windows.md)
**Update a maintenance window**
**Operation ID:** `updateMaintenanceWindow`

Update an existing maintenance window.

A Maintenance Window is used to temporarily disable one or more Services for a set period of time.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#maintenance-windows)

Scoped OAuth requires: `services.write`


## Request Body

The maintenance window to be updated.

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | The maintenance window that was updated. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

