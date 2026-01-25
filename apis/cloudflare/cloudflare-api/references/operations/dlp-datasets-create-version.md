# POST /accounts/{account_id}/dlp/datasets/{dataset_id}/upload

**Resource:** [DLP Datasets](../resources/DLP-Datasets.md)
**Prepare to upload a new version of a dataset**
**Operation ID:** `dlp-datasets-create-version`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `dataset_id` | path | string (uuid) | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Dataset version created successfully. |
| 4XX | Dataset version creation failed. |

## Security

- **api_email**
- **api_key**
- **api_token**
