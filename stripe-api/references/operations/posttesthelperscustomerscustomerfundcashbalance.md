# POST /v1/test_helpers/customers/{customer}/fund_cash_balance

**Resource:** [test_helpers](../resources/test-helpers.md)
**Fund a test mode cash balance**
**Operation ID:** `PostTestHelpersCustomersCustomerFundCashBalance`

<p>Create an incoming testmode bank transfer</p>

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

[customer_cash_balance_transaction](../schemas/customer/customer-cash-balance-transaction.md)

