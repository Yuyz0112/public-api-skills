# GET /accounts/{account_id}/zerotrust/subnets

**Resource:** [Zero Trust Subnets](../resources/Zero-Trust-Subnets.md)
**List Subnets**
**Operation ID:** `zero-trust-networks-subnets-list`

Lists and filters subnets in an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | tunnel_account_id | Yes |  |
| `name` | query | tunnel_subnet_query_name | No | If set, only list subnets with the given name |
| `comment` | query | tunnel_subnet_query_comment | No |  |
| `network` | query | any | No |  |
| `existed_at` | query | tunnel_existed_at | No |  |
| `address_family` | query | tunnel_address_family | No | If set, only include subnets in the given address family - `v4` or `v6` |
| `is_default_network` | query | boolean | No |  |
| `is_deleted` | query | boolean | No |  |
| `sort_order` | query | enum: asc, desc | No |  |
| `subnet_types` | query | enum: cloudflare_source, warp | No |  |
| `per_page` | query | tunnel_per_page | No |  |
| `page` | query | tunnel_page_number | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List subnets response |
| 4XX | List subnets response failure |

**Success Response Schema:**

[tunnel_subnet_response_collection](../schemas/tunnel/tunnel-subnet-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
- **user_service_key**
