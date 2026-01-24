# POST /v1/credit_notes/{id}/void

**Resource:** [credit_notes](../resources/credit-notes.md)
**Void a credit note**
**Operation ID:** `PostCreditNotesIdVoid`

<p>Marks a credit note as void. Learn more about <a href="/docs/billing/invoices/credit-notes#voiding">voiding credit notes</a>.</p>

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

