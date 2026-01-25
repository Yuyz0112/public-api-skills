# GET /radar/bgp/hijacks/events

**Resource:** [Radar BGP](../resources/Radar-BGP.md)
**Get BGP hijack events**
**Operation ID:** `radar-get-bgp-hijacks-events`

Retrieves the BGP hijack events.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `page` | query | integer | No | Current page number, starting from 1. |
| `per_page` | query | integer | No | Number of entries per page. |
| `eventId` | query | integer | No | The unique identifier of a event. |
| `hijackerAsn` | query | integer | No | The potential hijacker AS of a BGP hijack event. |
| `victimAsn` | query | integer | No | The potential victim AS of a BGP hijack event. |
| `involvedAsn` | query | integer | No | The potential hijacker or victim AS of a BGP hijack event. |
| `involvedCountry` | query | string | No | The country code of the potential hijacker or victim AS of a BGP hijack event. |
| `prefix` | query | string | No |  |
| `minConfidence` | query | integer | No | Filters events by minimum confidence score (1-4 low, 5-7 mid, 8+ high). |
| `maxConfidence` | query | integer | No | Filters events by maximum confidence score (1-4 low, 5-7 mid, 8+ high). |
| `dateRange` | query | string | No | Filters results by date range. |
| `dateStart` | query | string (date-time) | No | Start of the date range (inclusive). |
| `dateEnd` | query | string (date-time) | No | End of the date range (inclusive). |
| `sortBy` | query | enum: ID, TIME, CONFIDENCE | No | Sorts results by the specified field. |
| `sortOrder` | query | enum: ASC, DESC | No | Sort order. |
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
