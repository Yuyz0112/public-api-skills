# GET /accounts/{account_id}/cloudforce-one/events/dataset

**Resource:** [Dataset](../resources/Dataset.md)
**Lists all datasets in an account**
**Operation ID:** `get_DatasetList`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns a list of dataset in an account. |
| 400 | Bad Request. |

## Security

- **api_token**
