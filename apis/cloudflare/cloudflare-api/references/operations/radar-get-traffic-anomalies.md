# GET /radar/traffic_anomalies

**Resource:** [Radar Traffic Anomalies](../resources/Radar-Traffic-Anomalies.md)
**Get latest Internet traffic anomalies**
**Operation ID:** `radar-get-traffic-anomalies`

Retrieves the latest Internet traffic anomalies, which are signals that might indicate an outage. These alerts are automatically detected by Radar and manually verified by our team.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `limit` | query | integer | No | Limits the number of objects returned in the response. |
| `offset` | query | integer | No | Skips the specified number of objects before fetching the results. |
| `dateRange` | query | string | No | Filters results by date range. |
| `dateStart` | query | string (date-time) | No | Start of the date range (inclusive). |
| `dateEnd` | query | string (date-time) | No | End of the date range (inclusive). |
| `status` | query | enum: VERIFIED, UNVERIFIED | No |  |
| `type` | query | string[] | No | Filters results by entity type (LOCATION, AS, or ORIGIN). |
| `asn` | query | integer | No | Filters results by Autonomous System. Specify a single Autonomous System Number (ASN) as integer. |
| `location` | query | string | No | Filters results by location. Specify an alpha-2 location code. |
| `origin` | query | string | No | Filters results by origin. |
| `format` | query | enum: JSON, CSV | No | Format in which results will be returned. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List of Internet traffic anomalies. |
| 400 | Bad request. |

## Security

- **api_email**
- **api_key**
- **api_token**
