# POST /v1/billing/meters/{id}

**Resource:** [billing](../resources/billing.md)
**Update a billing meter**
**Operation ID:** `PostBillingMetersId`

<p>Updates a billing meter.</p>

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

