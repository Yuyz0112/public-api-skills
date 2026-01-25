# GET /radar/ranking/internet_services/top

**Resource:** [Radar Internet Services Ranking](../resources/Radar-Internet-Services-Ranking.md)
**Get top Internet services**
**Operation ID:** `radar-get-ranking-top-internet-services`

Retrieves top Internet services based on their rank.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `serviceCategory` | query | string[] | No | Filters results by Internet service category. |
| `limit` | query | integer | No | Limits the number of objects returned in the response. |
| `name` | query | string[] | No | Array of names used to label the series in the response. |
| `date` | query | string[] | No | Filters results by the specified array of dates. |
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
