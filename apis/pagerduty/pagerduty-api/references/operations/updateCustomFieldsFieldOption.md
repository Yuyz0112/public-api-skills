# PUT /incidents/custom_fields/{field_id}/field_options/{field_option_id}

**Resource:** [Incident Custom Fields](../resources/Incident-Custom-Fields.md)
**Update a Field Option**
**Operation ID:** `updateCustomFieldsFieldOption`
⚠️ **Deprecated**


<!-- theme: warning -->
> ### Deprecated
> This endpoint is deprecated and only works for fields on the Base Incident Type. \
> For more flexibility, we recommend using the Incident Types endpoint: \
> [/incidents/types/{type_id_or_name}/custom_fields/{field_id}/field_options/{field_option_id}](openapiv3.json/paths/~1incidents~1types~1{type_id_or_name}~1custom_fields~1{field_id}~1field_options~1{field_option_id}/put)

Update a Field Option for a Custom Field on the Base Incident Type.

Scoped OAuth requires: `custom_fields.write`


## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | The field option object updated. |
| 400 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

