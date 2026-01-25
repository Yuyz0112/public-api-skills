# GET /radar/attacks/layer7/summary/http_version

**Resource:** [Radar Layer 7 Attacks](../resources/Radar-Layer-7-Attacks.md)
**Get layer 7 attacks by HTTP version summary**
**Operation ID:** `radar-get-attacks-layer7-summary-by-http-version`
⚠️ **Deprecated**

Retrieves the distribution of layer 7 attacks by HTTP version.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `name` | query | string[] | No | Array of names used to label the series in the response. |
| `dateRange` | query | string[] | No | Filters results by date range. For example, use `7d` and `7dcontrol` to compare this week with the previous week. Use this parameter or set specific start and end dates (`dateStart` and `dateEnd` parameters). |
| `dateStart` | query | string[] | No | Start of the date range. |
| `dateEnd` | query | string[] | No | End of the date range (inclusive). |
| `asn` | query | string[] | No | Filters results by Autonomous System. Specify one or more Autonomous System Numbers (ASNs) as a comma-separated list. Prefix with `-` to exclude ASNs from results. For example, `-174, 3356` excludes results from AS174, but includes results from AS3356. |
| `location` | query | string[] | No | Filters results by location. Specify a comma-separated list of alpha-2 codes. Prefix with `-` to exclude locations from results. For example, `-US,PT` excludes results from the US, but includes results from PT. |
| `continent` | query | string[] | No | Filters results by continent. Specify a comma-separated list of alpha-2 codes. Prefix with `-` to exclude continents from results. For example, `-EU,NA` excludes results from EU, but includes results from NA. |
| `ipVersion` | query | string[] | No | Filters results by IP version (Ipv4 vs. IPv6). |
| `httpMethod` | query | string[] | No | Filters results by HTTP method. |
| `mitigationProduct` | query | string[] | No | Filters the results by layer 7 mitigation product. |
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
