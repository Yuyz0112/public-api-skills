# GET /zones/{zone_id}/api_gateway/user_schemas

**Resource:** [API Shield Schema Validation 2.0](../resources/API-Shield-Schema-Validation-2-0.md)
**Retrieve information about all schemas on a zone**
**Operation ID:** `api-shield-schema-validation-retrieve-information-about-all-schemas`
⚠️ **Deprecated**

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `validation_enabled` | query | api-shield_old_validation_enabled | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Retrieve information about all schemas on a zone response |
| 4XX | Retrieve information about all schemas on a zone response failure |

## Security

- **api_email**
- **api_key**
- **api_token**
