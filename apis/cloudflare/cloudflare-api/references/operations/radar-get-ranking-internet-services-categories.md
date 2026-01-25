# GET /radar/ranking/internet_services/categories

**Resource:** [Radar Internet Services Ranking](../resources/Radar-Internet-Services-Ranking.md)
**List Internet services categories**
**Operation ID:** `radar-get-ranking-internet-services-categories`

Retrieves the list of Internet services categories.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
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
