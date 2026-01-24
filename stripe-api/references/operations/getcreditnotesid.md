# GET /v1/credit_notes/{id}

**Resource:** [credit_notes](../resources/credit-notes.md)
**Retrieve a credit note**
**Operation ID:** `GetCreditNotesId`

<p>Retrieves the credit note object with the given identifier.</p>

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

[credit_note](../schemas/credit/credit-note.md)

