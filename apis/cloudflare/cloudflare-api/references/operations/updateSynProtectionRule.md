# PATCH /accounts/{account_id}/magic/advanced_tcp_protection/configs/syn_protection/rules/{rule_id}

**Resource:** [dos-flowtrackd-api_other](../resources/dos-flowtrackd-api-other.md)
**Update SYN Protection rule.**
**Operation ID:** `updateSynProtectionRule`

Update a SYN Protection rule specified by the given UUID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | dos_identifier | Yes | The ID of the account. |
| `rule_id` | path | dos_uuid | Yes | The UUID of the SYN Protection rule to update. |

## Request Body

The fields to update on the SYN Protection rule.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [dos_SynProtectionRuleUpdate](../schemas/dos/dos-SynProtectionRuleUpdate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update SYN Protection rule response. |
| 4XX | Update SYN Protection rule failure. |

**Success Response Schema:**

[dos_syn-protection-rule-response](../schemas/dos/dos-syn-protection-rule-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
- **api_email**
- **api_key**
