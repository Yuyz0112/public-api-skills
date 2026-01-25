# GET /incidents/types

**Resource:** [Incident Types](../resources/Incident-Types.md)
**List incident types**
**Operation ID:** `listIncidentTypes`

List the available incident types

Incident Types are a feature which will allow customers to categorize incidents, such as a security incident, a major incident, or a fraud incident.
These can be filtered by enabled or disabled types.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#incidentType)

Scoped OAuth requires: `incident_types.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | An array of all types for the account. The default incident type will automatically return on this list. |
| 400 | (reference) |
| 401 | (reference) |
| 402 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

