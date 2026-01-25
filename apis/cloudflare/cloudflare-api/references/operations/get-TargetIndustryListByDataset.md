# GET /accounts/{account_id}/cloudforce-one/events/dataset/{dataset_id}/targetIndustries

**Resource:** [Target Industry](../resources/Target-Industry.md)
**Lists all target industries for a specific dataset**
**Operation ID:** `get_TargetIndustryListByDataset`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |
| `dataset_id` | path | string (uuid) | Yes | Dataset UUID. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns a list of target industries for the dataset. |
| 400 | Bad Request. |

## Security

- **api_token**
