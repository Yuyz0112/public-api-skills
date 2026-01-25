# GET /radar/http/top/locations/ip_version/{ip_version}

**Resource:** [Radar HTTP](../resources/Radar-HTTP.md)
**Get top locations by HTTP requests for an IP version**
**Operation ID:** `radar-get-http-top-locations-by-ip-version`

Retrieves the top locations, by HTTP requests, of the requested IP version.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `ip_version` | path | enum: IPv4, IPv6 | Yes | IP version. |
| `limit` | query | integer | No | Limits the number of objects returned in the response. |
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
| `os` | query | string[] | No | Filters results by operating system. |
| `tlsVersion` | query | string[] | No | Filters results by TLS version. |
| `browserFamily` | query | string[] | No | Filters results by browser family. |
| `format` | query | enum: JSON, CSV | No | Format in which results will be returned. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| 404 | Not found. |

## Security

- **api_email**
- **api_key**
- **api_token**
