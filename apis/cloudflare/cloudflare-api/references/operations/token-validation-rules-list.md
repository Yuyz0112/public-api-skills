# GET /zones/{zone_id}/token_validation/rules

**Resource:** [Token Validation Token Rules](../resources/Token-Validation-Token-Rules.md)
**List token validation rules**
**Operation ID:** `token-validation-rules-list`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token_configuration` | query | api-shield_schemas-uuid[] | No | Select rules using any of these token configurations. |
| `action` | query | api-shield_action | No |  |
| `enabled` | query | api-shield_enabled | No |  |
| `id` | query | api-shield_schemas-uuid | No | Select rules with these IDs. |
| `rule_id` | query | api-shield_schemas-uuid | No | Select rules with these IDs. |
| `host` | query | api-shield_host | No | Select rules with this host in `include`. |
| `hostname` | query | api-shield_host | No | Select rules with this host in `include`. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |
| 4XX | (reference) |

## Security

- **api_token**
- **api_email**
- **api_key**
