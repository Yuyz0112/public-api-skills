# GET /v1/charges/{charge}

**Resource:** [charges](../resources/charges.md)
**Retrieve a charge**
**Operation ID:** `GetChargesCharge`

<p>Retrieves the details of a charge that has previously been created. Supply the unique charge ID that was returned from your previous request, and Stripe will return the corresponding charge information. The same information is returned when creating or refunding the charge.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `charge` | path | string | Yes |  |
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[charge](../schemas/charge/charge.md)

