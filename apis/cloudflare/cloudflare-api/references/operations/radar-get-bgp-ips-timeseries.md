# GET /radar/bgp/ips/timeseries

**Resource:** [Radar BGP](../resources/Radar-BGP.md)
**Get announced IP address space time series**
**Operation ID:** `radar-get-bgp-ips-timeseries`

Retrieves time series data for the announced IP space count, represented as the number of IPv4 /24s and IPv6 /48s, for a given ASN.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `name` | query | string[] | No | Array of names used to label the series in the response. |
| `dateRange` | query | string[] | No | Filters results by date range. For example, use `7d` and `7dcontrol` to compare this week with the previous week. Use this parameter or set specific start and end dates (`dateStart` and `dateEnd` parameters). |
| `dateStart` | query | string[] | No | Start of the date range. |
| `dateEnd` | query | string[] | No | End of the date range (inclusive). |
| `asn` | query | string[] | No | Filters results by Autonomous System. Specify one or more Autonomous System Numbers (ASNs) as a comma-separated list. Prefix with `-` to exclude ASNs from results. For example, `-174, 3356` excludes results from AS174, but includes results from AS3356. |
| `location` | query | string[] | No | Filters results by location. Specify a comma-separated list of alpha-2 location codes. |
| `ipVersion` | query | string[] | No | Filters results by IP version (Ipv4 vs. IPv6). |
| `includeDelay` | query | boolean | No | Includes data delay meta information. |
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
