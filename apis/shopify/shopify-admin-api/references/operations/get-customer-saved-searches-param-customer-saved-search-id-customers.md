# GET /admin/api/2020-10/customer_saved_searches/{customer_saved_search_id}/customers.json

**Resource:** [customers/customersavedsearch](../resources/customers-customersavedsearch.md)
**Retrieves all customers returned by a customer saved search.**
**Operation ID:** `get_customer_saved_searches_param_customer_saved_search_id_customers`

https://shopify.dev/docs/admin-api/rest/reference/customers/customersavedsearch#other-2020-10

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `customer_saved_search_id` | path | string | Yes | customer_saved_search_id |
| `order` | query | any | No | Set the field and direction by which to order results.
                  (default: last_order_date DESC) |
| `limit` | query | any | No | The maximum number of results to show.
                  (default: 50, maximum: 250) |
| `fields` | query | any | No | Show only certain fields, specified by a comma-separated list of field names. |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

