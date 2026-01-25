# GET /accounts/{account_id}/cloudforce-one/events/targetIndustries

**Resource:** [Target Industry](../resources/Target-Industry.md)
**Lists target industries across multiple datasets**
**Operation ID:** `get_TargetIndustryList`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |
| `datasetIds` | query | string[] | No | Array of dataset IDs to query target industries from. If not provided, uses the default dataset. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns a list of target industries. |
| 400 | Bad Request. |

## Security

- **api_token**
