# POST /v1/payment_records/{id}/report_payment_attempt_canceled

**Resource:** [payment_records](../resources/payment-records.md)
**Report payment attempt canceled**
**Operation ID:** `PostPaymentRecordsIdReportPaymentAttemptCanceled`

<p>Report that the most recent payment attempt on the specified Payment Record
 was canceled.</p>

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

