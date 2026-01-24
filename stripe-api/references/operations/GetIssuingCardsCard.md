# GET /v1/issuing/cards/{card}

**Resource:** [issuing](../resources/issuing.md)
**Retrieve a card**
**Operation ID:** `GetIssuingCardsCard`

<p>Retrieves an Issuing <code>Card</code> object.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `card` | path | string | Yes |  |
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[issuing.card](../schemas/issuing-card/issuing-card.md)

