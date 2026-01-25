# PUT /accounts/{account_id}/dlp/document_fingerprints/{document_fingerprint_id}

**Resource:** [DLP Document Fingerprints](../resources/DLP-Document-Fingerprints.md)
**Uploads a new version for a document fingerprint.**
**Operation ID:** `dlp-document-fingerprints-upload`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `document_fingerprint_id` | path | string (uuid) | Yes |  |

## Request Body

File used for document fingerprinting.

**Required:** Yes

**Content Types:** `multipart/form-data`

## Responses

| Status | Description |
|--------|-------------|
| 200 | File uploaded successfully. |
| 4XX | Failed to upload file. |

## Security

- **api_email**
- **api_key**
- **api_token**
