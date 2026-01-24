# POST /v1/tax/transactions/create_from_calculation

**Resource:** [tax](../resources/tax.md)
**Create a transaction from a calculation**
**Operation ID:** `PostTaxTransactionsCreateFromCalculation`

<p>Creates a Tax Transaction from a calculation, if that calculation hasn’t expired. Calculations expire after 90 days.</p>

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[tax.transaction](../schemas/tax-transaction/tax-transaction.md)

