# GET /radar/bots

**Resource:** [Radar Bots](../resources/Radar-Bots.md)
**List bots**
**Operation ID:** `radar-get-bots`

Retrieves a list of bots.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `limit` | query | integer | No | Limits the number of objects returned in the response. |
| `offset` | query | integer | No | Skips the specified number of objects before fetching the results. |
| `botCategory` | query | enum: SEARCH_ENGINE_CRAWLER, SEARCH_ENGINE_OPTIMIZATION, MONITORING_AND_ANALYTICS... | No | Filters results by bot category. |
| `botOperator` | query | string | No | Filters results by bot operator. |
| `kind` | query | enum: AGENT, BOT | No | Filters results by bot kind. |
| `botVerificationStatus` | query | enum: VERIFIED | No | Filters results by bot verification status. |
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
