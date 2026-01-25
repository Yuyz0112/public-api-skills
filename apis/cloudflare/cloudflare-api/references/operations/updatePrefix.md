# PATCH /accounts/{account_id}/magic/advanced_tcp_protection/configs/prefixes/{prefix_id}

**Resource:** [dos-flowtrackd-api_other](../resources/dos-flowtrackd-api-other.md)
**Update prefix.**
**Operation ID:** `updatePrefix`

Update a prefix specified by the given UUID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | dos_identifier | Yes | The ID of the account. |
| `prefix_id` | path | dos_uuid | Yes | The UUID of the prefix to update. |

## Request Body

The updates to apply to the prefix.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [dos_PrefixUpdate](../schemas/dos/dos-PrefixUpdate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update prefix response. |
| 4XX | Update prefix failure. |

**Success Response Schema:**

[dos_prefix-response](../schemas/dos/dos-prefix-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
- **api_email**
- **api_key**
