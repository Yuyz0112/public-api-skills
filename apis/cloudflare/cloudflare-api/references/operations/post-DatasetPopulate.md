# POST /accounts/{account_id}/cloudforce-one/events/datasets/populate

**Resource:** [Datasets](../resources/Datasets.md)
**Populate dataset-specific lookup tables from existing Events data with batch processing**
**Operation ID:** `post_DatasetPopulate`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns population results with counts and any errors |
| 400 | Bad Request. |

## Security

- **api_token**
