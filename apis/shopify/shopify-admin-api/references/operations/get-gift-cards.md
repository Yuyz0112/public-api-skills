# GET /admin/api/2020-10/gift_cards.json

**Resource:** [plus/giftcard](../resources/plus-giftcard.md)
**Retrieves a list of gift cards. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints.**
**Operation ID:** `get_gift_cards`

https://shopify.dev/docs/admin-api/rest/reference/plus/giftcard#index-2020-10

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `status` | query | any | No | Retrieve gift cards with a given status. Valid values:
                    
                        enabled: Restrict results to only enabled gift cards
                        disabled: Restrict results to only disabled gift cards |
| `limit` | query | any | No | The maximum number of results to show.
                  (default: 50, maximum: 250) |
| `since_id` | query | any | No | Restrict results to after the specified ID. |
| `fields` | query | any | No | Show only certain fields, specified by a comma-separated list of field names. |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

