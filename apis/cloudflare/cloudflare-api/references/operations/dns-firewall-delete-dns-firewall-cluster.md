# DELETE /accounts/{account_id}/dns_firewall/{dns_firewall_id}

**Resource:** [DNS Firewall](../resources/DNS-Firewall.md)
**Delete DNS Firewall Cluster**
**Operation ID:** `dns-firewall-delete-dns-firewall-cluster`

Delete a DNS Firewall cluster

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `dns_firewall_id` | path | dns-firewall_identifier | Yes |  |
| `account_id` | path | dns-firewall_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete DNS Firewall Cluster response |
| 4XX | Delete DNS Firewall Cluster response failure |

## Security

- **api_token**
- **api_email**
- **api_key**
