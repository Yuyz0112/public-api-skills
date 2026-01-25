# GET /admin/api/2021-01/gift_cards/search.json

**Resource:** [plus/giftcard](../resources/plus-giftcard.md)
**Searches for gift cards that match a supplied query. The following fields are indexed by search:
          
            created_at
            updated_at
            disabled_at
            balance
            initial_value
            amount_spent
            email
            last_characters
          
          Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints.**
**Operation ID:** `deprecated_202101_get_gift_cards_search`

https://shopify.dev/docs/admin-api/rest/reference/plus/giftcard#search-2021-01

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `order` | query | any | No | The field and direction to order results by.
                  (default: disabled_at DESC) |
| `query` | query | any | No | The text to search for. |
| `limit` | query | any | No | The maximum number of results to retrieve.
                  (default: 50, maximum: 250) |
| `fields` | query | any | No | Show only certain fields, specified by a comma-separated list of field names. |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

