# GET /accounts/{account_id}/dlp/document_fingerprints

**Resource:** [DLP Document Fingerprints](../resources/DLP-Document-Fingerprints.md)
**Retrieve data about all document fingerprints.**
**Operation ID:** `dlp-document-fingerprints-read-all`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Document fingerprint read was successful. |
| 4XX | Document fingerprint read failed. |

## Security

- **api_email**
- **api_key**
- **api_token**
