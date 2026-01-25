# GET /radar/annotations

**Resource:** [Radar Annotations](../resources/Radar-Annotations.md)
**Get latest annotations**
**Operation ID:** `radar-get-annotations`

Retrieves the latest annotations.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `limit` | query | integer | No | Limits the number of objects returned in the response. |
| `offset` | query | integer | No | Skips the specified number of objects before fetching the results. |
| `dateRange` | query | string | No | Filters results by date range. |
| `dateStart` | query | string (date-time) | No | Start of the date range (inclusive). |
| `dateEnd` | query | string (date-time) | No | End of the date range (inclusive). |
| `dataSource` | query | enum: ALL, AI_BOTS, AI_GATEWAY... | No | Filters results by data source. |
| `eventType` | query | enum: EVENT, GENERAL, OUTAGE... | No | Filters results by event type. |
| `asn` | query | integer | No | Filters results by Autonomous System. Specify a single Autonomous System Number (ASN) as integer. |
| `location` | query | string | No | Filters results by location. Specify an alpha-2 location code. |
| `origin` | query | string | No | Filters results by origin. |
| `format` | query | enum: JSON, CSV | No | Format in which results will be returned. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| 400 | Bad request. |

## Security

- **api_email**
- **api_key**
- **api_token**
