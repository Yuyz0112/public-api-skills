# POST /v1/issuing/cardholders/{cardholder}

**Resource:** [issuing](../resources/issuing.md)
**Update a cardholder**
**Operation ID:** `PostIssuingCardholdersCardholder`

<p>Updates the specified Issuing <code>Cardholder</code> object by setting the values of the parameters passed. Any parameters not provided will be left unchanged.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `cardholder` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[issuing.cardholder](../schemas/issuing-cardholder/issuing-cardholder.md)

