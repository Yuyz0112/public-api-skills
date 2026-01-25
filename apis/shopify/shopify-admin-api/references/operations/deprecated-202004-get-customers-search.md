# GET /admin/api/2020-04/customers/search.json

**Resource:** [customers/customer](../resources/customers-customer.md)
**Searches for customers that match a supplied query. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints.**
**Operation ID:** `deprecated_202004_get_customers_search`

https://shopify.dev/docs/admin-api/rest/reference/customers/customer#search-2020-04

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `order` | query | any | No | Set the field and direction by which to order results.
                  (default: last_order_date DESC) |
| `query` | query | any | No | Text to search for in the shop's customer data. |
| `limit` | query | any | No | The maximum number of results to show.
                  (default: 50, maximum: 250) |
| `fields` | query | any | No | Show only certain fields, specified by a comma-separated list of field names. |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

