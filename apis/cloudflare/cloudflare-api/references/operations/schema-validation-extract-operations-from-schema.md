# GET /zones/{zone_id}/schema_validation/schemas/{schema_id}/operations

**Resource:** [Schema Validation](../resources/Schema-Validation.md)
**Retrieve all operations from the schema.**
**Operation ID:** `schema-validation-extract-operations-from-schema`

Retrieves all operations from the schema. Operations that already exist in API Shield Endpoint Management will be returned as full operations.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `operation_status` | query | enum: new, existing | No | Filter results by whether operations exist in Web Asset Management or not. `new` will just return operations from the schema that do not exist otherwise. `existing` will just return operations from the schema that already exist. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |
| 4XX | (reference) |

## Security

- **api_token**
- **api_email**
- **api_key**
