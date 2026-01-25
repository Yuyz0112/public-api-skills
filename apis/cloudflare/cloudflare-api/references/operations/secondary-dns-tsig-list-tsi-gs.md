# GET /accounts/{account_id}/secondary_dns/tsigs

**Resource:** [Secondary DNS (TSIG)](../resources/Secondary-DNS-TSIG.md)
**List TSIGs**
**Operation ID:** `secondary-dns-(-tsig)-list-tsi-gs`

List TSIGs.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | secondary-dns_account_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List TSIGs response. |
| 4XX | List TSIGs response failure. |

**Success Response Schema:**

[secondary-dns_response_collection](../schemas/secondary-dns/secondary-dns-response-collection.md)

## Security

- **api_token**
- **api_email**
- **api_key**
