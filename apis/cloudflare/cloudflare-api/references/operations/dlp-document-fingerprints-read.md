# GET /accounts/{account_id}/dlp/document_fingerprints/{document_fingerprint_id}

**Resource:** [DLP Document Fingerprints](../resources/DLP-Document-Fingerprints.md)
**Retrieve data about a specific document fingerprint.**
**Operation ID:** `dlp-document-fingerprints-read`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `document_fingerprint_id` | path | string (uuid) | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Document fingerprint read was successful. |
| 4XX | Document fingerprint read failed. |

## Security

- **api_email**
- **api_key**
- **api_token**
