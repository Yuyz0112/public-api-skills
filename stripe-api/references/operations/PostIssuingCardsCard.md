# POST /v1/issuing/cards/{card}

**Resource:** [issuing](../resources/issuing.md)
**Update a card**
**Operation ID:** `PostIssuingCardsCard`

<p>Updates the specified Issuing <code>Card</code> object by setting the values of the parameters passed. Any parameters not provided will be left unchanged.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `card` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[issuing.card](../schemas/issuing-card/issuing-card.md)

