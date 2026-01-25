# PATCH /zones/{zone_id}/api_gateway/operations/schema_validation

**Resource:** [API Shield Schema Validation 2.0](../resources/API-Shield-Schema-Validation-2-0.md)
**Update multiple operation-level schema validation settings**
**Operation ID:** `api-shield-schema-validation-update-multiple-operation-level-settings`
⚠️ **Deprecated**

Updates multiple operation-level schema validation settings on the zone

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [api-shield_old_operation_schema_validation_settings_multiple_request](../schemas/api-shield/api-shield-old-operation-schema-validation-settings-multiple-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update multiple operation-level schema validation settings response |
| 4XX | Update multiple operation-level schema validation settings response failure |

## Security

- **api_email**
- **api_key**
- **api_token**
