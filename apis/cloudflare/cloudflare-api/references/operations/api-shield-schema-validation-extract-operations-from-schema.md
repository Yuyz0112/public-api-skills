# GET /zones/{zone_id}/api_gateway/user_schemas/{schema_id}/operations

**Resource:** [API Shield Schema Validation 2.0](../resources/API-Shield-Schema-Validation-2-0.md)
**Retrieve all operations from a schema.**
**Operation ID:** `api-shield-schema-validation-extract-operations-from-schema`
⚠️ **Deprecated**

Retrieves all operations from the schema. Operations that already exist in API Shield Endpoint Management will be returned as full operations.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `operation_status` | query | enum: new, existing | No | Filter results by whether operations exist in API Shield Endpoint Management or not. `new` will just return operations from the schema that do not exist in API Shield Endpoint Management. `existing` will just return operations from the schema that already exist in API Shield Endpoint Management. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Retrieve all operations from a schema response |
| 4XX | Retrieve all operations from a schema response failure |

## Security

- **api_email**
- **api_key**
- **api_token**
