# DELETE /v1/customers/{customer}/discount

**Resource:** [customers](../resources/customers.md)
**Delete a customer discount**
**Operation ID:** `DeleteCustomersCustomerDiscount`

<p>Removes the currently applied discount on a customer.</p>

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

[deleted_discount](../schemas/deleted/deleted-discount.md)

