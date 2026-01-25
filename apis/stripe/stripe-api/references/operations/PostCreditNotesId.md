# POST /v1/credit_notes/{id}

**Resource:** [credit_notes](../resources/credit-notes.md)
**Update a credit note**
**Operation ID:** `PostCreditNotesId`

<p>Updates an existing credit note.</p>

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

[credit_note](../schemas/credit/credit-note.md)

