# GET /v1/treasury/credit_reversals/{credit_reversal}

**Resource:** [treasury](../resources/treasury.md)
**Retrieve a CreditReversal**
**Operation ID:** `GetTreasuryCreditReversalsCreditReversal`

<p>Retrieves the details of an existing CreditReversal by passing the unique CreditReversal ID from either the CreditReversal creation request or CreditReversal list</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `credit_reversal` | path | string | Yes |  |
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[treasury.credit_reversal](../schemas/treasury-credit/treasury-credit-reversal.md)

