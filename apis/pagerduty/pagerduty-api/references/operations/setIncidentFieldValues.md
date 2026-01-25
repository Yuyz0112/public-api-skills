# PUT /incidents/{id}/custom_fields/values

**Resource:** [Incidents](../resources/Incidents.md)
**Update Custom Field Values**
**Operation ID:** `setIncidentFieldValues`

Set custom field values for an incident.

Scoped OAuth requires: `incidents.write`


## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Custom field values were updated. |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

