# GET /v1/billing/alerts/{id}

**Resource:** [billing](../resources/billing.md)
**Retrieve a billing alert**
**Operation ID:** `GetBillingAlertsId`

<p>Retrieves a billing alert given an ID</p>

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

[billing.alert](../schemas/billing-alert/billing-alert.md)

