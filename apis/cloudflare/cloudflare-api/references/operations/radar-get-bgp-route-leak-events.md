# GET /radar/bgp/leaks/events

**Resource:** [Radar BGP](../resources/Radar-BGP.md)
**Get BGP route leak events**
**Operation ID:** `radar-get-bgp-route-leak-events`

Retrieves the BGP route leak events.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `page` | query | integer | No | Current page number, starting from 1. |
| `per_page` | query | integer | No | Number of entries per page. |
| `eventId` | query | integer | No | The unique identifier of a event. |
| `leakAsn` | query | integer | No | The leaking AS of a route leak event. |
| `involvedAsn` | query | integer | No | ASN that is causing or affected by a route leak event. |
| `involvedCountry` | query | string | No | Country code of a involved ASN in a route leak event. |
| `dateRange` | query | string | No | Filters results by date range. |
| `dateStart` | query | string (date-time) | No | Start of the date range (inclusive). |
| `dateEnd` | query | string (date-time) | No | End of the date range (inclusive). |
| `sortBy` | query | enum: ID, LEAKS, PEERS... | No | Sorts results by the specified field. |
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
