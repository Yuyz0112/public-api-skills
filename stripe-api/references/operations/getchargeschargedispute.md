# GET /v1/charges/{charge}/dispute

**Resource:** [charges](../resources/charges.md)
**Operation ID:** `GetChargesChargeDispute`

<p>Retrieve a dispute for a specified charge.</p>

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

[dispute](../schemas/dispute/dispute.md)

