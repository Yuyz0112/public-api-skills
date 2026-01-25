# GET /accounts/{account_id}/cloudforce-one/events/dataset/{dataset_id}/indicators

**Resource:** [Indicator](../resources/Indicator.md)
**Lists indicators**
**Operation ID:** `get_IndicatorListLegacy`

Retrieves a paginated list of indicators for the account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |
| `dataset_id` | path | string (uuid) | Yes | Dataset UUID. |
| `page` | query | number | No |  |
| `pageSize` | query | number | No |  |
| `search` | query | string | No |  |
| `indicatorType` | query | string | No |  |
| `relatedEvent` | query | string[] | No | Filter indicators by related event UUID(s). Multiple UUIDs can be provided by repeating the parameter. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns a list of indicators. |

## Security

- **api_token**
