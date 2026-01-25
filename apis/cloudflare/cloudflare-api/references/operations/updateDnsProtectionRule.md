# PATCH /accounts/{account_id}/magic/advanced_dns_protection/configs/dns_protection/rules/{rule_id}

**Resource:** [dos-flowtrackd-api_other](../resources/dos-flowtrackd-api-other.md)
**Update DNS Protection rule.**
**Operation ID:** `updateDnsProtectionRule`

Update a DNS Protection rule specified by the given UUID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | dos_identifier | Yes | The ID of the account. |
| `rule_id` | path | dos_uuid | Yes | The UUID of the DNS Protection rule to update. |

## Request Body

The updates to apply to the DNS Protection rule.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [dos_DnsProtectionRuleUpdate](../schemas/dos/dos-DnsProtectionRuleUpdate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update DNS Protection rule response. |
| 4XX | Update DNS Protection rule failure. |

**Success Response Schema:**

[dos_dns-protection-rule-response](../schemas/dos/dos-dns-protection-rule-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
- **api_email**
- **api_key**
