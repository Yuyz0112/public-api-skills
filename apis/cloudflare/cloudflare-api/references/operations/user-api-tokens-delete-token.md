# DELETE /user/tokens/{token_id}

**Resource:** [User API Tokens](../resources/User-API-Tokens.md)
**Delete Token**
**Operation ID:** `user-api-tokens-delete-token`

Destroy a token.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token_id` | path | iam_token_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete Token response |
| 4XX | Delete Token response failure |

**Success Response Schema:**

[iam_api-response-single-id](../schemas/iam/iam-api-response-single-id.md)

## Security

- **api_token**
