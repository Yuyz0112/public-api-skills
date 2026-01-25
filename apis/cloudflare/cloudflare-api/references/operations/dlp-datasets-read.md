# GET /accounts/{account_id}/dlp/datasets/{dataset_id}

**Resource:** [DLP Datasets](../resources/DLP-Datasets.md)
**Fetch a specific dataset**
**Operation ID:** `dlp-datasets-read`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `dataset_id` | path | string (uuid) | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Dataset read successfully. |
| 4XX | Dataset read failed. |

## Security

- **api_email**
- **api_key**
- **api_token**
