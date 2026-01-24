# POST /v1/tax/transactions/create_reversal

**Resource:** [tax](../resources/tax.md)
**Create a reversal transaction**
**Operation ID:** `PostTaxTransactionsCreateReversal`

<p>Partially or fully reverses a previously created <code>Transaction</code>.</p>

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

