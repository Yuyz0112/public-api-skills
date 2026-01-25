# GET /accounts/{account_id}/dlp/datasets

**Resource:** [DLP Datasets](../resources/DLP-Datasets.md)
**Fetch all datasets**
**Operation ID:** `dlp-datasets-read-all`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Datasets read successfully. |
| 4XX | Datasets read failed. |

## Security

- **api_email**
- **api_key**
- **api_token**
