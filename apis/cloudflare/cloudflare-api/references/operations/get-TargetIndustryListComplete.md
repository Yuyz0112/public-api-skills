# GET /accounts/{account_id}/cloudforce-one/events/targetIndustries/catalog

**Resource:** [Target Industry](../resources/Target-Industry.md)
**Lists all target industries from industry map catalog**
**Operation ID:** `get_TargetIndustryListComplete`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns all target industries from industry map catalog. |
| 400 | Bad Request. |

## Security

- **api_token**
