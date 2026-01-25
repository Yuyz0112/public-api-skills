# GET /v1/customers/{customer}/cash_balance

**Resource:** [customers](../resources/customers.md)
**Retrieve a cash balance**
**Operation ID:** `GetCustomersCustomerCashBalance`

<p>Retrieves a customer’s cash balance.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `customer` | path | string | Yes |  |
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[cash_balance](../schemas/cash/cash-balance.md)

