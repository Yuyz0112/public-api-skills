# GET /incidents/custom_fields

**Resource:** [Incident Custom Fields](../resources/Incident-Custom-Fields.md)
**List Fields**
**Operation ID:** `listCustomFieldsFields`
⚠️ **Deprecated**


<!-- theme: warning -->
> ### Deprecated
> This endpoint is deprecated and only works for fields on the Base Incident Type. \
> For more flexibility, we recommend using the Incident Types endpoint: \
> [/incidents/types/{type_id_or_name}/custom_fields](openapiv3.json/paths/~1incidents~1types~1{type_id_or_name}~1custom_fields/get)

List Custom Fields on the Base Incident Type.

Scoped OAuth requires: `custom_fields.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | A list of fields. |
| 400 | (reference) |
| 500 | (reference) |

