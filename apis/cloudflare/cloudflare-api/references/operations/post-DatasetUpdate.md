# POST /accounts/{account_id}/cloudforce-one/events/dataset/{dataset_id}

**Resource:** [Dataset](../resources/Dataset.md)
**Updates an existing dataset**
**Operation ID:** `post_DatasetUpdate`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |
| `dataset_id` | path | string (uuid) | Yes | Dataset ID. |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns dataset information. |
| 400 | Bad Request. |

## Security

- **api_token**
