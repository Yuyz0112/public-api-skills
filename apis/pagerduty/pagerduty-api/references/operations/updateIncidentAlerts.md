# PUT /incidents/{id}/alerts

**Resource:** [Incidents](../resources/Incidents.md)
**Manage alerts**
**Operation ID:** `updateIncidentAlerts`

Resolve multiple alerts or associate them with different incidents.

An incident represents a problem or an issue that needs to be addressed and resolved. An alert represents a digital signal that was emitted to PagerDuty by the monitoring systems that detected or identified the issue.

A maximum of 250 alerts may be updated at a time. If more than this number of alerts are given, the API will respond with status 413 (Request Entity Too Large).

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#incidents)

Scoped OAuth requires: `incidents.write`


## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | All of the updates succeeded. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 413 | (reference) |
| 429 | (reference) |

