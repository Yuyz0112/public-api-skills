# GET /v1/quotes/{quote}

**Resource:** [quotes](../resources/quotes.md)
**Retrieve a quote**
**Operation ID:** `GetQuotesQuote`

<p>Retrieves the quote with the given ID.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
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

