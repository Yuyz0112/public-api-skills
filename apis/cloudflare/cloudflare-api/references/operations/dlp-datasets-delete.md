# DELETE /accounts/{account_id}/dlp/datasets/{dataset_id}

**Resource:** [DLP Datasets](../resources/DLP-Datasets.md)
**Delete a dataset**
**Operation ID:** `dlp-datasets-delete`

This deletes all versions of the dataset.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `dataset_id` | path | string (uuid) | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Dataset deleted successfully. |
| 4XX | Dataset delete failed. |

## Security

- **api_email**
- **api_key**
- **api_token**
