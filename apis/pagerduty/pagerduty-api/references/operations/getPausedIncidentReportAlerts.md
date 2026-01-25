# GET /paused_incident_reports/alerts

**Resource:** [Paused Incident Reports](../resources/Paused-Incident-Reports.md)
**Get Paused Incident Reporting on Alerts**
**Operation ID:** `getPausedIncidentReportAlerts`

Returns the 5 most recent alerts that were triggered after being paused and the 5 most recent alerts that were resolved after being paused for a given reporting period (maximum 6 months lookback period).  Note: This feature is currently available as part of the Event Intelligence package or Digital Operations plan only.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#paused-incident-reports)

Scoped OAuth requires: `incidents.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | Paused Incident Reporting on Alerts for the Account or scoped to a Service. |
| 400 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |
| 500 | (reference) |

