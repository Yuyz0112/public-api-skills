# GET /incidents/types/{type_id_or_name}

**Resource:** [Incident Types](../resources/Incident-Types.md)
**Get an Incident Type**
**Operation ID:** `getIncidentType`

Get detailed information about a single incident type. Accepts either an incident type id, or an incident type name.

Incident Types are a feature which will allow customers to categorize incidents, such as a security incident, a major incident, or a fraud incident.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#incident)

Scoped OAuth requires: `incident_types.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | The incident type requested. |
| 400 | (reference) |
| 401 | (reference) |
| 402 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

