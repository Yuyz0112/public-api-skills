# GET /radar/bots/summary/{dimension}

**Resource:** [Radar Bots](../resources/Radar-Bots.md)
**Get bots HTTP requests distribution by dimension**
**Operation ID:** `radar-get-bots-summary`

Retrieves an aggregated summary of bots HTTP requests grouped by the specified dimension.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `dimension` | path | enum: BOT, BOT_KIND, BOT_OPERATOR... | Yes | Specifies the attribute by which to group the results. |
| `name` | query | string[] | No | Array of names used to label the series in the response. |
| `dateRange` | query | string[] | No | Filters results by date range. For example, use `7d` and `7dcontrol` to compare this week with the previous week. Use this parameter or set specific start and end dates (`dateStart` and `dateEnd` parameters). |
| `dateStart` | query | string[] | No | Start of the date range. |
| `dateEnd` | query | string[] | No | End of the date range (inclusive). |
| `asn` | query | string[] | No | Filters results by Autonomous System. Specify one or more Autonomous System Numbers (ASNs) as a comma-separated list. Prefix with `-` to exclude ASNs from results. For example, `-174, 3356` excludes results from AS174, but includes results from AS3356. |
| `location` | query | string[] | No | Filters results by location. Specify a comma-separated list of alpha-2 codes. Prefix with `-` to exclude locations from results. For example, `-US,PT` excludes results from the US, but includes results from PT. |
| `continent` | query | string[] | No | Filters results by continent. Specify a comma-separated list of alpha-2 codes. Prefix with `-` to exclude continents from results. For example, `-EU,NA` excludes results from EU, but includes results from NA. |
| `limitPerGroup` | query | integer | No | Limits the number of objects per group to the top items within the specified time range. When item count exceeds the limit, extra items appear grouped under an "other" category. |
| `bot` | query | string[] | No | Filters results by bot name. |
| `botOperator` | query | string[] | No | Filters results by bot operator. |
| `botCategory` | query | string[] | No | Filters results by bot category. |
| `botKind` | query | string[] | No | Filters results by bot kind. |
| `botVerificationStatus` | query | string[] | No | Filters results by bot verification status (Verified vs. Unverified). |
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
