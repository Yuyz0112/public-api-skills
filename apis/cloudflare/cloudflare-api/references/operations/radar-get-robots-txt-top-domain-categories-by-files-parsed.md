# GET /radar/robots_txt/top/domain_categories

**Resource:** [Radar Robots.txt](../resources/Radar-Robots-txt.md)
**Get top domain categories by robots.txt files parsed**
**Operation ID:** `radar-get-robots-txt-top-domain-categories-by-files-parsed`

Retrieves the top domain categories by the number of robots.txt files parsed.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `limit` | query | integer | No | Limits the number of objects returned in the response. |
| `name` | query | string[] | No | Array of names used to label the series in the response. |
| `userAgentCategory` | query | enum: AI | No | Filters results by user agent category. |
| `date` | query | string[] | No | Filters results by the specified array of dates. |
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
