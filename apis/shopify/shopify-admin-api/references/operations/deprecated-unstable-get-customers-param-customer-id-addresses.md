# GET /admin/api/unstable/customers/{customer_id}/addresses.json

**Resource:** [customers/customer-address](../resources/customers-customer-address.md)
**Retrieves a list of addresses for a customer. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints.**
**Operation ID:** `deprecated_unstable_get_customers_param_customer_id_addresses`

https://shopify.dev/docs/admin-api/rest/reference/customers/customer-address#index-unstable

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `customer_id` | path | string | Yes | customer_id |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

