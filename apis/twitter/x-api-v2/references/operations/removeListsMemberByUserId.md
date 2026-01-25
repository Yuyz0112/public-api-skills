# DELETE /2/lists/{id}/members/{user_id}

**Resource:** [Lists](../resources/Lists.md)
**Remove List member**
**Operation ID:** `removeListsMemberByUserId`

Removes a User from a specific List by its ID and the User’s ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | ListId | Yes | The ID of the List to remove a member. |
| `user_id` | path | UserId | Yes | The ID of User that will be removed from the List. |

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
