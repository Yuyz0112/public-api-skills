# POST /accounts/{account_id}/magic/advanced_dns_protection/configs/dns_protection/rules

**Resource:** [dos-flowtrackd-api_other](../resources/dos-flowtrackd-api-other.md)
**Create DNS Protection rule.**
**Operation ID:** `createDnsProtectionRule`

Create a DNS Protection rule for an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | dos_identifier | Yes | The ID of the account. |

## Request Body

The new DNS Protection rule to add.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [dos_NewDnsProtectionRule](../schemas/dos/dos-NewDnsProtectionRule.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create DNS Protection rule response. |
| 4XX | Create DNS Protection rule failure. |

**Success Response Schema:**

[dos_dns-protection-rule-response](../schemas/dos/dos-dns-protection-rule-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
- **api_email**
- **api_key**
