# DELETE /incidents/types/{type_id_or_name}/custom_fields/{field_id}/field_options/{field_option_id}

**Resource:** [Incident Types](../resources/Incident-Types.md)
**Delete a Field Option for a Custom Field**
**Operation ID:** `deleteIncidentTypeCustomFieldFieldOption`

Delete a field option for a custom field.

Custom Fields (CF) are a feature which will allow customers to extend Incidents with their own custom data,
to provide additional context and support features such as customized filtering, search and analytics.
Custom Fields can be applied to different incident types.

Scoped OAuth requires: `custom_fields.write`


## Responses

| Status | Description |
|--------|-------------|
| 204 | The field option was deleted successfully. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

