# POST /v1/billing/meters

**Resource:** [billing](../resources/billing.md)
**Create a billing meter**
**Operation ID:** `PostBillingMeters`

<p>Creates a billing meter.</p>

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[billing.meter](../schemas/billing-meter/billing-meter.md)

