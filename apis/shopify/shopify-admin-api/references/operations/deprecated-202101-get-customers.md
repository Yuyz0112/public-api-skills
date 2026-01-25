# GET /admin/api/2021-01/customers.json

**Resource:** [customers/customer](../resources/customers-customer.md)
**Retrieves a list of customers. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints.**
**Operation ID:** `deprecated_202101_get_customers`

https://shopify.dev/docs/admin-api/rest/reference/customers/customer#index-2021-01

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `ids` | query | any | No | Restrict results to customers specified by a comma-separated list of IDs. |
| `since_id` | query | any | No | Restrict results to those after the specified ID. |
| `created_at_min` | query | any | No | Show customers created after a specified date.(format: 2014-04-25T16:15:47-04:00) |
| `created_at_max` | query | any | No | Show customers created before a specified date.(format: 2014-04-25T16:15:47-04:00) |
| `updated_at_min` | query | any | No | Show customers last updated after a specified date.(format: 2014-04-25T16:15:47-04:00) |
| `updated_at_max` | query | any | No | Show customers last updated before a specified date.(format: 2014-04-25T16:15:47-04:00) |
| `limit` | query | any | No | The maximum number of results to show.
                  (default: 50, maximum: 250) |
| `fields` | query | any | No | Show only certain fields, specified by a comma-separated list of field names. |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

