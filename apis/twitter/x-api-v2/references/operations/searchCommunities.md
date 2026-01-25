# GET /2/communities/search

**Resource:** [Communities](../resources/Communities.md)
**Search Communities**
**Operation ID:** `searchCommunities`

Retrieves a list of Communities matching the specified search query.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `query` | query | string | Yes | Query to search communities. |
| `max_results` | query | integer (int32) | No | The maximum number of search results to be returned by a request. |
| `next_token` | query | NextToken | No | This parameter is used to get the next 'page' of results. The value used with the parameter is pulled directly from the response provided by the API, and should not be modified. |
| `pagination_token` | query | NextToken | No | This parameter is used to get the next 'page' of results. The value used with the parameter is pulled directly from the response provided by the API, and should not be modified. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[Get2CommunitiesSearchResponse](../schemas/Get/Get2CommunitiesSearchResponse.md)

## Security

- **OAuth2UserToken**: tweet.read, users.read
- **UserToken**
