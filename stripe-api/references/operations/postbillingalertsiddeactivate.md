# POST /v1/billing/alerts/{id}/deactivate

**Resource:** [billing](../resources/billing.md)
**Deactivate a billing alert**
**Operation ID:** `PostBillingAlertsIdDeactivate`

<p>Deactivates this alert, preventing it from triggering.</p>

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

[billing.alert](../schemas/billing-alert/billing-alert.md)

