# POST /accounts/{account_id}/magic/advanced_tcp_protection/configs/prefixes/bulk

**Resource:** [dos-flowtrackd-api_other](../resources/dos-flowtrackd-api-other.md)
**Create multiple prefixes.**
**Operation ID:** `bulkCreatePrefixes`

Create multiple prefixes for an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | dos_identifier | Yes | The ID of the account. |

## Request Body

The list of new prefixes to create.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** Array of [dos_NewPrefix](../schemas/dos/dos-NewPrefix.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create multiple prefixes response. |
| 4XX | Create multiple prefixes failure. |

**Success Response Schema:**

[dos_prefix-list-response](../schemas/dos/dos-prefix-list-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
- **api_email**
- **api_key**
