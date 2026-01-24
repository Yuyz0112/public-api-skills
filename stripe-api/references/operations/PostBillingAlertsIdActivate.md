# POST /v1/billing/alerts/{id}/activate

**Resource:** [billing](../resources/billing.md)
**Activate a billing alert**
**Operation ID:** `PostBillingAlertsIdActivate`

<p>Reactivates this alert, allowing it to trigger again.</p>

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

