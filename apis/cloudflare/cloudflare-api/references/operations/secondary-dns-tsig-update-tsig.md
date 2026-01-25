# PUT /accounts/{account_id}/secondary_dns/tsigs/{tsig_id}

**Resource:** [Secondary DNS (TSIG)](../resources/Secondary-DNS-TSIG.md)
**Update TSIG**
**Operation ID:** `secondary-dns-(-tsig)-update-tsig`

Modify TSIG.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `tsig_id` | path | secondary-dns_schemas-identifier | Yes |  |
| `account_id` | path | secondary-dns_account_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [secondary-dns_tsig](../schemas/secondary-dns/secondary-dns-tsig.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update TSIG response. |
| 4XX | Update TSIG response failure. |

**Success Response Schema:**

[secondary-dns_single_response](../schemas/secondary-dns/secondary-dns-single-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
