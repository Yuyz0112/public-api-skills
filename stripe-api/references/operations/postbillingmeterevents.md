# POST /v1/billing/meter_events

**Resource:** [billing](../resources/billing.md)
**Create a billing meter event**
**Operation ID:** `PostBillingMeterEvents`

<p>Creates a billing meter event.</p>

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[billing.meter_event](../schemas/billing-meter/billing-meter-event.md)

