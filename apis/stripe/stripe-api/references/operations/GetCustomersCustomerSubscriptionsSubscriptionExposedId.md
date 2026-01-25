# GET /v1/customers/{customer}/subscriptions/{subscription_exposed_id}

**Resource:** [customers](../resources/customers.md)
**Retrieve a subscription**
**Operation ID:** `GetCustomersCustomerSubscriptionsSubscriptionExposedId`

<p>Retrieves the subscription with the given ID.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `customer` | path | string | Yes |  |
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

