# POST /v1/issuing/cards

**Resource:** [issuing](../resources/issuing.md)
**Create a card**
**Operation ID:** `PostIssuingCards`

<p>Creates an Issuing <code>Card</code> object.</p>

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[issuing.card](../schemas/issuing-card/issuing-card.md)

