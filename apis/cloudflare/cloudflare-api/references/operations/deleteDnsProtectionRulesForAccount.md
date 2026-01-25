# DELETE /accounts/{account_id}/magic/advanced_dns_protection/configs/dns_protection/rules

**Resource:** [dos-flowtrackd-api_other](../resources/dos-flowtrackd-api-other.md)
**Delete all DNS Protection rules.**
**Operation ID:** `deleteDnsProtectionRulesForAccount`

Delete all DNS Protection rules for an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | dos_identifier | Yes | The ID of the account. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete all DNS Protection rules response. |

**Success Response Schema:**

[dos_api-response-common](../schemas/dos/dos-api-response-common.md)

## Security

- **api_token**
- **api_email**
- **api_key**
- **api_email**
- **api_key**
