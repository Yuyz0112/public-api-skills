# customers

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/v1/customers` | List all customers | [View](../operations/getcustomers.md) |
| POST | `/v1/customers` | Create a customer | [View](../operations/postcustomers.md) |
| GET | `/v1/customers/search` | Search customers | [View](../operations/getcustomerssearch.md) |
| GET | `/v1/customers/{customer}` | Retrieve a customer | [View](../operations/getcustomerscustomer.md) |
| POST | `/v1/customers/{customer}` | Update a customer | [View](../operations/postcustomerscustomer.md) |
| DELETE | `/v1/customers/{customer}` | Delete a customer | [View](../operations/deletecustomerscustomer.md) |
| GET | `/v1/customers/{customer}/balance_transactions` | List customer balance transactions | [View](../operations/getcustomerscustomerbalancetransactions.md) |
| POST | `/v1/customers/{customer}/balance_transactions` | Create a customer balance transaction | [View](../operations/postcustomerscustomerbalancetransactions.md) |
| GET | `/v1/customers/{customer}/balance_transactions/{transaction}` | Retrieve a customer balance transaction | [View](../operations/getcustomerscustomerbalancetransactionstransaction.md) |
| POST | `/v1/customers/{customer}/balance_transactions/{transaction}` | Update a customer credit balance transaction | [View](../operations/postcustomerscustomerbalancetransactionstransaction.md) |
| GET | `/v1/customers/{customer}/bank_accounts` | List all bank accounts | [View](../operations/getcustomerscustomerbankaccounts.md) |
| POST | `/v1/customers/{customer}/bank_accounts` | Create a card | [View](../operations/postcustomerscustomerbankaccounts.md) |
| GET | `/v1/customers/{customer}/bank_accounts/{id}` | Retrieve a bank account | [View](../operations/getcustomerscustomerbankaccountsid.md) |
| POST | `/v1/customers/{customer}/bank_accounts/{id}` |  | [View](../operations/postcustomerscustomerbankaccountsid.md) |
| DELETE | `/v1/customers/{customer}/bank_accounts/{id}` | Delete a customer source | [View](../operations/deletecustomerscustomerbankaccountsid.md) |
| POST | `/v1/customers/{customer}/bank_accounts/{id}/verify` | Verify a bank account | [View](../operations/postcustomerscustomerbankaccountsidverify.md) |
| GET | `/v1/customers/{customer}/cards` | List all cards | [View](../operations/getcustomerscustomercards.md) |
| POST | `/v1/customers/{customer}/cards` | Create a card | [View](../operations/postcustomerscustomercards.md) |
| GET | `/v1/customers/{customer}/cards/{id}` | Retrieve a card | [View](../operations/getcustomerscustomercardsid.md) |
| POST | `/v1/customers/{customer}/cards/{id}` |  | [View](../operations/postcustomerscustomercardsid.md) |
| DELETE | `/v1/customers/{customer}/cards/{id}` | Delete a customer source | [View](../operations/deletecustomerscustomercardsid.md) |
| GET | `/v1/customers/{customer}/cash_balance` | Retrieve a cash balance | [View](../operations/getcustomerscustomercashbalance.md) |
| POST | `/v1/customers/{customer}/cash_balance` | Update a cash balance's settings | [View](../operations/postcustomerscustomercashbalance.md) |
| GET | `/v1/customers/{customer}/cash_balance_transactions` | List cash balance transactions | [View](../operations/getcustomerscustomercashbalancetransactions.md) |
| GET | `/v1/customers/{customer}/cash_balance_transactions/{transaction}` | Retrieve a cash balance transaction | [View](../operations/getcustomerscustomercashbalancetransactionstransaction.md) |
| GET | `/v1/customers/{customer}/discount` |  | [View](../operations/getcustomerscustomerdiscount.md) |
| DELETE | `/v1/customers/{customer}/discount` | Delete a customer discount | [View](../operations/deletecustomerscustomerdiscount.md) |
| POST | `/v1/customers/{customer}/funding_instructions` | Create or retrieve funding instructions for a customer cash balance | [View](../operations/postcustomerscustomerfundinginstructions.md) |
| GET | `/v1/customers/{customer}/payment_methods` | List a Customer's PaymentMethods | [View](../operations/getcustomerscustomerpaymentmethods.md) |
| GET | `/v1/customers/{customer}/payment_methods/{payment_method}` | Retrieve a Customer's PaymentMethod | [View](../operations/getcustomerscustomerpaymentmethodspaymentmethod.md) |
| GET | `/v1/customers/{customer}/sources` |  | [View](../operations/getcustomerscustomersources.md) |
| POST | `/v1/customers/{customer}/sources` | Create a card | [View](../operations/postcustomerscustomersources.md) |
| GET | `/v1/customers/{customer}/sources/{id}` |  | [View](../operations/getcustomerscustomersourcesid.md) |
| POST | `/v1/customers/{customer}/sources/{id}` |  | [View](../operations/postcustomerscustomersourcesid.md) |
| DELETE | `/v1/customers/{customer}/sources/{id}` | Delete a customer source | [View](../operations/deletecustomerscustomersourcesid.md) |
| POST | `/v1/customers/{customer}/sources/{id}/verify` | Verify a bank account | [View](../operations/postcustomerscustomersourcesidverify.md) |
| GET | `/v1/customers/{customer}/subscriptions` | List active subscriptions | [View](../operations/getcustomerscustomersubscriptions.md) |
| POST | `/v1/customers/{customer}/subscriptions` | Create a subscription | [View](../operations/postcustomerscustomersubscriptions.md) |
| GET | `/v1/customers/{customer}/subscriptions/{subscription_exposed_id}` | Retrieve a subscription | [View](../operations/getcustomerscustomersubscriptionssubscriptionexposedid.md) |
| POST | `/v1/customers/{customer}/subscriptions/{subscription_exposed_id}` | Update a subscription on a customer | [View](../operations/postcustomerscustomersubscriptionssubscriptionexposedid.md) |
| DELETE | `/v1/customers/{customer}/subscriptions/{subscription_exposed_id}` | Cancel a subscription | [View](../operations/deletecustomerscustomersubscriptionssubscriptionexposedid.md) |
| GET | `/v1/customers/{customer}/subscriptions/{subscription_exposed_id}/discount` |  | [View](../operations/getcustomerscustomersubscriptionssubscriptionexposediddiscount.md) |
| DELETE | `/v1/customers/{customer}/subscriptions/{subscription_exposed_id}/discount` | Delete a customer discount | [View](../operations/deletecustomerscustomersubscriptionssubscriptionexposediddiscount.md) |
| GET | `/v1/customers/{customer}/tax_ids` | List all Customer tax IDs | [View](../operations/getcustomerscustomertaxids.md) |
| POST | `/v1/customers/{customer}/tax_ids` | Create a Customer tax ID | [View](../operations/postcustomerscustomertaxids.md) |
| GET | `/v1/customers/{customer}/tax_ids/{id}` | Retrieve a Customer tax ID | [View](../operations/getcustomerscustomertaxidsid.md) |
| DELETE | `/v1/customers/{customer}/tax_ids/{id}` | Delete a Customer tax ID | [View](../operations/deletecustomerscustomertaxidsid.md) |
