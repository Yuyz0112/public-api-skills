# POST /v1/tax_rates

**Resource:** [tax_rates](../resources/tax-rates.md)
**Create a tax rate**
**Operation ID:** `PostTaxRates`

<p>Creates a new tax rate.</p>

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[tax_rate](../schemas/tax/tax-rate.md)

