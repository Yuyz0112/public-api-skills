# PATCH /accounts/{account_id}/zerotrust/subnets/cloudflare_source/{address_family}

**Resource:** [Zero Trust Subnets](../resources/Zero-Trust-Subnets.md)
**Update Cloudflare Source Subnet**
**Operation ID:** `zero-trust-networks-subnet-update-cloudflare-source`

Updates the Cloudflare Source subnet of the given address family

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | tunnel_account_id | Yes |  |
| `address_family` | path | tunnel_address_family | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update subnet response |
| 4XX | Update subnet response failure |

**Success Response Schema:**

[tunnel_subnet_response_single](../schemas/tunnel/tunnel-subnet-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
- **user_service_key**
