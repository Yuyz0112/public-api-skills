# POST /v1/billing/alerts/{id}/archive

**Resource:** [billing](../resources/billing.md)
**Archive a billing alert**
**Operation ID:** `PostBillingAlertsIdArchive`

<p>Archives this alert, removing it from the list view and APIs. This is non-reversible.</p>

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

