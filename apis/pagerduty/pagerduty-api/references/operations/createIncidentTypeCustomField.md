# POST /incidents/types/{type_id_or_name}/custom_fields

**Resource:** [Incident Types](../resources/Incident-Types.md)
**Create a Custom Field for an Incident Type**
**Operation ID:** `createIncidentTypeCustomField`

Create a Custom Field for an Incident Type

Custom Fields (CF) are a feature which will allow customers to extend Incidents with their own custom data,
to provide additional context and support features such as customized filtering, search and analytics.
Custom Fields can be applied to different incident types.

Scoped OAuth requires: `custom_fields.write`


## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | The custom field object created. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

