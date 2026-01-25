# GET /radar/dns/top/locations

**Resource:** [Radar DNS](../resources/Radar-DNS.md)
**Get top locations by DNS queries**
**Operation ID:** `radar-get-dns-top-locations`

Retrieves the top locations by DNS queries made to 1.1.1.1 DNS resolver.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `limit` | query | integer | No | Limits the number of objects returned in the response. |
| `name` | query | string[] | No | Array of names used to label the series in the response. |
| `dateRange` | query | string[] | No | Filters results by date range. For example, use `7d` and `7dcontrol` to compare this week with the previous week. Use this parameter or set specific start and end dates (`dateStart` and `dateEnd` parameters). |
| `dateStart` | query | string[] | No | Start of the date range. |
| `dateEnd` | query | string[] | No | End of the date range (inclusive). |
| `asn` | query | string[] | No | Filters results by Autonomous System. Specify one or more Autonomous System Numbers (ASNs) as a comma-separated list. Prefix with `-` to exclude ASNs from results. For example, `-174, 3356` excludes results from AS174, but includes results from AS3356. |
| `location` | query | string[] | No | Filters results by location. Specify a comma-separated list of alpha-2 codes. Prefix with `-` to exclude locations from results. For example, `-US,PT` excludes results from the US, but includes results from PT. |
| `continent` | query | string[] | No | Filters results by continent. Specify a comma-separated list of alpha-2 codes. Prefix with `-` to exclude continents from results. For example, `-EU,NA` excludes results from EU, but includes results from NA. |
| `domain` | query | string[] | No | Filters results by domain name. |
| `cacheHit` | query | boolean[] | No | Filters results based on cache status. |
| `nodata` | query | boolean[] | No | Specifies whether the response includes empty DNS responses (NODATA). |
| `protocol` | query | string[] | No | Filters results by DNS transport protocol. |
| `queryType` | query | string[] | No | Filters results by DNS query type. |
| `responseCode` | query | string[] | No | Filters results by DNS response code. |
| `responseTtl` | query | string[] | No | Filters results by DNS response TTL. |
| `dnssec` | query | string[] | No | Filters results based on DNSSEC (DNS Security Extensions) support. |
| `dnssecAware` | query | string[] | No | Filters results based on DNSSEC (DNS Security Extensions) client awareness. |
| `dnssecE2e` | query | boolean[] | No | Filters results based on DNSSEC-validated answers by end-to-end security status. |
| `ipVersion` | query | string[] | No | Filters results by IP version (Ipv4 vs. IPv6). |
| `matchingAnswer` | query | boolean[] | No | Filters results based on whether the queries have a matching answer. |
| `tld` | query | string[] | No | Filters results by top-level domain. |
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
