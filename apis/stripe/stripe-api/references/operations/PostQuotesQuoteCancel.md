# POST /v1/quotes/{quote}/cancel

**Resource:** [quotes](../resources/quotes.md)
**Cancel a quote**
**Operation ID:** `PostQuotesQuoteCancel`

<p>Cancels the quote.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `quote` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[quote](../schemas/quote/quote.md)

