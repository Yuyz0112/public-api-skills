# GET /radar/attacks/layer3/top/attacks

**Resource:** [Radar Layer 3 Attacks](../resources/Radar-Layer-3-Attacks.md)
**Get top layer 3 attack pairs (origin and target locations)**
**Operation ID:** `radar-get-attacks-layer3-top-attacks`

Retrieves the top layer 3 attacks from origin to target location. Values are a percentage out of the total layer 3 attacks (with billing country). You can optionally limit the number of attacks by origin/target location (useful if all the top attacks are from or to the same location).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `limit` | query | integer | No | Limits the number of objects returned in the response. |
| `name` | query | string[] | No | Array of names used to label the series in the response. |
| `dateRange` | query | string[] | No | Filters results by date range. For example, use `7d` and `7dcontrol` to compare this week with the previous week. Use this parameter or set specific start and end dates (`dateStart` and `dateEnd` parameters). |
| `dateStart` | query | string[] | No | Start of the date range. |
| `dateEnd` | query | string[] | No | End of the date range (inclusive). |
| `location` | query | string[] | No | Filters results by location. Specify a comma-separated list of alpha-2 codes. Prefix with `-` to exclude locations from results. For example, `-US,PT` excludes results from the US, but includes results from PT. |
| `continent` | query | string[] | No | Filters results by continent. Specify a comma-separated list of alpha-2 codes. Prefix with `-` to exclude continents from results. For example, `-EU,NA` excludes results from EU, but includes results from NA. |
| `ipVersion` | query | string[] | No | Filters results by IP version (Ipv4 vs. IPv6). |
| `protocol` | query | string[] | No | Filters the results by layer 3/4 protocol. |
| `limitDirection` | query | enum: ORIGIN, TARGET | No | Specifies whether the `limitPerLocation` applies to the source or target location. |
| `limitPerLocation` | query | integer | No | Limits the number of attacks per origin/target (refer to `limitDirection` parameter) location. |
| `magnitude` | query | enum: MITIGATED_BYTES, MITIGATED_ATTACKS | No | Orders results based on attack magnitude, defined by total mitigated bytes or total mitigated attacks. |
| `normalization` | query | enum: PERCENTAGE, MIN_MAX | No | Normalization method applied to the results. Refer to [Normalization methods](https://developers.cloudflare.com/radar/concepts/normalization/). |
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
