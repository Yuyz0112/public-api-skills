# GET /v1/payment_attempt_records/{id}

**Resource:** [payment_attempt_records](../resources/payment-attempt-records.md)
**Retrieve a Payment Attempt Record**
**Operation ID:** `GetPaymentAttemptRecordsId`

<p>Retrieves a Payment Attempt Record with the given ID</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `id` | path | string | Yes | The ID of the Payment Attempt Record. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[payment_attempt_record](../schemas/payment/payment-attempt-record.md)

