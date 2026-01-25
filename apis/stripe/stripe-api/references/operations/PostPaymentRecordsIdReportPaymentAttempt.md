# POST /v1/payment_records/{id}/report_payment_attempt

**Resource:** [payment_records](../resources/payment-records.md)
**Report a payment attempt**
**Operation ID:** `PostPaymentRecordsIdReportPaymentAttempt`

<p>Report a new payment attempt on the specified Payment Record. A new payment
 attempt can only be specified if all other payment attempts are canceled or failed.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of the Payment Record. |

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[payment_record](../schemas/payment/payment-record.md)

