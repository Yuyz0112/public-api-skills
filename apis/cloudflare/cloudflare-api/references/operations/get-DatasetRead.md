# GET /accounts/{account_id}/cloudforce-one/events/dataset/{dataset_id}

**Resource:** [Dataset](../resources/Dataset.md)
**Reads a dataset**
**Operation ID:** `get_DatasetRead`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |
| `dataset_id` | path | string (uuid) | Yes | Dataset ID. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns a dataset. |
| 400 | Bad Request. |

## Security

- **api_token**
