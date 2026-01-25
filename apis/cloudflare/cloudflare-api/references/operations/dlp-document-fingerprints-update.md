# POST /accounts/{account_id}/dlp/document_fingerprints/{document_fingerprint_id}

**Resource:** [DLP Document Fingerprints](../resources/DLP-Document-Fingerprints.md)
**Update the attributes of a single document fingerprint.**
**Operation ID:** `dlp-document-fingerprints-update`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `document_fingerprint_id` | path | string (uuid) | Yes |  |

## Request Body

Attributes of the document fingerprint to update.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [dlp_UpdateDocumentFingerprint](../schemas/dlp/dlp-UpdateDocumentFingerprint.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Document fingerprint read was successful. |
| 4XX | Document fingerprint read failed. |

## Security

- **api_email**
- **api_key**
- **api_token**
