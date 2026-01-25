# POST /2/users/{id}/pinned_lists

**Resource:** [Lists](../resources/Lists.md)
**Pin List**
**Operation ID:** `pinList`

Causes the authenticated user to pin a specific List by its ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | UserIdMatchesAuthenticatedUser | Yes | The ID of the authenticated source User that will pin the List. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [ListPinnedRequest](../schemas/List/ListPinnedRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[ListPinnedResponse](../schemas/List/ListPinnedResponse.md)

## Security

- **OAuth2UserToken**: list.write, tweet.read, users.read
- **UserToken**
