# POST /accounts/{account_id}/dlp/document_fingerprints

**Resource:** [DLP Document Fingerprints](../resources/DLP-Document-Fingerprints.md)
**Creates a new document fingerprint.**
**Operation ID:** `dlp-document-fingerprints-create`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |

## Request Body

Attributes of the new document fingerprint.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Document fingerprint created successfully. |
| 4XX | Document fingerprint creation failed. |

## Security

- **api_email**
- **api_key**
- **api_token**
