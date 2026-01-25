# GET /v1/issuing/settlements/{settlement}

**Resource:** [issuing](../resources/issuing.md)
**Retrieve a settlement**
**Operation ID:** `GetIssuingSettlementsSettlement`

<p>Retrieves an Issuing <code>Settlement</code> object.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `settlement` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[issuing.settlement](../schemas/issuing-settlement/issuing-settlement.md)

