# POST /2/lists/{id}/members

**Resource:** [Lists](../resources/Lists.md)
**Add List member**
**Operation ID:** `addListsMember`

Adds a User to a specific List by its ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | ListId | Yes | The ID of the List for which to add a member. |

## Request Body

**Content Types:** `application/json`

**Schema:** [ListAddUserRequest](../schemas/List/ListAddUserRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[ListMutateResponse](../schemas/List/ListMutateResponse.md)

## Security

- **OAuth2UserToken**: list.write, tweet.read, users.read
- **UserToken**
