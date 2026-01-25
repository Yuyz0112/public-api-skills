# POST /accounts/{account_id}/dns_firewall

**Resource:** [DNS Firewall](../resources/DNS-Firewall.md)
**Create DNS Firewall Cluster**
**Operation ID:** `dns-firewall-create-dns-firewall-cluster`

Create a DNS Firewall cluster

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | dns-firewall_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [dns-firewall_dns-firewall-cluster-post](../schemas/dns-firewall/dns-firewall-dns-firewall-cluster-post.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create DNS Firewall Cluster response |
| 4XX | Create DNS Firewall Cluster response failure |

**Success Response Schema:**

[dns-firewall_dns_firewall_single_response](../schemas/dns-firewall/dns-firewall-dns-firewall-single-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
