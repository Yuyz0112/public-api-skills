# GET /admin/api/2020-01/customer_saved_searches.json

**Resource:** [customers/customersavedsearch](../resources/customers-customersavedsearch.md)
**Retrieves a list of customer saved searches. Note: As of version 2019-07, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints.**
**Operation ID:** `deprecated_202001_get_customer_saved_searches`

https://shopify.dev/docs/admin-api/rest/reference/customers/customersavedsearch#index-2020-01

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `limit` | query | any | No | The maximum number of results to show.
                  (default: 50, maximum: 250) |
| `since_id` | query | any | No | Restrict results to after the specified ID. |
| `fields` | query | any | No | Show only certain fields, specified by a comma-separated list of field names. |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

