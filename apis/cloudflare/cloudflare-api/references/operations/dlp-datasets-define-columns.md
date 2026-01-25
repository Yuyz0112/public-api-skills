# POST /accounts/{account_id}/dlp/datasets/{dataset_id}/versions/{version}

**Resource:** [DLP Datasets](../resources/DLP-Datasets.md)
**Sets the column information for a multi-column upload**
**Operation ID:** `dlp-datasets-define-columns`

This is used for multi-column EDMv2 datasets. The EDMv2 format can only be
created in the Cloudflare dashboard. The columns in the response appear in
the same order as in the request.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `dataset_id` | path | string (uuid) | Yes |  |
| `version` | path | integer (int64) | Yes |  |

## Request Body

array of new columns to create for this dataset version.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Dataset columns created successfully. |
| 4XX | Failed to create dataset columns. |

## Security

- **api_email**
- **api_key**
- **api_token**
