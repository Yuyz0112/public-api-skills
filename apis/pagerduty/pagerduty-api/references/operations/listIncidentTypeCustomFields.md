# GET /incidents/types/{type_id_or_name}/custom_fields

**Resource:** [Incident Types](../resources/Incident-Types.md)
**List Incident Type Custom Fields**
**Operation ID:** `listIncidentTypeCustomFields`

List the custom fields for an incident type.

Custom Fields (CF) are a feature which will allow customers to extend Incidents with their own custom data,
to provide additional context and support features such as customized filtering, search and analytics.
Custom Fields can be applied to different incident types.

Scoped OAuth requires: `custom_fields.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | The custom fields for the incident type requested. Passing in include[]=field_options will return the field options for the custom field. |
| 400 | (reference) |
| 401 | (reference) |
| 402 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

