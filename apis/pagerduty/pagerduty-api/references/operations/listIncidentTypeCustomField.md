# GET /incidents/types/{type_id_or_name}/custom_fields/{field_id}/field_options

**Resource:** [Incident Types](../resources/Incident-Types.md)
**List Field Options on a Custom Field**
**Operation ID:** `listIncidentTypeCustomField`

List field options for a custom field.

Custom Fields (CF) are a feature which will allow customers to extend Incidents with their own custom data,
to provide additional context and support features such as customized filtering, search and analytics.
Custom Fields can be applied to different incident types.

Scoped OAuth requires: `custom_fields.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | The field option for the custom field requested. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

