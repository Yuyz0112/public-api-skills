# GET /radar/traffic_anomalies/locations

**Resource:** [Radar Traffic Anomalies](../resources/Radar-Traffic-Anomalies.md)
**Get top locations by total traffic anomalies**
**Operation ID:** `radar-get-traffic-anomalies-top`

Retrieves the sum of Internet traffic anomalies, grouped by location. These anomalies are signals that might indicate an outage, automatically detected by Radar and manually verified by our team.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `limit` | query | integer | No | Limits the number of objects returned in the response. |
| `dateRange` | query | string | No | Filters results by date range. |
| `dateStart` | query | string (date-time) | No | Start of the date range (inclusive). |
| `dateEnd` | query | string (date-time) | No | End of the date range (inclusive). |
| `status` | query | enum: VERIFIED, UNVERIFIED | No |  |
| `format` | query | enum: JSON, CSV | No | Format in which results will be returned. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List of locations with number of traffic anomalies. |
| 400 | Bad request. |

## Security

- **api_email**
- **api_key**
- **api_token**
