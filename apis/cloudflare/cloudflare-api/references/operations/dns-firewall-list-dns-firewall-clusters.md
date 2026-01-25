# GET /accounts/{account_id}/dns_firewall

**Resource:** [DNS Firewall](../resources/DNS-Firewall.md)
**List DNS Firewall Clusters**
**Operation ID:** `dns-firewall-list-dns-firewall-clusters`

List DNS Firewall clusters for an account

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | dns-firewall_identifier | Yes |  |
| `page` | query | number | No |  |
| `per_page` | query | number | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List DNS Firewall Clusters response |
| 4XX | List DNS Firewall Clusters response failure |

**Success Response Schema:**

[dns-firewall_dns_firewall_response_collection](../schemas/dns-firewall/dns-firewall-dns-firewall-response-collection.md)

## Security

- **api_token**
- **api_email**
- **api_key**
