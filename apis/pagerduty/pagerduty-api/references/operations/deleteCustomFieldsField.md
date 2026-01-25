# DELETE /incidents/custom_fields/{field_id}

**Resource:** [Incident Custom Fields](../resources/Incident-Custom-Fields.md)
**Delete a Field**
**Operation ID:** `deleteCustomFieldsField`
⚠️ **Deprecated**


<!-- theme: warning -->
> ### Deprecated
> This endpoint is deprecated and only works for fields on the Base Incident Type. \
> For more flexibility, we recommend using the Incident Types endpoint: \
> [/incidents/types/{type_id_or_name}/custom_fields/{field_id}](openapiv3.json/paths/~1incidents~1types~1{type_id_or_name}~1custom_fields~1{field_id}/delete)

Delete a Custom Field from the Base Incident Type.

Scoped OAuth requires: `custom_fields.write`


## Responses

| Status | Description |
|--------|-------------|
| 204 | The field was deleted successfully. |
| 400 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

