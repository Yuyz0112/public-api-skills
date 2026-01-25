# POST /accounts/{account_id}/magic/advanced_tcp_protection/configs/syn_protection/rules

**Resource:** [dos-flowtrackd-api_other](../resources/dos-flowtrackd-api-other.md)
**Create SYN Protection rule.**
**Operation ID:** `createSynProtectionRule`

Create a SYN Protection rule for an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | dos_identifier | Yes | The ID of the account. |

## Request Body

The new SYN Protection rule to add.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [dos_NewSynProtectionRule](../schemas/dos/dos-NewSynProtectionRule.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create SYN Protection rule response. |
| 4XX | Create SYN Protection rule failure. |

**Success Response Schema:**

[dos_syn-protection-rule-response](../schemas/dos/dos-syn-protection-rule-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
- **api_email**
- **api_key**
