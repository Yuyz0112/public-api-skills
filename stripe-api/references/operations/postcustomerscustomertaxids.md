# POST /v1/customers/{customer}/tax_ids

**Resource:** [customers](../resources/customers.md)
**Create a Customer tax ID**
**Operation ID:** `PostCustomersCustomerTaxIds`

<p>Creates a new <code>tax_id</code> object for a customer.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `customer` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[tax_id](../schemas/tax/tax-id.md)

