# GET /incidents/custom_fields/{field_id}

**Resource:** [Incident Custom Fields](../resources/Incident-Custom-Fields.md)
**Get a Field**
**Operation ID:** `getCustomFieldsField`
⚠️ **Deprecated**


<!-- theme: warning -->
> ### Deprecated
> This endpoint is deprecated and only works for fields on the Base Incident Type. \
> For more flexibility, we recommend using the Incident Types endpoint: \
> [/incidents/types/{type_id_or_name}/custom_fields/{field_id}](openapiv3.json/paths/~1incidents~1types~1{type_id_or_name}~1custom_fields~1{field_id}/get)

Show detailed information about a Custom Field on the Base Incident Type.

Scoped OAuth requires: `custom_fields.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | The field requested. |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

