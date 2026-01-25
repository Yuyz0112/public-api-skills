# DELETE /accounts/{account_id}/secondary_dns/peers/{peer_id}

**Resource:** [Secondary DNS (Peer)](../resources/Secondary-DNS-Peer.md)
**Delete Peer**
**Operation ID:** `secondary-dns-(-peer)-delete-peer`

Delete Peer.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `peer_id` | path | secondary-dns_components-schemas-identifier | Yes |  |
| `account_id` | path | secondary-dns_account_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete Peer response. |
| 4XX | Delete Peer response failure. |

**Success Response Schema:**

[secondary-dns_components-schemas-id_response](../schemas/secondary-dns/secondary-dns-components-schemas-id-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
