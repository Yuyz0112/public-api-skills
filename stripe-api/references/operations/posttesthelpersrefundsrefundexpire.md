# POST /v1/test_helpers/refunds/{refund}/expire

**Resource:** [test_helpers](../resources/test-helpers.md)
**Expire a pending refund.**
**Operation ID:** `PostTestHelpersRefundsRefundExpire`

<p>Expire a refund with a status of <code>requires_action</code>.</p>

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

