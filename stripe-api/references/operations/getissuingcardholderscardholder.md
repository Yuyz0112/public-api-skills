# GET /v1/issuing/cardholders/{cardholder}

**Resource:** [issuing](../resources/issuing.md)
**Retrieve a cardholder**
**Operation ID:** `GetIssuingCardholdersCardholder`

<p>Retrieves an Issuing <code>Cardholder</code> object.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `cardholder` | path | string | Yes |  |
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[issuing.cardholder](../schemas/issuing-cardholder/issuing-cardholder.md)

