# POST /user/tokens

**Resource:** [User API Tokens](../resources/User-API-Tokens.md)
**Create Token**
**Operation ID:** `user-api-tokens-create-token`

Create a new access token.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [iam_create_payload](../schemas/iam/iam-create-payload.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create Token response |
| 4XX | Create Token response failure |

**Success Response Schema:**

[iam_single_token_create_response](../schemas/iam/iam-single-token-create-response.md)

## Security

- **api_token**
