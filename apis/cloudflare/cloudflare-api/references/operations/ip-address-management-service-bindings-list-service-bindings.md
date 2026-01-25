# GET /accounts/{account_id}/addressing/prefixes/{prefix_id}/bindings

**Resource:** [IP Address Management Service Bindings](../resources/IP-Address-Management-Service-Bindings.md)
**List Service Bindings**
**Operation ID:** `ip-address-management-service-bindings-list-service-bindings`

List the Cloudflare services this prefix is currently bound to. Traffic sent to an address within an IP prefix will be routed to the Cloudflare service of the most-specific Service Binding matching the address.
**Example:** binding `192.0.2.0/24` to Cloudflare Magic Transit and `192.0.2.1/32` to the Cloudflare CDN would route traffic for `192.0.2.1` to the CDN, and traffic for all other IPs in the prefix to Cloudflare Magic Transit.


## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | addressing_account_identifier | Yes |  |
| `prefix_id` | path | addressing_prefix_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Service Bindings attached to the Prefix |
| 4XX | List Service Bindings response failure |

## Security

- **api_email**
- **api_key**
