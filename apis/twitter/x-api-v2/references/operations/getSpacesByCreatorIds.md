# GET /2/spaces/by/creator_ids

**Resource:** [Spaces](../resources/Spaces.md)
**Get Spaces by creator IDs**
**Operation ID:** `getSpacesByCreatorIds`

Retrieves details of Spaces created by specified User IDs.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `user_ids` | query | UserId[] | Yes | The IDs of Users to search through. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[Get2SpacesByCreatorIdsResponse](../schemas/Get/Get2SpacesByCreatorIdsResponse.md)

## Security

- **BearerToken**
- **OAuth2UserToken**: space.read, tweet.read, users.read
