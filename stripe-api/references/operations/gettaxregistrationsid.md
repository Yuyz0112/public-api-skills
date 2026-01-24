# GET /v1/tax/registrations/{id}

**Resource:** [tax](../resources/tax.md)
**Retrieve a registration**
**Operation ID:** `GetTaxRegistrationsId`

<p>Returns a Tax <code>Registration</code> object.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `id` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[tax.registration](../schemas/tax-registration/tax-registration.md)

