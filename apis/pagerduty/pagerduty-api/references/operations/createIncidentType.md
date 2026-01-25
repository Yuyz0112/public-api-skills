# POST /incidents/types

**Resource:** [Incident Types](../resources/Incident-Types.md)
**Create an Incident Type**
**Operation ID:** `createIncidentType`

Create a new incident type.

Incident Types are a feature which will allow customers to categorize incidents, such as a security incident, a major incident, or a fraud incident.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#incidentType)

Scoped OAuth requires: `incident_types.write`


## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | The incident type object created. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

