# GET /zones/{zone_id}/speed_api/pages/{url}/trend

**Resource:** [Observatory](../resources/Observatory.md)
**List core web vital metrics trend**
**Operation ID:** `speed-list-page-trend`

Lists the core web vital metrics trend over time for a specific page.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | observatory_identifier | Yes |  |
| `url` | path | observatory_url | Yes |  |
| `region` | query | observatory_region | Yes |  |
| `deviceType` | query | observatory_device_type | Yes |  |
| `start` | query | observatory_timestamp | Yes |  |
| `end` | query | observatory_timestamp | No |  |
| `tz` | query | string | Yes | The timezone of the start and end timestamps. |
| `metrics` | query | string | Yes | A comma-separated list of metrics to include in the results. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Page trend. |
| 4XX | Failure response. |

**Success Response Schema:**

[observatory_trend-response](../schemas/observatory/observatory-trend-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
