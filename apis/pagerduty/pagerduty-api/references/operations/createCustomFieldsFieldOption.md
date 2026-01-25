# POST /incidents/custom_fields/{field_id}/field_options

**Resource:** [Incident Custom Fields](../resources/Incident-Custom-Fields.md)
**Create a Field Option**
**Operation ID:** `createCustomFieldsFieldOption`
⚠️ **Deprecated**


<!-- theme: warning -->
> ### Deprecated
> This endpoint is deprecated and only works for fields on the Base Incident Type. \
> For more flexibility, we recommend using the Incident Types endpoint: \
> [/incidents/types/{type_id_or_name}/custom_fields/{field_id}/field_options](openapiv3.json/paths/~1incidents~1types~1{type_id_or_name}~1custom_fields~1{field_id}~1field_options/post)

Create a new Field Option for a Custom Field on the Base Incident Type. Field Options may only be created for Fields that have `field_options`. A Field may have no more than 10 enabled options.

Scoped OAuth requires: `custom_fields.write`


## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | The field option created. |
| 400 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

