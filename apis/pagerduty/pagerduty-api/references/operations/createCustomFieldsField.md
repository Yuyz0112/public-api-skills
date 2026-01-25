# POST /incidents/custom_fields

**Resource:** [Incident Custom Fields](../resources/Incident-Custom-Fields.md)
**Create a Field**
**Operation ID:** `createCustomFieldsField`
⚠️ **Deprecated**


<!-- theme: warning -->
> ### Deprecated
> This endpoint is deprecated and only works for fields on the Base Incident Type. \
> For more flexibility, we recommend using the Incident Types endpoint: \
> [/incidents/types/{type_id_or_name}/custom_fields](openapiv3.json/paths/~1incidents~1types~1{type_id_or_name}~1custom_fields/post)

Creates a new Custom Field on the Base Incident Type, along with the Field Options if provided. \
An account may have up to 10 Fields.

Scoped OAuth requires: `custom_fields.write`


## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | The field object created, along with the Field Options if provided. |
| 400 | (reference) |
| 403 | (reference) |
| 500 | (reference) |

