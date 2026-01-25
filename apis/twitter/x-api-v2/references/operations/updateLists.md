# PUT /2/lists/{id}

**Resource:** [Lists](../resources/Lists.md)
**Update List**
**Operation ID:** `updateLists`

Updates the details of a specific List owned by the authenticated user by its ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | ListId | Yes | The ID of the List to modify. |

## Request Body

**Content Types:** `application/json`

**Schema:** [ListUpdateRequest](../schemas/List/ListUpdateRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[ListUpdateResponse](../schemas/List/ListUpdateResponse.md)

## Security

- **OAuth2UserToken**: list.write, tweet.read, users.read
- **UserToken**
