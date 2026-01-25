# POST /v1/tax/registrations/{id}

**Resource:** [tax](../resources/tax.md)
**Update a registration**
**Operation ID:** `PostTaxRegistrationsId`

<p>Updates an existing Tax <code>Registration</code> object.</p>

<p>A registration cannot be deleted after it has been created. If you wish to end a registration you may do so by setting <code>expires_at</code>.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
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

