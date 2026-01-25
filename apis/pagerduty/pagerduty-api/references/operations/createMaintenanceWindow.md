# POST /maintenance_windows

**Resource:** [Maintenance Windows](../resources/Maintenance-Windows.md)
**Create a maintenance window**
**Operation ID:** `createMaintenanceWindow`

Create a new maintenance window for the specified services. No new incidents will be created for a service that is in maintenance.

A Maintenance Window is used to temporarily disable one or more Services for a set period of time.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#maintenance-windows)

Scoped OAuth requires: `services.write`


## Request Body

The maintenance window object.

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | The maintenance window that was created. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 429 | (reference) |

