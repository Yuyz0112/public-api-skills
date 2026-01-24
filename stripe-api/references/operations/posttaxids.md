# POST /v1/tax_ids

**Resource:** [tax_ids](../resources/tax-ids.md)
**Create a tax ID**
**Operation ID:** `PostTaxIds`

<p>Creates a new account or customer <code>tax_id</code> object.</p>

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[tax_id](../schemas/tax/tax-id.md)

