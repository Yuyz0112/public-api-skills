# POST /accounts/{account_id}/addressing/prefixes/{prefix_id}/bindings

**Resource:** [IP Address Management Service Bindings](../resources/IP-Address-Management-Service-Bindings.md)
**Create Service Binding**
**Operation ID:** `ip-address-management-service-bindings-create-service-binding`

Creates a new Service Binding, routing traffic to IPs within the given CIDR to a service running on Cloudflare's network.
**NOTE:** The first Service Binding created for an IP Prefix must exactly match the IP Prefix's CIDR. Subsequent Service Bindings may be created with a more-specific CIDR. Refer to the  [Service Bindings Documentation](https://developers.cloudflare.com/byoip/service-bindings/) for compatibility details.


## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | addressing_account_identifier | Yes |  |
| `prefix_id` | path | addressing_prefix_identifier | Yes |  |

## Request Body

**Content Types:** `application/json`

**Schema:** [addressing_create_binding_request](../schemas/addressing/addressing-create-binding-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | The created Service Binding |
| 4XX | Create Service Binding response failure |

## Security

- **api_email**
- **api_key**
