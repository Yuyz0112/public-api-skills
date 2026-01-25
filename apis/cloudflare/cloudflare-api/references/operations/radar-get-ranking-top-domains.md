# GET /radar/ranking/top

**Resource:** [Radar Domains Ranking](../resources/Radar-Domains-Ranking.md)
**Get top or trending domains**
**Operation ID:** `radar-get-ranking-top-domains`

Retrieves the top or trending domains based on their rank. Popular domains are domains of broad appeal based on how people use the Internet. Trending domains are domains that are generating a surge in interest. For more information on top domains, see https://blog.cloudflare.com/radar-domain-rankings/.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `limit` | query | integer | No | Limits the number of objects returned in the response. |
| `name` | query | string[] | No | Array of names used to label the series in the response. |
| `location` | query | string[] | No | Filters results by location. Specify a comma-separated list of alpha-2 location codes. |
| `domainCategory` | query | string[] | No | Filters results by domain category. |
| `date` | query | string[] | No | Filters results by the specified array of dates. |
| `rankingType` | query | enum: POPULAR, TRENDING_RISE, TRENDING_STEADY | No | The ranking type. |
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
