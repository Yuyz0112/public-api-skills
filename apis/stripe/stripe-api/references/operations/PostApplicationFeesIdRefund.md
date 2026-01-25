# POST /v1/application_fees/{id}/refund

**Resource:** [application_fees](../resources/application-fees.md)
**Operation ID:** `PostApplicationFeesIdRefund`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[application_fee](../schemas/application/application-fee.md)

