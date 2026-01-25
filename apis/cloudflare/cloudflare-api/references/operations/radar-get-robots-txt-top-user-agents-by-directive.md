# GET /radar/robots_txt/top/user_agents/directive

**Resource:** [Radar Robots.txt](../resources/Radar-Robots-txt.md)
**Get top user agents on robots.txt files**
**Operation ID:** `radar-get-robots-txt-top-user-agents-by-directive`

Retrieves the top user agents on robots.txt files.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `limit` | query | integer | No | Limits the number of objects returned in the response. |
| `name` | query | string[] | No | Array of names used to label the series in the response. |
| `userAgentCategory` | query | enum: AI | No | Filters results by user agent category. |
| `date` | query | string[] | No | Filters results by the specified array of dates. |
| `domainCategory` | query | string[] | No | Filters results by domain category. |
| `directive` | query | enum: ALLOW, DISALLOW | No | Filters results by robots.txt directive. |
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
