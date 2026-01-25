# POST /v1/tax/registrations

**Resource:** [tax](../resources/tax.md)
**Create a registration**
**Operation ID:** `PostTaxRegistrations`

<p>Creates a new Tax <code>Registration</code> object.</p>

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[tax.registration](../schemas/tax-registration/tax-registration.md)

