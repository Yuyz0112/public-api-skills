# customers

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/v1/customers` | List all customers | [View](../operations/GetCustomers.md) |
| POST | `/v1/customers` | Create a customer | [View](../operations/PostCustomers.md) |
| GET | `/v1/customers/search` | Search customers | [View](../operations/GetCustomersSearch.md) |
| GET | `/v1/customers/{customer}` | Retrieve a customer | [View](../operations/GetCustomersCustomer.md) |
| POST | `/v1/customers/{customer}` | Update a customer | [View](../operations/PostCustomersCustomer.md) |
| DELETE | `/v1/customers/{customer}` | Delete a customer | [View](../operations/DeleteCustomersCustomer.md) |
| GET | `/v1/customers/{customer}/balance_transactions` | List customer balance transactions | [View](../operations/GetCustomersCustomerBalanceTransactions.md) |
| POST | `/v1/customers/{customer}/balance_transactions` | Create a customer balance transaction | [View](../operations/PostCustomersCustomerBalanceTransactions.md) |
| GET | `/v1/customers/{customer}/balance_transactions/{transaction}` | Retrieve a customer balance transaction | [View](../operations/GetCustomersCustomerBalanceTransactionsTransaction.md) |
| POST | `/v1/customers/{customer}/balance_transactions/{transaction}` | Update a customer credit balance transaction | [View](../operations/PostCustomersCustomerBalanceTransactionsTransaction.md) |
| GET | `/v1/customers/{customer}/bank_accounts` | List all bank accounts | [View](../operations/GetCustomersCustomerBankAccounts.md) |
| POST | `/v1/customers/{customer}/bank_accounts` | Create a card | [View](../operations/PostCustomersCustomerBankAccounts.md) |
| GET | `/v1/customers/{customer}/bank_accounts/{id}` | Retrieve a bank account | [View](../operations/GetCustomersCustomerBankAccountsId.md) |
| POST | `/v1/customers/{customer}/bank_accounts/{id}` |  | [View](../operations/PostCustomersCustomerBankAccountsId.md) |
| DELETE | `/v1/customers/{customer}/bank_accounts/{id}` | Delete a customer source | [View](../operations/DeleteCustomersCustomerBankAccountsId.md) |
| POST | `/v1/customers/{customer}/bank_accounts/{id}/verify` | Verify a bank account | [View](../operations/PostCustomersCustomerBankAccountsIdVerify.md) |
| GET | `/v1/customers/{customer}/cards` | List all cards | [View](../operations/GetCustomersCustomerCards.md) |
| POST | `/v1/customers/{customer}/cards` | Create a card | [View](../operations/PostCustomersCustomerCards.md) |
| GET | `/v1/customers/{customer}/cards/{id}` | Retrieve a card | [View](../operations/GetCustomersCustomerCardsId.md) |
| POST | `/v1/customers/{customer}/cards/{id}` |  | [View](../operations/PostCustomersCustomerCardsId.md) |
| DELETE | `/v1/customers/{customer}/cards/{id}` | Delete a customer source | [View](../operations/DeleteCustomersCustomerCardsId.md) |
| GET | `/v1/customers/{customer}/cash_balance` | Retrieve a cash balance | [View](../operations/GetCustomersCustomerCashBalance.md) |
| POST | `/v1/customers/{customer}/cash_balance` | Update a cash balance's settings | [View](../operations/PostCustomersCustomerCashBalance.md) |
| GET | `/v1/customers/{customer}/cash_balance_transactions` | List cash balance transactions | [View](../operations/GetCustomersCustomerCashBalanceTransactions.md) |
| GET | `/v1/customers/{customer}/cash_balance_transactions/{transaction}` | Retrieve a cash balance transaction | [View](../operations/GetCustomersCustomerCashBalanceTransactionsTransaction.md) |
| GET | `/v1/customers/{customer}/discount` |  | [View](../operations/GetCustomersCustomerDiscount.md) |
| DELETE | `/v1/customers/{customer}/discount` | Delete a customer discount | [View](../operations/DeleteCustomersCustomerDiscount.md) |
| POST | `/v1/customers/{customer}/funding_instructions` | Create or retrieve funding instructions for a customer cash balance | [View](../operations/PostCustomersCustomerFundingInstructions.md) |
| GET | `/v1/customers/{customer}/payment_methods` | List a Customer's PaymentMethods | [View](../operations/GetCustomersCustomerPaymentMethods.md) |
| GET | `/v1/customers/{customer}/payment_methods/{payment_method}` | Retrieve a Customer's PaymentMethod | [View](../operations/GetCustomersCustomerPaymentMethodsPaymentMethod.md) |
| GET | `/v1/customers/{customer}/sources` |  | [View](../operations/GetCustomersCustomerSources.md) |
| POST | `/v1/customers/{customer}/sources` | Create a card | [View](../operations/PostCustomersCustomerSources.md) |
| GET | `/v1/customers/{customer}/sources/{id}` |  | [View](../operations/GetCustomersCustomerSourcesId.md) |
| POST | `/v1/customers/{customer}/sources/{id}` |  | [View](../operations/PostCustomersCustomerSourcesId.md) |
| DELETE | `/v1/customers/{customer}/sources/{id}` | Delete a customer source | [View](../operations/DeleteCustomersCustomerSourcesId.md) |
| POST | `/v1/customers/{customer}/sources/{id}/verify` | Verify a bank account | [View](../operations/PostCustomersCustomerSourcesIdVerify.md) |
| GET | `/v1/customers/{customer}/subscriptions` | List active subscriptions | [View](../operations/GetCustomersCustomerSubscriptions.md) |
| POST | `/v1/customers/{customer}/subscriptions` | Create a subscription | [View](../operations/PostCustomersCustomerSubscriptions.md) |
| GET | `/v1/customers/{customer}/subscriptions/{subscription_exposed_id}` | Retrieve a subscription | [View](../operations/GetCustomersCustomerSubscriptionsSubscriptionExposedId.md) |
| POST | `/v1/customers/{customer}/subscriptions/{subscription_exposed_id}` | Update a subscription on a customer | [View](../operations/PostCustomersCustomerSubscriptionsSubscriptionExposedId.md) |
| DELETE | `/v1/customers/{customer}/subscriptions/{subscription_exposed_id}` | Cancel a subscription | [View](../operations/DeleteCustomersCustomerSubscriptionsSubscriptionExposedId.md) |
| GET | `/v1/customers/{customer}/subscriptions/{subscription_exposed_id}/discount` |  | [View](../operations/GetCustomersCustomerSubscriptionsSubscriptionExposedIdDiscount.md) |
| DELETE | `/v1/customers/{customer}/subscriptions/{subscription_exposed_id}/discount` | Delete a customer discount | [View](../operations/DeleteCustomersCustomerSubscriptionsSubscriptionExposedIdDiscount.md) |
| GET | `/v1/customers/{customer}/tax_ids` | List all Customer tax IDs | [View](../operations/GetCustomersCustomerTaxIds.md) |
| POST | `/v1/customers/{customer}/tax_ids` | Create a Customer tax ID | [View](../operations/PostCustomersCustomerTaxIds.md) |
| GET | `/v1/customers/{customer}/tax_ids/{id}` | Retrieve a Customer tax ID | [View](../operations/GetCustomersCustomerTaxIdsId.md) |
| DELETE | `/v1/customers/{customer}/tax_ids/{id}` | Delete a Customer tax ID | [View](../operations/DeleteCustomersCustomerTaxIdsId.md) |
