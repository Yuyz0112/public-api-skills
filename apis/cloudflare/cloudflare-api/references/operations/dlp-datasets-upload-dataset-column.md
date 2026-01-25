# POST /accounts/{account_id}/dlp/datasets/{dataset_id}/versions/{version}/entries/{entry_id}

**Resource:** [DLP Datasets](../resources/DLP-Datasets.md)
**Upload a new version of a multi-column dataset**
**Operation ID:** `dlp-datasets-upload-dataset-column`

This is used for multi-column EDMv2 datasets. The EDMv2 format can only be
created in the Cloudflare dashboard.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `dataset_id` | path | string (uuid) | Yes |  |
| `version` | path | integer (int64) | Yes |  |
| `entry_id` | path | string (uuid) | Yes |  |

## Request Body

Dataset content.

**Required:** Yes

**Content Types:** `application/octet-stream`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Dataset column uploaded successfully. |
| 4XX | Failed to upload dataset column. |

## Security

- **api_email**
- **api_key**
- **api_token**
