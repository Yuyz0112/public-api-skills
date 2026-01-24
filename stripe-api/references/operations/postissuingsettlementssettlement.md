# POST /v1/issuing/settlements/{settlement}

**Resource:** [issuing](../resources/issuing.md)
**Update a settlement**
**Operation ID:** `PostIssuingSettlementsSettlement`

<p>Updates the specified Issuing <code>Settlement</code> object by setting the values of the parameters passed. Any parameters not provided will be left unchanged.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
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

