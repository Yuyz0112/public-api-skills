# POST /services/custom_fields/{field_id}/field_options

**Resource:** [Service Custom Fields](../resources/Service-Custom-Fields.md)
**Create a Field Option**
**Operation ID:** `createServiceCustomFieldOption`

Create a new option for the given field.

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

