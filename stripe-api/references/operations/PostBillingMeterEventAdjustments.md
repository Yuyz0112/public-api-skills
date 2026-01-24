# POST /v1/billing/meter_event_adjustments

**Resource:** [billing](../resources/billing.md)
**Create a billing meter event adjustment**
**Operation ID:** `PostBillingMeterEventAdjustments`

<p>Creates a billing meter event adjustment.</p>

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[billing.meter_event_adjustment](../schemas/billing-meter/billing-meter-event-adjustment.md)

