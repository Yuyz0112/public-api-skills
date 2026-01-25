# GET /incidents/types/{type_id_or_name}/custom_fields/{field_id}

**Resource:** [Incident Types](../resources/Incident-Types.md)
**Get an Incident Type Custom Field**
**Operation ID:** `getIncidentTypeCustomField`

Get a custom field for an incident type.

Custom Fields (CF) are a feature which will allow customers to extend Incidents with their own custom data,
to provide additional context and support features such as customized filtering, search and analytics.
Custom Fields can be applied to different incident types.

Scoped OAuth requires: `custom_fields.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | The incident type custom field requested. |
| 400 | (reference) |
| 401 | (reference) |
| 402 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

