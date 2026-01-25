# GET /accounts/{account_id}/dns_firewall/{dns_firewall_id}

**Resource:** [DNS Firewall](../resources/DNS-Firewall.md)
**DNS Firewall Cluster Details**
**Operation ID:** `dns-firewall-dns-firewall-cluster-details`

Show a single DNS Firewall cluster for an account

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `dns_firewall_id` | path | dns-firewall_identifier | Yes |  |
| `account_id` | path | dns-firewall_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | DNS Firewall Cluster Details response |
| 4XX | DNS Firewall Cluster Details response failure |

**Success Response Schema:**

[dns-firewall_dns_firewall_single_response](../schemas/dns-firewall/dns-firewall-dns-firewall-single-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
