# GET /v1/customers/{customer}/tax_ids/{id}

**Resource:** [customers](../resources/customers.md)
**Retrieve a Customer tax ID**
**Operation ID:** `GetCustomersCustomerTaxIdsId`

<p>Retrieves the <code>tax_id</code> object with the given identifier.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `customer` | path | string | Yes |  |
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

[tax_id](../schemas/tax/tax-id.md)

