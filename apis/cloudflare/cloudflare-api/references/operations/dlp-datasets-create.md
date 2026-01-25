# POST /accounts/{account_id}/dlp/datasets

**Resource:** [DLP Datasets](../resources/DLP-Datasets.md)
**Create a new dataset**
**Operation ID:** `dlp-datasets-create`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |

## Request Body

Dataset description.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Dataset created successfully. |
| 4XX | Dataset creation failed. |

## Security

- **api_email**
- **api_key**
- **api_token**
