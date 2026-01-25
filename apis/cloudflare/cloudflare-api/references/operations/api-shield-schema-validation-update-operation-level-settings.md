# PUT /zones/{zone_id}/api_gateway/operations/{operation_id}/schema_validation

**Resource:** [API Shield Schema Validation 2.0](../resources/API-Shield-Schema-Validation-2-0.md)
**Update operation-level schema validation settings**
**Operation ID:** `api-shield-schema-validation-update-operation-level-settings`
⚠️ **Deprecated**

Updates operation-level schema validation settings on the zone

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [api-shield_old_operation_schema_validation_settings_modify_request](../schemas/api-shield/api-shield-old-operation-schema-validation-settings-modify-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update operation-level schema validation settings response |
| 4XX | Update operation-level schema validation settings response failure |

**Success Response Schema:**

[api-shield_old_operation_schema_validation_settings](../schemas/api-shield/api-shield-old-operation-schema-validation-settings.md)

## Security

- **api_email**
- **api_key**
- **api_token**
