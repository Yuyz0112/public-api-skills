# POST /accounts/{account_id}/secondary_dns/tsigs

**Resource:** [Secondary DNS (TSIG)](../resources/Secondary-DNS-TSIG.md)
**Create TSIG**
**Operation ID:** `secondary-dns-(-tsig)-create-tsig`

Create TSIG.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | secondary-dns_account_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [secondary-dns_tsig](../schemas/secondary-dns/secondary-dns-tsig.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create TSIG response. |
| 4XX | Create TSIG response failure. |

**Success Response Schema:**

[secondary-dns_single_response](../schemas/secondary-dns/secondary-dns-single-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
