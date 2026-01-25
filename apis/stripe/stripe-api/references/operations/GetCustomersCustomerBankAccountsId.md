# GET /v1/customers/{customer}/bank_accounts/{id}

**Resource:** [customers](../resources/customers.md)
**Retrieve a bank account**
**Operation ID:** `GetCustomersCustomerBankAccountsId`
⚠️ **Deprecated**

<p>By default, you can see the 10 most recent sources stored on a Customer directly on the object, but you can also retrieve details about a specific bank account stored on the Stripe account.</p>

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

[bank_account](../schemas/bank/bank-account.md)

