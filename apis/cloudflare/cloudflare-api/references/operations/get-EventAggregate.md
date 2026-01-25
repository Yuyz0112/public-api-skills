# GET /accounts/{account_id}/cloudforce-one/events/aggregate

**Resource:** [Event](../resources/Event.md)
**Aggregate events by single or multiple columns with optional date filtering**
**Operation ID:** `get_EventAggregate`

Aggregate threat events by one or more columns (e.g., attacker, targetIndustry) with optional date filtering and daily grouping. Supports multi-dimensional aggregation for cross-analysis.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |
| `aggregateBy` | query | string | Yes | Column(s) to aggregate by - single column or comma-separated list (e.g., 'attacker', 'targetIndustry', 'attacker,targetIndustry') |
| `datasetId` | query | any | No | Dataset ID(s) to filter by. Can be a single dataset ID or array of dataset IDs. If not provided, uses default dataset |
| `startDate` | query | string | No | Start date for filtering (ISO 8601 format, e.g., '2024-01-01') |
| `endDate` | query | string | No | End date for filtering (ISO 8601 format, e.g., '2024-12-31') |
| `groupByDate` | query | boolean | No | Whether to group results by date (daily aggregation) |
| `limit` | query | number | No | Maximum number of results to return |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns aggregated event data. |
| 400 | Bad Request. |

## Security

- **api_token**
