# GET /2/communities/{id}

**Resource:** [Communities](../resources/Communities.md)
**Get Community by ID**
**Operation ID:** `getCommunitiesById`

Retrieves details of a specific Community by its ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | CommunityId | Yes | The ID of the Community. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[Get2CommunitiesIdResponse](../schemas/Get/Get2CommunitiesIdResponse.md)

## Security

- **BearerToken**
- **OAuth2UserToken**: list.read, tweet.read, users.read
- **UserToken**
