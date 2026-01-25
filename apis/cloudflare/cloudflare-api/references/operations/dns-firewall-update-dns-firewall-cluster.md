# PATCH /accounts/{account_id}/dns_firewall/{dns_firewall_id}

**Resource:** [DNS Firewall](../resources/DNS-Firewall.md)
**Update DNS Firewall Cluster**
**Operation ID:** `dns-firewall-update-dns-firewall-cluster`

Modify the configuration of a DNS Firewall cluster

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `dns_firewall_id` | path | dns-firewall_identifier | Yes |  |
| `account_id` | path | dns-firewall_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [dns-firewall_dns-firewall-cluster-patch](../schemas/dns-firewall/dns-firewall-dns-firewall-cluster-patch.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update DNS Firewall Cluster response |
| 4XX | Update DNS Firewall Cluster response failure |

**Success Response Schema:**

[dns-firewall_dns_firewall_single_response](../schemas/dns-firewall/dns-firewall-dns-firewall-single-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
