# POST /v1/issuing/cardholders

**Resource:** [issuing](../resources/issuing.md)
**Create a cardholder**
**Operation ID:** `PostIssuingCardholders`

<p>Creates a new Issuing <code>Cardholder</code> object that can be issued cards.</p>

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[issuing.cardholder](../schemas/issuing-cardholder/issuing-cardholder.md)

