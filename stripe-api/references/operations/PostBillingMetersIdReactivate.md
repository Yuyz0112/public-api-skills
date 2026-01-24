# POST /v1/billing/meters/{id}/reactivate

**Resource:** [billing](../resources/billing.md)
**Reactivate a billing meter**
**Operation ID:** `PostBillingMetersIdReactivate`

<p>When a meter is reactivated, events for this meter can be accepted and you can attach the meter to a price.</p>

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

[billing.meter](../schemas/billing-meter/billing-meter.md)

