# POST /v1/customers/{customer}/cash_balance

**Resource:** [customers](../resources/customers.md)
**Update a cash balance's settings**
**Operation ID:** `PostCustomersCustomerCashBalance`

<p>Changes the settings on a customer’s cash balance.</p>

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

[cash_balance](../schemas/cash/cash-balance.md)

