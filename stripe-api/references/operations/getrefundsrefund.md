# GET /v1/refunds/{refund}

**Resource:** [refunds](../resources/refunds.md)
**Retrieve a refund**
**Operation ID:** `GetRefundsRefund`

<p>Retrieves the details of an existing refund.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `refund` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[refund](../schemas/refund/refund.md)

