# GET /admin/api/2020-01/tender_transactions.json

**Resource:** [tendertransaction](../resources/tendertransaction.md)
**Retrieves a list of tender transactions. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. To learn more, see Making requests to paginated REST Admin API endpoints.**
**Operation ID:** `deprecated_202001_get_tender_transactions`

https://shopify.dev/docs/admin-api/rest/reference/tendertransaction#index-2020-01

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `limit` | query | any | No | The maximum number of results to retrieve.
                  (default: 50, maximum: 250) |
| `since_id` | query | any | No | Retrieve only transactions after the specified ID. |
| `processed_at_min` | query | any | No | Show tender transactions processed_at or after the specified date. |
| `processed_at_max` | query | any | No | Show tender transactions processed_at or before the specified date. |
| `processed_at` | query | any | No | Show tender transactions processed at the specified date. |
| `order` | query | any | No | Show tender transactions ordered by processed_at in ascending or descending order. |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

