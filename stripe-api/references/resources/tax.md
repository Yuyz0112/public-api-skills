# tax

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/v1/tax/associations/find` | Find a Tax Association | [View](../operations/gettaxassociationsfind.md) |
| POST | `/v1/tax/calculations` | Create a Tax Calculation | [View](../operations/posttaxcalculations.md) |
| GET | `/v1/tax/calculations/{calculation}` | Retrieve a Tax Calculation | [View](../operations/gettaxcalculationscalculation.md) |
| GET | `/v1/tax/calculations/{calculation}/line_items` | Retrieve a calculation's line items | [View](../operations/gettaxcalculationscalculationlineitems.md) |
| GET | `/v1/tax/registrations` | List registrations | [View](../operations/gettaxregistrations.md) |
| POST | `/v1/tax/registrations` | Create a registration | [View](../operations/posttaxregistrations.md) |
| GET | `/v1/tax/registrations/{id}` | Retrieve a registration | [View](../operations/gettaxregistrationsid.md) |
| POST | `/v1/tax/registrations/{id}` | Update a registration | [View](../operations/posttaxregistrationsid.md) |
| GET | `/v1/tax/settings` | Retrieve settings | [View](../operations/gettaxsettings.md) |
| POST | `/v1/tax/settings` | Update settings | [View](../operations/posttaxsettings.md) |
| POST | `/v1/tax/transactions/create_from_calculation` | Create a transaction from a calculation | [View](../operations/posttaxtransactionscreatefromcalculation.md) |
| POST | `/v1/tax/transactions/create_reversal` | Create a reversal transaction | [View](../operations/posttaxtransactionscreatereversal.md) |
| GET | `/v1/tax/transactions/{transaction}` | Retrieve a transaction | [View](../operations/gettaxtransactionstransaction.md) |
| GET | `/v1/tax/transactions/{transaction}/line_items` | Retrieve a transaction's line items | [View](../operations/gettaxtransactionstransactionlineitems.md) |
