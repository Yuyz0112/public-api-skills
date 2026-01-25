# GET /radar/http/timeseries_groups/browser

**Resource:** [Radar HTTP](../resources/Radar-HTTP.md)
**Get HTTP requests by user agent time series**
**Operation ID:** `radar-get-http-timeseries-group-by-browsers`
⚠️ **Deprecated**

Retrieves the distribution of HTTP requests by user agent over time.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `aggInterval` | query | enum: 15m, 1h, 1d... | No | Aggregation interval of the results (e.g., in 15 minutes or 1 hour intervals). Refer to [Aggregation intervals](https://developers.cloudflare.com/radar/concepts/aggregation-intervals/). |
| `name` | query | string[] | No | Array of names used to label the series in the response. |
| `dateRange` | query | string[] | No | Filters results by date range. For example, use `7d` and `7dcontrol` to compare this week with the previous week. Use this parameter or set specific start and end dates (`dateStart` and `dateEnd` parameters). |
| `dateStart` | query | string[] | No | Start of the date range. |
| `dateEnd` | query | string[] | No | End of the date range (inclusive). |
| `asn` | query | string[] | No | Filters results by Autonomous System. Specify one or more Autonomous System Numbers (ASNs) as a comma-separated list. Prefix with `-` to exclude ASNs from results. For example, `-174, 3356` excludes results from AS174, but includes results from AS3356. |
| `location` | query | string[] | No | Filters results by location. Specify a comma-separated list of alpha-2 codes. Prefix with `-` to exclude locations from results. For example, `-US,PT` excludes results from the US, but includes results from PT. |
| `continent` | query | string[] | No | Filters results by continent. Specify a comma-separated list of alpha-2 codes. Prefix with `-` to exclude continents from results. For example, `-EU,NA` excludes results from EU, but includes results from NA. |
| `geoId` | query | string[] | No | Filters results by Geolocation. Specify a comma-separated list of GeoNames IDs. Prefix with `-` to exclude geoIds from results. For example, `-2267056,360689` excludes results from the 2267056 (Lisbon), but includes results from 5128638 (New York). |
| `botClass` | query | string[] | No | Filters results by bot class. Refer to [Bot classes](https://developers.cloudflare.com/radar/concepts/bot-classes/). |
| `deviceType` | query | string[] | No | Filters results by device type. |
| `httpProtocol` | query | string[] | No | Filters results by HTTP protocol (HTTP vs. HTTPS). |
| `httpVersion` | query | string[] | No | Filters results by HTTP version. |
| `ipVersion` | query | string[] | No | Filters results by IP version (Ipv4 vs. IPv6). |
| `os` | query | string[] | No | Filters results by operating system. |
| `tlsVersion` | query | string[] | No | Filters results by TLS version. |
| `browserFamily` | query | string[] | No | Filters results by browser family. |
| `limitPerGroup` | query | integer | No | Limits the number of objects per group to the top items within the specified time range. When item count exceeds the limit, extra items appear grouped under an "other" category. |
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
