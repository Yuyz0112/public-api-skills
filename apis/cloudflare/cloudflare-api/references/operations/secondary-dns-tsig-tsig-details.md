# GET /accounts/{account_id}/secondary_dns/tsigs/{tsig_id}

**Resource:** [Secondary DNS (TSIG)](../resources/Secondary-DNS-TSIG.md)
**TSIG Details**
**Operation ID:** `secondary-dns-(-tsig)-tsig-details`

Get TSIG.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `tsig_id` | path | secondary-dns_schemas-identifier | Yes |  |
| `account_id` | path | secondary-dns_account_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | TSIG Details response. |
| 4XX | TSIG Details response failure. |

**Success Response Schema:**

[secondary-dns_single_response](../schemas/secondary-dns/secondary-dns-single-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
