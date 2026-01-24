# GET /v1/subscriptions/{subscription_exposed_id}

**Resource:** [subscriptions](../resources/subscriptions.md)
**Retrieve a subscription**
**Operation ID:** `GetSubscriptionsSubscriptionExposedId`

<p>Retrieves the subscription with the given ID.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `subscription_exposed_id` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[subscription](../schemas/subscription/subscription.md)

