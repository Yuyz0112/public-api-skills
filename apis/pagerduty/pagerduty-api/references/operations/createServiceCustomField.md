# POST /services/custom_fields

**Resource:** [Service Custom Fields](../resources/Service-Custom-Fields.md)
**Create a Field**
**Operation ID:** `createServiceCustomField`

Creates a new Custom Field for Services, along with the Field Options if provided.

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

