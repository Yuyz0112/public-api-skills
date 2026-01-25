# POST /accounts/{account_id}/magic/advanced_tcp_protection/configs/prefixes

**Resource:** [dos-flowtrackd-api_other](../resources/dos-flowtrackd-api-other.md)
**Create prefix.**
**Operation ID:** `createPrefix`

Create a prefix for an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | dos_identifier | Yes | The ID of the account. |

## Request Body

The new prefix to create.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [dos_NewPrefix](../schemas/dos/dos-NewPrefix.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create prefix response. |
| 4XX | Create prefix failure. |

**Success Response Schema:**

[dos_prefix-response](../schemas/dos/dos-prefix-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
- **api_email**
- **api_key**
