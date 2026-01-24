# POST /v1/application_fees/{fee}/refunds/{id}

**Resource:** [application_fees](../resources/application-fees.md)
**Update an application fee refund**
**Operation ID:** `PostApplicationFeesFeeRefundsId`

<p>Updates the specified application fee refund by setting the values of the parameters passed. Any parameters not provided will be left unchanged.</p>

<p>This request only accepts metadata as an argument.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
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

