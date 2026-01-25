# POST /accounts/{account_id}/dlp/datasets/{dataset_id}/upload/{version}

**Resource:** [DLP Datasets](../resources/DLP-Datasets.md)
**Upload a new version of a dataset**
**Operation ID:** `dlp-datasets-upload-version`

This is used for single-column EDMv1 and Custom Word Lists. The EDM format
can only be created in the Cloudflare dashboard. For other clients, this
operation can only be used for non-secret Custom Word Lists. The body must
be a UTF-8 encoded, newline (NL or CRNL) separated list of words to be matched.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `dataset_id` | path | string (uuid) | Yes |  |
| `version` | path | integer (int64) | Yes |  |

## Request Body

Dataset. For custom wordlists this contains UTF-8 patterns separated by newline characters.

**Required:** Yes

**Content Types:** `application/octet-stream`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Dataset version uploaded successfully. |
| 4XX | Dataset version upload failed. |

## Security

- **api_email**
- **api_key**
- **api_token**
