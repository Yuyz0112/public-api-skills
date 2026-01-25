# POST /v1/customers/{customer}/cards

**Resource:** [customers](../resources/customers.md)
**Create a card**
**Operation ID:** `PostCustomersCustomerCards`

<p>When you create a new credit card, you must specify a customer or recipient on which to create it.</p>

<p>If the card’s owner has no default card, then the new card will become the default.
However, if the owner already has a default, then it will not change.
To change the default, you should <a href="/docs/api#update_customer">update the customer</a> to have a new <code>default_source</code>.</p>

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

[payment_source](../schemas/payment/payment-source.md)

