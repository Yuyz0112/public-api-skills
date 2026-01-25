# POST /2/lists

**Resource:** [Lists](../resources/Lists.md)
**Create List**
**Operation ID:** `createLists`

Creates a new List for the authenticated user.

## Request Body

**Content Types:** `application/json`

**Schema:** [ListCreateRequest](../schemas/List/ListCreateRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[ListCreateResponse](../schemas/List/ListCreateResponse.md)

## Security

- **OAuth2UserToken**: list.read, list.write, tweet.read, users.read
- **UserToken**
