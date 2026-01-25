# GET /radar/attacks/layer3/timeseries_groups/{dimension}

**Resource:** [Radar Layer 3 Attacks](../resources/Radar-Layer-3-Attacks.md)
**Get layer 3 attacks time series grouped by dimension**
**Operation ID:** `radar-get-attacks-layer3-timeseries-group`

Retrieves the distribution of layer 3 attacks grouped by dimension over time.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `dimension` | path | enum: PROTOCOL, IP_VERSION, VECTOR... | Yes | Specifies the attribute by which to group the results. |
| `aggInterval` | query | enum: 15m, 1h, 1d... | No | Aggregation interval of the results (e.g., in 15 minutes or 1 hour intervals). Refer to [Aggregation intervals](https://developers.cloudflare.com/radar/concepts/aggregation-intervals/). |
| `name` | query | string[] | No | Array of names used to label the series in the response. |
| `dateRange` | query | string[] | No | Filters results by date range. For example, use `7d` and `7dcontrol` to compare this week with the previous week. Use this parameter or set specific start and end dates (`dateStart` and `dateEnd` parameters). |
| `dateStart` | query | string[] | No | Start of the date range. |
| `dateEnd` | query | string[] | No | End of the date range (inclusive). |
| `location` | query | string[] | No | Filters results by location. Specify a comma-separated list of alpha-2 codes. Prefix with `-` to exclude locations from results. For example, `-US,PT` excludes results from the US, but includes results from PT. |
| `continent` | query | string[] | No | Filters results by continent. Specify a comma-separated list of alpha-2 codes. Prefix with `-` to exclude continents from results. For example, `-EU,NA` excludes results from EU, but includes results from NA. |
| `ipVersion` | query | string[] | No | Filters results by IP version (Ipv4 vs. IPv6). |
| `protocol` | query | string[] | No | Filters the results by layer 3/4 protocol. |
| `normalization` | query | enum: PERCENTAGE, MIN0_MAX | No | Normalization method applied to the results. Refer to [Normalization methods](https://developers.cloudflare.com/radar/concepts/normalization/). |
| `direction` | query | enum: ORIGIN, TARGET | No | Specifies whether the `location` filter applies to the source or target location. |
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
