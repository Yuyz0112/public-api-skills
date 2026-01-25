# GET /2/lists/{id}

**Resource:** [Lists](../resources/Lists.md)
**Get List by ID**
**Operation ID:** `getListsById`

Retrieves details of a specific List by its ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | ListId | Yes | The ID of the List. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[Get2ListsIdResponse](../schemas/Get/Get2ListsIdResponse.md)

## Security

- **BearerToken**
- **OAuth2UserToken**: list.read, tweet.read, users.read
- **UserToken**
