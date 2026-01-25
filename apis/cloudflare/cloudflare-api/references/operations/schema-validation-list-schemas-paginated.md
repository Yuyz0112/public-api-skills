# GET /zones/{zone_id}/schema_validation/schemas

**Resource:** [Schema Validation](../resources/Schema-Validation.md)
**List all uploaded schemas**
**Operation ID:** `schema-validation-list-schemas-paginated`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `validation_enabled` | query | boolean | No | Filter for enabled schemas |

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |
| 4XX | (reference) |

## Security

- **api_token**
- **api_email**
- **api_key**
