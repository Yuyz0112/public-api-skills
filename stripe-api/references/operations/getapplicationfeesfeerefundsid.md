# GET /v1/application_fees/{fee}/refunds/{id}

**Resource:** [application_fees](../resources/application-fees.md)
**Retrieve an application fee refund**
**Operation ID:** `GetApplicationFeesFeeRefundsId`

<p>By default, you can see the 10 most recent refunds stored directly on the application fee object, but you can also retrieve details about a specific refund stored on the application fee.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `fee` | path | string | Yes |  |
| `id` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[fee_refund](../schemas/fee/fee-refund.md)

