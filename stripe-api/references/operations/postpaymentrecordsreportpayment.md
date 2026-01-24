# POST /v1/payment_records/report_payment

**Resource:** [payment_records](../resources/payment-records.md)
**Report a payment**
**Operation ID:** `PostPaymentRecordsReportPayment`

<p>Report a new Payment Record. You may report a Payment Record as it is
 initialized and later report updates through the other report_* methods, or report Payment
 Records in a terminal state directly, through this method.</p>

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

