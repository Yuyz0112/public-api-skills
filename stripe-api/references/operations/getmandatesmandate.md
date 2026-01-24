# GET /v1/mandates/{mandate}

**Resource:** [mandates](../resources/mandates.md)
**Retrieve a Mandate**
**Operation ID:** `GetMandatesMandate`

<p>Retrieves a Mandate object.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `mandate` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[mandate](../schemas/mandate/mandate.md)

