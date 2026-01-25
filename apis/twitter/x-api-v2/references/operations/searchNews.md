# GET /2/news/search

**Resource:** [News](../resources/News.md)
**Search News**
**Operation ID:** `searchNews`

Retrieves a list of News stories matching the specified search query.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `query` | query | string | Yes | The search query. |
| `max_results` | query | integer (int32) | No | The number of results to return. |
| `max_age_hours` | query | integer (int32) | No | The maximum age of the News story to search for. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[Get2NewsSearchResponse](../schemas/Get/Get2NewsSearchResponse.md)

## Security

- **BearerToken**
- **OAuth2UserToken**: tweet.read, users.read
