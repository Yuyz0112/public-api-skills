# DELETE /v1/customers/{customer}

**Resource:** [customers](../resources/customers.md)
**Delete a customer**
**Operation ID:** `DeleteCustomersCustomer`

<p>Permanently deletes a customer. It cannot be undone. Also immediately cancels any active subscriptions on the customer.</p>

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

[deleted_customer](../schemas/deleted/deleted-customer.md)

