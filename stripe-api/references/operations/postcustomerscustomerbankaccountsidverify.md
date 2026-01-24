# POST /v1/customers/{customer}/bank_accounts/{id}/verify

**Resource:** [customers](../resources/customers.md)
**Verify a bank account**
**Operation ID:** `PostCustomersCustomerBankAccountsIdVerify`

<p>Verify a specified bank account for a given customer.</p>

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

[bank_account](../schemas/bank/bank-account.md)

