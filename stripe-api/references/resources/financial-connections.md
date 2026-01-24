# financial_connections

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/v1/financial_connections/accounts` | List Accounts | [View](../operations/GetFinancialConnectionsAccounts.md) |
| GET | `/v1/financial_connections/accounts/{account}` | Retrieve an Account | [View](../operations/GetFinancialConnectionsAccountsAccount.md) |
| POST | `/v1/financial_connections/accounts/{account}/disconnect` | Disconnect an Account | [View](../operations/PostFinancialConnectionsAccountsAccountDisconnect.md) |
| GET | `/v1/financial_connections/accounts/{account}/owners` | List Account Owners | [View](../operations/GetFinancialConnectionsAccountsAccountOwners.md) |
| POST | `/v1/financial_connections/accounts/{account}/refresh` | Refresh Account data | [View](../operations/PostFinancialConnectionsAccountsAccountRefresh.md) |
| POST | `/v1/financial_connections/accounts/{account}/subscribe` | Subscribe to data refreshes for an Account | [View](../operations/PostFinancialConnectionsAccountsAccountSubscribe.md) |
| POST | `/v1/financial_connections/accounts/{account}/unsubscribe` | Unsubscribe from data refreshes for an Account | [View](../operations/PostFinancialConnectionsAccountsAccountUnsubscribe.md) |
| POST | `/v1/financial_connections/sessions` | Create a Session | [View](../operations/PostFinancialConnectionsSessions.md) |
| GET | `/v1/financial_connections/sessions/{session}` | Retrieve a Session | [View](../operations/GetFinancialConnectionsSessionsSession.md) |
| GET | `/v1/financial_connections/transactions` | List Transactions | [View](../operations/GetFinancialConnectionsTransactions.md) |
| GET | `/v1/financial_connections/transactions/{transaction}` | Retrieve a Transaction | [View](../operations/GetFinancialConnectionsTransactionsTransaction.md) |
