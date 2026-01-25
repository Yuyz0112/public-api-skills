# POST /zones/{zone_id}/token_validation/rules/preview

**Resource:** [Token Validation Token Rules](../resources/Token-Validation-Token-Rules.md)
**Preview operations covered by a Token Validation rule**
**Operation ID:** `token-validation-rules-preview`

Preview operations covered by a Token Validation rule.

The API will return all operations on a zone annotated with an additional `state` field.
Operations with an `included` `state` will be covered by a Token Validation Rule.


## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `state` | query | api-shield_selector-operation-state[] | No |  |
| `host` | query | api-shield_host[] | No | Filter operations by host. |
| `hostname` | query | api-shield_host[] | No | Filter operations by host. |
| `method` | query | api-shield_method[] | No | Filter operations by method. |
| `endpoint` | query | api-shield_endpoint[] | No | Filter operations by endpoint. Allows substring matching. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |
| 4XX | (reference) |

## Security

- **api_token**
- **api_email**
- **api_key**
