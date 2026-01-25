# PATCH /accounts/{account_id}/dns_firewall/{dns_firewall_id}/reverse_dns

**Resource:** [DNS Firewall](../resources/DNS-Firewall.md)
**Update DNS Firewall Cluster Reverse DNS**
**Operation ID:** `dns-firewall-update-dns-firewall-cluster-reverse-dns`

Update reverse DNS configuration (PTR records) for a DNS Firewall cluster

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `dns_firewall_id` | path | dns-firewall_identifier | Yes |  |
| `account_id` | path | dns-firewall_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [dns-firewall_dns-firewall-reverse-dns-patch](../schemas/dns-firewall/dns-firewall-dns-firewall-reverse-dns-patch.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update DNS Firewall Cluster Reverse DNS response |
| 4XX | Update DNS Firewall Cluster Reverse DNS response failure |

**Success Response Schema:**

[dns-firewall_dns_firewall_reverse_dns_response](../schemas/dns-firewall/dns-firewall-dns-firewall-reverse-dns-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
