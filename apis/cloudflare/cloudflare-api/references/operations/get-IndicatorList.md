# GET /accounts/{account_id}/cloudforce-one/events/indicators

**Resource:** [Indicator](../resources/Indicator.md)
**Lists indicators across multiple datasets**
**Operation ID:** `get_IndicatorList`

Retrieves a paginated list of indicators across specified datasets. Use datasetIds=all or datasetIds=* to query all datasets for the account. If no datasetIds provided, uses the default dataset.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |
| `datasetIds` | query | string[] | No | Dataset IDs to query indicators from (array of UUIDs), or special value 'all' or '*' to query all datasets. If not provided, uses the default dataset. |
| `page` | query | number | No |  |
| `pageSize` | query | number | No |  |
| `search` | query | string | No |  |
| `indicatorType` | query | string | No |  |
| `relatedEvents` | query | string[] | No | Filter by related event IDs |
| `tags` | query | string[] | No | Filter by tag values or UUIDs. Indicators must have at least one of the specified tags (OR logic). Supports both tag UUID and tag value. |
| `createdAfter` | query | string (date-time) | No | Filter indicators created on or after this date. Must use ISO 8601 format (e.g., '2024-01-15T00:00:00Z'). |
| `createdBefore` | query | string (date-time) | No | Filter indicators created on or before this date. Must use ISO 8601 format (e.g., '2024-12-31T23:59:59Z'). |
| `relatedEventsLimit` | query | number | No | Limit the number of related events returned per indicator. Default: 2. Set to 0 for none, -1 for all events. |
| `includeTags` | query | boolean | No | Whether to include full tag details for each indicator. Defaults to false for performance. |
| `includeTotalCount` | query | boolean | No | Whether to compute accurate total count via COUNT(*). Defaults to false for performance. When false, total_count is an approximation. |
| `format` | query | enum: json, stix2 | No | Output format for indicator data. 'json' returns the default format, 'stix2' returns STIX 2.1 Indicator SDOs. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns a paginated list of indicators. |
| 400 | Bad Request. |

## Security

- **api_token**
