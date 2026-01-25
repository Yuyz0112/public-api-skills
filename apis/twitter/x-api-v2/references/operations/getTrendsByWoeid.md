# GET /2/trends/by/woeid/{woeid}

**Resource:** [Trends](../resources/Trends.md)
**Get Trends by WOEID**
**Operation ID:** `getTrendsByWoeid`

Retrieves trending topics for a specific location identified by its WOEID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `woeid` | path | integer (int32) | Yes | The WOEID of the place to lookup a trend for. |
| `max_trends` | query | integer (int32) | No | The maximum number of results. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[Get2TrendsByWoeidWoeidResponse](../schemas/Get/Get2TrendsByWoeidWoeidResponse.md)

## Security

- **BearerToken**
