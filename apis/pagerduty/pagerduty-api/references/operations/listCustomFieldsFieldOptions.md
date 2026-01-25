# GET /incidents/custom_fields/{field_id}/field_options

**Resource:** [Incident Custom Fields](../resources/Incident-Custom-Fields.md)
**List Field Options**
**Operation ID:** `listCustomFieldsFieldOptions`
⚠️ **Deprecated**


<!-- theme: warning -->
> ### Deprecated
> This endpoint is deprecated and only works for fields on the Base Incident Type. \
> For more flexibility, we recommend using the Incident Types endpoint: \
> [/incidents/types/{type_id_or_name}/custom_fields/{field_id}/field_options](openapiv3.json/paths/~1incidents~1types~1{type_id_or_name}~1custom_fields~1{field_id}~1field_options/get)

List all enabled Field Options for a Custom Field on the Base Incident Type.

Scoped OAuth requires: `custom_fields.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | A list of field options. |
| 404 | (reference) |
| 500 | (reference) |

