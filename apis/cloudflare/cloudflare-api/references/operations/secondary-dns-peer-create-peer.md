# POST /accounts/{account_id}/secondary_dns/peers

**Resource:** [Secondary DNS (Peer)](../resources/Secondary-DNS-Peer.md)
**Create Peer**
**Operation ID:** `secondary-dns-(-peer)-create-peer`

Create Peer.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | secondary-dns_account_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create Peer response. |
| 4XX | Create Peer response failure. |

**Success Response Schema:**

[secondary-dns_schemas-single_response](../schemas/secondary-dns/secondary-dns-schemas-single-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
