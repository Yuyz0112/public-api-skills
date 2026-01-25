# GET /2/news/{id}

**Resource:** [News](../resources/News.md)
**Get news stories by ID**
**Operation ID:** `getNews`

Retrieves news story by its ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | NewsId | Yes | The ID of the news story. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[Get2NewsIdResponse](../schemas/Get/Get2NewsIdResponse.md)

## Security

- **BearerToken**
- **OAuth2UserToken**: tweet.read, users.read
- **UserToken**
