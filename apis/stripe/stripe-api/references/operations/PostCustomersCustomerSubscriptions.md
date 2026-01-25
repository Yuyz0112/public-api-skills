# POST /v1/customers/{customer}/subscriptions

**Resource:** [customers](../resources/customers.md)
**Create a subscription**
**Operation ID:** `PostCustomersCustomerSubscriptions`

<p>Creates a new subscription on an existing customer.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `customer` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[subscription](../schemas/subscription/subscription.md)

