# POST /v1/quotes/{quote}

**Resource:** [quotes](../resources/quotes.md)
**Update a quote**
**Operation ID:** `PostQuotesQuote`

<p>A quote models prices and services for a customer.</p>

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

