# POST /v1/payment_records/{id}/report_payment_attempt_informational

**Resource:** [payment_records](../resources/payment-records.md)
**Report payment attempt informational**
**Operation ID:** `PostPaymentRecordsIdReportPaymentAttemptInformational`

<p>Report informational updates on the specified Payment Record.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of the Payment Record. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[payment_record](../schemas/payment/payment-record.md)

