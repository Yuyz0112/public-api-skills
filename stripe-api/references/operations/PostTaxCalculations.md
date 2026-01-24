# POST /v1/tax/calculations

**Resource:** [tax](../resources/tax.md)
**Create a Tax Calculation**
**Operation ID:** `PostTaxCalculations`

<p>Calculates tax based on the input and returns a Tax <code>Calculation</code> object.</p>

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[tax.calculation](../schemas/tax-calculation/tax-calculation.md)

