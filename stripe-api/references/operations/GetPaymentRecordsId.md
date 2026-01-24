# GET /v1/payment_records/{id}

**Resource:** [payment_records](../resources/payment-records.md)
**Retrieve a Payment Record**
**Operation ID:** `GetPaymentRecordsId`

<p>Retrieves a Payment Record with the given ID</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
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

