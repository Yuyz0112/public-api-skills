# POST /zones/{zone_id}/secondary_dns/outgoing/force_notify

**Resource:** [Secondary DNS (Primary Zone)](../resources/Secondary-DNS-Primary-Zone.md)
**Force DNS NOTIFY**
**Operation ID:** `secondary-dns-(-primary-zone)-force-dns-notify`

Notifies the secondary nameserver(s) and clears IXFR backlog of primary zone.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | secondary-dns_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Force DNS NOTIFY response. |
| 4XX | Force DNS NOTIFY response failure. |

**Success Response Schema:**

[secondary-dns_schemas-force_response](../schemas/secondary-dns/secondary-dns-schemas-force-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
