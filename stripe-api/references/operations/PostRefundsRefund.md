# POST /v1/refunds/{refund}

**Resource:** [refunds](../resources/refunds.md)
**Update a refund**
**Operation ID:** `PostRefundsRefund`

<p>Updates the refund that you specify by setting the values of the passed parameters. Any parameters that you don’t provide remain unchanged.</p>

<p>This request only accepts <code>metadata</code> as an argument.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
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

