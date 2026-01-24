# GET /v1/tax/calculations/{calculation}

**Resource:** [tax](../resources/tax.md)
**Retrieve a Tax Calculation**
**Operation ID:** `GetTaxCalculationsCalculation`

<p>Retrieves a Tax <code>Calculation</code> object, if the calculation hasn’t expired.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `calculation` | path | string | Yes |  |
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[tax.calculation](../schemas/tax-calculation/tax-calculation.md)

