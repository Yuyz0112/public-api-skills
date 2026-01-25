# GET /v1/billing/meters/{id}

**Resource:** [billing](../resources/billing.md)
**Retrieve a billing meter**
**Operation ID:** `GetBillingMetersId`

<p>Retrieves a billing meter given an ID.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
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

