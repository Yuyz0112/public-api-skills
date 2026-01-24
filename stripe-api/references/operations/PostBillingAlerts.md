# POST /v1/billing/alerts

**Resource:** [billing](../resources/billing.md)
**Create a billing alert**
**Operation ID:** `PostBillingAlerts`

<p>Creates a billing alert</p>

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[billing.alert](../schemas/billing-alert/billing-alert.md)

