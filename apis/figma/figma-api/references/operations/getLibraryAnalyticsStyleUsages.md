# GET /v1/analytics/libraries/{file_key}/style/usages

**Resource:** [Library Analytics](../resources/Library-Analytics.md)
**Get library analytics style usage data.**
**Operation ID:** `getLibraryAnalyticsStyleUsages`

Returns a list of library analytics style usage data broken down by the requested dimension.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `file_key` | path | string | Yes | File key of the library to fetch analytics data for. |
| `cursor` | query | string | No | Cursor indicating what page of data to fetch. Obtained from prior API call. |
| `group_by` | query | enum: style, file | Yes | A dimension to group returned analytics data by. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 429 | (reference) |
| 500 | (reference) |

## Security

- **PersonalAccessToken**
- **OAuth2**: library_analytics:read
