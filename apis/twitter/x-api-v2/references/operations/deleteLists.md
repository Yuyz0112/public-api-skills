# DELETE /2/lists/{id}

**Resource:** [Lists](../resources/Lists.md)
**Delete List**
**Operation ID:** `deleteLists`

Deletes a specific List owned by the authenticated user by its ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | ListId | Yes | The ID of the List to delete. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[ListDeleteResponse](../schemas/List/ListDeleteResponse.md)

## Security

- **OAuth2UserToken**: list.write, tweet.read, users.read
- **UserToken**
