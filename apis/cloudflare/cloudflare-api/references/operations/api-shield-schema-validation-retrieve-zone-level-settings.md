# GET /zones/{zone_id}/api_gateway/settings/schema_validation

**Resource:** [API Shield Schema Validation 2.0](../resources/API-Shield-Schema-Validation-2-0.md)
**Retrieve zone level schema validation settings**
**Operation ID:** `api-shield-schema-validation-retrieve-zone-level-settings`
⚠️ **Deprecated**

Retrieves zone level schema validation settings currently set on the zone

## Responses

| Status | Description |
|--------|-------------|
| 200 | Zone level schema validation settings response |
| 4XX | Zone level schema validation settings response failure |

**Success Response Schema:**

[api-shield_old_zone_schema_validation_settings](../schemas/api-shield/api-shield-old-zone-schema-validation-settings.md)

## Security

- **api_email**
- **api_key**
- **api_token**
