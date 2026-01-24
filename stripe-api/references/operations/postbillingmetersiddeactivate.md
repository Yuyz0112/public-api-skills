# POST /v1/billing/meters/{id}/deactivate

**Resource:** [billing](../resources/billing.md)
**Deactivate a billing meter**
**Operation ID:** `PostBillingMetersIdDeactivate`

<p>When a meter is deactivated, no more meter events will be accepted for this meter. You can’t attach a deactivated meter to a price.</p>

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

