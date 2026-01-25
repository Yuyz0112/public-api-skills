# GET /accounts/{account_id}/dns_records/usage

**Resource:** [DNS Records for an Account](../resources/DNS-Records-for-an-Account.md)
**Get DNS Record Usage for Account**
**Operation ID:** `dns-records-for-an-account-get-usage`

Get the current DNS record usage and quota for an account. May include internal DNS usage and quota.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | dns-records_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get DNS Record Usage response |
| 4XX | Get DNS Record Usage response failure |

**Success Response Schema:**

[dns-records_dns_response_account_usage](../schemas/dns-records/dns-records-dns-response-account-usage.md)

## Security

- **api_token**
- **api_email**
- **api_key**
