# PUT /accounts/{account_id}/dlp/datasets/{dataset_id}

**Resource:** [DLP Datasets](../resources/DLP-Datasets.md)
**Update details about a dataset**
**Operation ID:** `dlp-datasets-update`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `dataset_id` | path | string (uuid) | Yes |  |

## Request Body

Dataset description.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Dataset updated successfully. |
| 4XX | Dataset update failed. |

## Security

- **api_email**
- **api_key**
- **api_token**
