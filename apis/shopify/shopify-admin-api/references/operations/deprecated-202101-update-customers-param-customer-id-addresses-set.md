# PUT /admin/api/2021-01/customers/{customer_id}/addresses/set.json

**Resource:** [customers/customer-address](../resources/customers-customer-address.md)
**Performs bulk operations for multiple customer addresses.**
**Operation ID:** `deprecated_202101_update_customers_param_customer_id_addresses_set`

https://shopify.dev/docs/admin-api/rest/reference/customers/customer-address#set-2021-01

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `customer_id` | path | string | Yes | customer_id |
| `address_ids[]` | query | integer | No | address_ids[] |
| `operation` | query | string | No | operation |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

