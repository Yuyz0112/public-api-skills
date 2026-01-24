# POST /v1/customers/{customer}/bank_accounts/{id}

**Resource:** [customers](../resources/customers.md)
**Operation ID:** `PostCustomersCustomerBankAccountsId`

<p>Update a specified source for a given customer.</p>

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

