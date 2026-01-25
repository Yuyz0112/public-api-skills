# PUT /zones/{zone_id}/api_gateway/settings/schema_validation

**Resource:** [API Shield Schema Validation 2.0](../resources/API-Shield-Schema-Validation-2-0.md)
**Update zone level schema validation settings**
**Operation ID:** `api-shield-schema-validation-update-zone-level-settings`
⚠️ **Deprecated**

Updates zone level schema validation settings on the zone

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [api-shield_old_zone_schema_validation_settings_put](../schemas/api-shield/api-shield-old-zone-schema-validation-settings-put.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update zone level schema validation settings response |
| 4XX | Update zone level schema validation settings response failure |

**Success Response Schema:**

[api-shield_old_zone_schema_validation_settings](../schemas/api-shield/api-shield-old-zone-schema-validation-settings.md)

## Security

- **api_email**
- **api_key**
- **api_token**
