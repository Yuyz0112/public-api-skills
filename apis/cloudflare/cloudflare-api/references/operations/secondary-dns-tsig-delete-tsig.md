# DELETE /accounts/{account_id}/secondary_dns/tsigs/{tsig_id}

**Resource:** [Secondary DNS (TSIG)](../resources/Secondary-DNS-TSIG.md)
**Delete TSIG**
**Operation ID:** `secondary-dns-(-tsig)-delete-tsig`

Delete TSIG.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `tsig_id` | path | secondary-dns_schemas-identifier | Yes |  |
| `account_id` | path | secondary-dns_account_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete TSIG response. |
| 4XX | Delete TSIG response failure. |

**Success Response Schema:**

[secondary-dns_schemas-id_response](../schemas/secondary-dns/secondary-dns-schemas-id-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
