# tax

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/v1/tax/associations/find` | Find a Tax Association | [View](../operations/GetTaxAssociationsFind.md) |
| POST | `/v1/tax/calculations` | Create a Tax Calculation | [View](../operations/PostTaxCalculations.md) |
| GET | `/v1/tax/calculations/{calculation}` | Retrieve a Tax Calculation | [View](../operations/GetTaxCalculationsCalculation.md) |
| GET | `/v1/tax/calculations/{calculation}/line_items` | Retrieve a calculation's line items | [View](../operations/GetTaxCalculationsCalculationLineItems.md) |
| GET | `/v1/tax/registrations` | List registrations | [View](../operations/GetTaxRegistrations.md) |
| POST | `/v1/tax/registrations` | Create a registration | [View](../operations/PostTaxRegistrations.md) |
| GET | `/v1/tax/registrations/{id}` | Retrieve a registration | [View](../operations/GetTaxRegistrationsId.md) |
| POST | `/v1/tax/registrations/{id}` | Update a registration | [View](../operations/PostTaxRegistrationsId.md) |
| GET | `/v1/tax/settings` | Retrieve settings | [View](../operations/GetTaxSettings.md) |
| POST | `/v1/tax/settings` | Update settings | [View](../operations/PostTaxSettings.md) |
| POST | `/v1/tax/transactions/create_from_calculation` | Create a transaction from a calculation | [View](../operations/PostTaxTransactionsCreateFromCalculation.md) |
| POST | `/v1/tax/transactions/create_reversal` | Create a reversal transaction | [View](../operations/PostTaxTransactionsCreateReversal.md) |
| GET | `/v1/tax/transactions/{transaction}` | Retrieve a transaction | [View](../operations/GetTaxTransactionsTransaction.md) |
| GET | `/v1/tax/transactions/{transaction}/line_items` | Retrieve a transaction's line items | [View](../operations/GetTaxTransactionsTransactionLineItems.md) |
