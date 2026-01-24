# POST /v1/tax_rates/{tax_rate}

**Resource:** [tax_rates](../resources/tax-rates.md)
**Update a tax rate**
**Operation ID:** `PostTaxRatesTaxRate`

<p>Updates an existing tax rate.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `tax_rate` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[tax_rate](../schemas/tax/tax-rate.md)

