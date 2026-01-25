# GET /accounts/{account_id}/secondary_dns/peers/{peer_id}

**Resource:** [Secondary DNS (Peer)](../resources/Secondary-DNS-Peer.md)
**Peer Details**
**Operation ID:** `secondary-dns-(-peer)-peer-details`

Get Peer.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `peer_id` | path | secondary-dns_components-schemas-identifier | Yes |  |
| `account_id` | path | secondary-dns_account_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Peer Details response. |
| 4XX | Peer Details response failure. |

**Success Response Schema:**

[secondary-dns_schemas-single_response](../schemas/secondary-dns/secondary-dns-schemas-single-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
