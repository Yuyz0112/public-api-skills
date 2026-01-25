# DELETE /accounts/{account_id}/cloudforce-one/events/dataset/{dataset_id}

**Resource:** [Dataset](../resources/Dataset.md)
**Delete a dataset**
**Operation ID:** `delete_DatasetDelete`

Deletes a dataset given a datasetId.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |
| `dataset_id` | path | string | Yes | Dataset ID to delete |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns the uuid and name of the deleted dataset. |
| 400 | Bad Request. |
| 404 | Bad Request. |

## Security

- **api_token**
