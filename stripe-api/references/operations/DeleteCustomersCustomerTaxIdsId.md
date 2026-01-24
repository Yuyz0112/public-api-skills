# DELETE /v1/customers/{customer}/tax_ids/{id}

**Resource:** [customers](../resources/customers.md)
**Delete a Customer tax ID**
**Operation ID:** `DeleteCustomersCustomerTaxIdsId`

<p>Deletes an existing <code>tax_id</code> object.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `customer` | path | string | Yes |  |
| `id` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[deleted_tax_id](../schemas/deleted/deleted-tax-id.md)

