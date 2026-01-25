# GET /accounts/{account_id}/secondary_dns/peers

**Resource:** [Secondary DNS (Peer)](../resources/Secondary-DNS-Peer.md)
**List Peers**
**Operation ID:** `secondary-dns-(-peer)-list-peers`

List Peers.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | secondary-dns_account_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Peers response. |
| 4XX | List Peers response failure. |

**Success Response Schema:**

[secondary-dns_schemas-response_collection](../schemas/secondary-dns/secondary-dns-schemas-response-collection.md)

## Security

- **api_token**
- **api_email**
- **api_key**
