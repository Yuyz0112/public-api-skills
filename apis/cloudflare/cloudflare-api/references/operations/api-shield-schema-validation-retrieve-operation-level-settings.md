# GET /zones/{zone_id}/api_gateway/operations/{operation_id}/schema_validation

**Resource:** [API Shield Schema Validation 2.0](../resources/API-Shield-Schema-Validation-2-0.md)
**Retrieve operation-level schema validation settings**
**Operation ID:** `api-shield-schema-validation-retrieve-operation-level-settings`
⚠️ **Deprecated**

Retrieves operation-level schema validation settings on the zone

## Responses

| Status | Description |
|--------|-------------|
| 200 | Operation-level schema validation settings response |
| 4XX | Operation-level schema validation settings response |

**Success Response Schema:**

[api-shield_old_operation_schema_validation_settings](../schemas/api-shield/api-shield-old-operation-schema-validation-settings.md)

## Security

- **api_email**
- **api_key**
- **api_token**
