# PUT /accounts/{account_id}/secondary_dns/peers/{peer_id}

**Resource:** [Secondary DNS (Peer)](../resources/Secondary-DNS-Peer.md)
**Update Peer**
**Operation ID:** `secondary-dns-(-peer)-update-peer`

Modify Peer.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `peer_id` | path | secondary-dns_components-schemas-identifier | Yes |  |
| `account_id` | path | secondary-dns_account_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [secondary-dns_peer](../schemas/secondary-dns/secondary-dns-peer.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update Peer response. |
| 4XX | Update Peer response failure. |

**Success Response Schema:**

[secondary-dns_schemas-single_response](../schemas/secondary-dns/secondary-dns-schemas-single-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
