# GET /accounts/{account_id}/addressing/services

**Resource:** [IP Address Management Service Bindings](../resources/IP-Address-Management-Service-Bindings.md)
**List Services**
**Operation ID:** `ip-address-management-service-bindings-list-services`

Bring-Your-Own IP (BYOIP) prefixes onboarded to Cloudflare must be bound to a service running on the Cloudflare network to enable a Cloudflare product on the IP addresses. This endpoint can be used as a reference of available services on the Cloudflare network, and their service IDs.


## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | addressing_account_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Service names and IDs |
| 4XX | List Services response failure |

## Security

- **api_email**
- **api_key**
