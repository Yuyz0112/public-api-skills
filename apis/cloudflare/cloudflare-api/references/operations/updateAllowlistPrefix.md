# PATCH /accounts/{account_id}/magic/advanced_tcp_protection/configs/allowlist/{prefix_id}

**Resource:** [dos-flowtrackd-api_other](../resources/dos-flowtrackd-api-other.md)
**Update allowlist prefix.**
**Operation ID:** `updateAllowlistPrefix`

Update an allowlist prefix specified by the given UUID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | dos_identifier | Yes | The ID of the account. |
| `prefix_id` | path | dos_uuid | Yes | The UUID of the allowlist prefix to update. |

## Request Body

The updates to apply to the allowlist prefix.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [dos_InfraPrefixUpdate](../schemas/dos/dos-InfraPrefixUpdate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update allowlist prefix response. |
| 4XX | Update allowlist prefix failure. |

**Success Response Schema:**

[dos_infra-prefix-response](../schemas/dos/dos-infra-prefix-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
- **api_email**
- **api_key**
