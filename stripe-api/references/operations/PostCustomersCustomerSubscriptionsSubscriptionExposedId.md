# POST /v1/customers/{customer}/subscriptions/{subscription_exposed_id}

**Resource:** [customers](../resources/customers.md)
**Update a subscription on a customer**
**Operation ID:** `PostCustomersCustomerSubscriptionsSubscriptionExposedId`

<p>Updates an existing subscription on a customer to match the specified parameters. When changing plans or quantities, we will optionally prorate the price we charge next month to make up for any price changes. To preview how the proration will be calculated, use the <a href="#upcoming_invoice">upcoming invoice</a> endpoint.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `customer` | path | string | Yes |  |
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

