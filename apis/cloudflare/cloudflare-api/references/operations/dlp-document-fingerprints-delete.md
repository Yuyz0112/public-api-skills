# DELETE /accounts/{account_id}/dlp/document_fingerprints/{document_fingerprint_id}

**Resource:** [DLP Document Fingerprints](../resources/DLP-Document-Fingerprints.md)
**Delete a single document fingerprint.**
**Operation ID:** `dlp-document-fingerprints-delete`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `document_fingerprint_id` | path | string (uuid) | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Document fingerprint delete was successful. |
| 4XX | Document fingerprint delete failed. |

## Security

- **api_email**
- **api_key**
- **api_token**
