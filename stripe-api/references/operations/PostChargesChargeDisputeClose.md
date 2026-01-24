# POST /v1/charges/{charge}/dispute/close

**Resource:** [charges](../resources/charges.md)
**Operation ID:** `PostChargesChargeDisputeClose`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `charge` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[dispute](../schemas/dispute/dispute.md)

