# POST /accounts/{account_id}/magic/advanced_tcp_protection/configs/allowlist

**Resource:** [dos-flowtrackd-api_other](../resources/dos-flowtrackd-api-other.md)
**Create allowlist prefix.**
**Operation ID:** `createAllowlistedPrefix`

Create an allowlist prefix for an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | dos_identifier | Yes | The ID of the account. |

## Request Body

The new allowlist prefix to create.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [dos_NewInfraPrefix](../schemas/dos/dos-NewInfraPrefix.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create allowlist prefix response. |
| 4XX | Create allowlist prefix failure. |

**Success Response Schema:**

[dos_infra-prefix-response](../schemas/dos/dos-infra-prefix-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
- **api_email**
- **api_key**
