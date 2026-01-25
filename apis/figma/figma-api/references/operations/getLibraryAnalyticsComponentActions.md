# GET /v1/analytics/libraries/{file_key}/component/actions

**Resource:** [Library Analytics](../resources/Library-Analytics.md)
**Get library analytics component action data.**
**Operation ID:** `getLibraryAnalyticsComponentActions`

Returns a list of library analytics component actions data broken down by the requested dimension.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `file_key` | path | string | Yes | File key of the library to fetch analytics data for. |
| `cursor` | query | string | No | Cursor indicating what page of data to fetch. Obtained from prior API call. |
| `group_by` | query | enum: component, team | Yes | A dimension to group returned analytics data by. |
| `start_date` | query | string | No | ISO 8601 date string (YYYY-MM-DD) of the earliest week to include. Dates are rounded back to the nearest start of a week. Defaults to one year prior. |
| `end_date` | query | string | No | ISO 8601 date string (YYYY-MM-DD) of the latest week to include. Dates are rounded forward to the nearest end of a week. Defaults to the latest computed week. |

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
