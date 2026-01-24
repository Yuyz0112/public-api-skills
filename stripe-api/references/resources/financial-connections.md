# financial_connections

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/v1/financial_connections/accounts` | List Accounts | [View](../operations/getfinancialconnectionsaccounts.md) |
| GET | `/v1/financial_connections/accounts/{account}` | Retrieve an Account | [View](../operations/getfinancialconnectionsaccountsaccount.md) |
| POST | `/v1/financial_connections/accounts/{account}/disconnect` | Disconnect an Account | [View](../operations/postfinancialconnectionsaccountsaccountdisconnect.md) |
| GET | `/v1/financial_connections/accounts/{account}/owners` | List Account Owners | [View](../operations/getfinancialconnectionsaccountsaccountowners.md) |
| POST | `/v1/financial_connections/accounts/{account}/refresh` | Refresh Account data | [View](../operations/postfinancialconnectionsaccountsaccountrefresh.md) |
| POST | `/v1/financial_connections/accounts/{account}/subscribe` | Subscribe to data refreshes for an Account | [View](../operations/postfinancialconnectionsaccountsaccountsubscribe.md) |
| POST | `/v1/financial_connections/accounts/{account}/unsubscribe` | Unsubscribe from data refreshes for an Account | [View](../operations/postfinancialconnectionsaccountsaccountunsubscribe.md) |
| POST | `/v1/financial_connections/sessions` | Create a Session | [View](../operations/postfinancialconnectionssessions.md) |
| GET | `/v1/financial_connections/sessions/{session}` | Retrieve a Session | [View](../operations/getfinancialconnectionssessionssession.md) |
| GET | `/v1/financial_connections/transactions` | List Transactions | [View](../operations/getfinancialconnectionstransactions.md) |
| GET | `/v1/financial_connections/transactions/{transaction}` | Retrieve a Transaction | [View](../operations/getfinancialconnectionstransactionstransaction.md) |
